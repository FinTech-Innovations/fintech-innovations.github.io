---
layout: default
---

<script type="text/javascript">
function onoff(name){
  currentvalue = document.getElementById(name).value;
  if(currentvalue == "Display Post"){
  
    blogstate = document.getElementById('blog-frame').getAttribute('data-value');
    if(blogstate != "off"){
      document.getElementById(blogstate).value="Display Post";	
    }
    document.getElementById(name).value="Close Post";
    
    switch(name){
      case "grammar":
        document.getElementById('blog-frame').innerHTML='<div text-align="left">Displaying blog post from:</div><a href="https://nordlund.ai/GrammarInPython">https://nordlund.ai/GrammarInPython</a><embed type="text/html" src="https://nordlund.ai/GrammarInPython" width="1000" height="800"></embed>';
        document.getElementById('blog-frame').setAttribute('data-value',name);
        break;
      default:
        document.getElementById(name).value="Display Post";
        document.getElementById('blog-frame').innerHTML='';
        document.getElementById('blog-frame').setAttribute('data-value', 'off');
        break;
    }
  }else{
    document.getElementById(name).value="Display Post";
    document.getElementById('blog-frame').innerHTML='';
    document.getElementById('blog-frame').setAttribute('data-value', 'off');
  }
}
</script>



# FI.lab Blog

Bite-size snippets of FI.lab member research and advising will be posted here from time to time.

**Playing with Grammar in Python**: How can we use Python to extract meaning from sentences?
<input type="button" value="Display Post" id="grammar" onclick='onoff("grammar");'>

<!-- <input type="button" value="Display Post" id="alt" onclick='onoff("alt");'> -->

<div data-value="off" id="blog-frame"></div>
