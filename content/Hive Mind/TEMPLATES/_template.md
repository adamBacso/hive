---
<%*
 let title=tp.file.title
 if(title.startsWith("Untitled")){
  title=await tp.system.prompt("Title")
  await tp.file.rename(title)
 }
%>
title: "<%title%>"
type: note
tags:
 - 
created: <%tp.file.creation_date(format="YYYY.MM.DD HH:mm")%>
---