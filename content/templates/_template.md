---
<%*
//Change title
 let title=tp.file.title
 if(title.startsWith("Untitled")){
  title=await tp.system.prompt("Title")
  await tp.file.rename(title)
 }
 //Change note type
 const types = ["note", "main_note", "class_note", "template", "other"]
 type=await tp.system.suggester(types, types)
 if (type=="other"){
  type=await tp.system.prompt("Type")
 }
 //Change subject
 const subjects = ["biology", "physics", "geography", "math", "french", "german", "spanish", "history", "magyar", "chemistry", "none"]
 if (type!="none"){
  subj=await tp.system.suggester(subjects, subjects)
 } else {
  subj="none"
 }
 //Tags
 const tags=[subj]
 sep="\n - "
 while (true){
  tag=await tp.system.prompt("Tag:")
  if (tag==""){break}
  tag=tag.split(" ").join("_")
  tags.push(sep)
  tags.push(tag)
 }
 tagF=tags.join("")
%>title: "<%title%>"
alias: 
type: <%type%>
subject: <%subj%>
tags:
 - <%tagF%>
created: <%tp.file.creation_date(format="YYYY.MM.DD HH:mm")%>
created_by: Ádám
TARGET DECK: <%subj%>
summary: 
status: draft
---
