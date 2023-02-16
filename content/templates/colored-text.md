<%*<!--https://www.computerhope.com/jargon/w/w3c-color-names.htm-->
 text=tp.file.selection()
 const cols=["gray", "lightgray", "red", "blue", "green", "orange", "magenta", "CUSTOM"]
 col=await tp.system.suggester(cols,cols)
 if (col=="CUSTOM") {
  col=await tp.system.prompt("Enter preferred color:")
 }
%><font style="color:<%col%>"><%text%></font>