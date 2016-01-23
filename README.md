<!DOCTYPE HTML>
<html>
<head>
<meta charset="utf-8">
<title>更多按钮</title>
<style>
#div1 {background:#ff0;height:200px;width:150px;border:1px solid green;}
</style>
<script>
function setColor(color)
{
  var oDiv=document.getElementById('div1');
  
    oDiv.style.background=color;
 
}
</script>
</head>
<body>
<input type="button" value="变红" onmouseover="setColor('red')">
<input type="button" value="变绿" onmouseover="setColor('green')">
<input type="button" value="变黄" onclick="setColor('yellow')">
<div id="div1">
为了您的信息安全。。。。
</div>
</body>
</html>

