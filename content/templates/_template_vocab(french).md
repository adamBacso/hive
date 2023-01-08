---
<%*
 //Change title
 let title=tp.file.title
 if(title.startsWith("Untitled")){
  title=await tp.system.prompt("Title")
  await tp.file.rename(title)
 }
 //Change word type
 type=await tp.system.suggester(["noun", "verb", "adjective"], ["noun", "verb", "adjective"])
 //Ask for meaning
 meaning=await tp.system.prompt("Meaning")
%>title: "<%title%>"
alias: 
type: <%type%>
meaning: <%meaning%>
tags:
 - french
 - vocab
 - <%type%>
created: <%tp.file.creation_date(format="YYYY.MM.DD HH:mm")%>
created_by: <%tp.file.cursor(2)%>
---