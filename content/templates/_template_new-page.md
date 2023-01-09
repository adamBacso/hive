<%*
 //Put tags in a string with the right format
 tags=tp.file.tags
 const tagL=[]
 for (tag of tags){
  tag=tag.slice(1)
  tagL.push("\n - ")
  tagL.push(tag)
 }
 tags=tagL.join("")

 //Date (change format as needed)
 date=tp.file.creation_date(format="YYYY.MM.DD HH:mm")

 //Assemble frontmatter of new file
 const front_matter=[]
 front_matter.push("---")
 
 front_matter.push('\ntitle: "')
 front_matter.push(tp.file.selection())
 
 front_matter.push('"\nalias: ')

 front_matter.push("\ntype: ")
 front_matter.push(tp.frontmatter.type)

 front_matter.push("\ntags:")
 front_matter.push(tags)

 front_matter.push("\ncreated: ")
 front_matter.push(date)

 front_matter.push("\ncreated_by: ")
 front_matter.push("Ádám")

 front_matter.push("\ndraft: true")

 front_matter.push("\n---")
 
 fm=front_matter.join("")
 tp.file.create_new(fm,tp.file.selection())
%>[[<%tp.file.selection()%>]]