<html>
<head>
<title>Page Title</title>
<style>
body {
  background-color: maroon;
  text-align: left;
  link: teal;
  color: white;
  font-family: Arial, Helvetica, sans-serif;
}
a{
    color: yellow;
    font-family:標楷體;
    text-align: left;
}
</style>
<head>
<body>

<h1>Andy Kuo</h1>
<hr>
<img src="1.jpg" alt="Avatar" style="width:300px" align="center">
<p>NAME : 郭珈源</p>
<p>Constellation : Taurus</p>
<p>STUDY : 
<ul>
  <li>桃園市振聲國中</li>
  <li>桃園市陽明高中</li>
  <li>新竹市清華大學 (資工23)</li>
</ul>
</p>
<p>INTEREST : 
<ol>
       <li>游泳</li>
       <li>健身</li>
       <li>只要遠離原文書就好</li>
</ol> 
</p>
<p>EMAIL : 17831783andy@gmail.com</p>
<p>PHONE : 0968-679-232</p>
<marquee><a href="https://www.google.com/search?q=%E9%87%91%E6%AD%A3%E6%81%A9+%E5%B7%9D%E6%99%AE&sxsrf=ACYBGNQlaFOJXyoJ-vlu9wrH725o7FfJdw:1578495645161&source=lnms&tbm=isch&sa=X&ved=2ahUKEwjD_NXBovTmAhWi7HMBHRYpDTsQ_AUoAXoECAwQAw&biw=1536&bih=731">千萬不要點</a></marquee>

<script language="JavaScript">
function ShowTime(){
　document.getElementById('showbox').innerHTML = new Date();
　setTimeout('ShowTime()',1000);
}
</script>
<body onload="ShowTime()">
<div onclick="ChangeColor('white')" style="background-color: gray; border:3px double; width:150px;height:70px;float:right;">
<div id="showbox"></div>
