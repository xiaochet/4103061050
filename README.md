
<!DOCTYPE html>
<html>
<title>顯示你的畫面大小</title>
<body>
<p id="demo1"></p>
<p id="demo2"></p>

<button onclick="myFunction()">click me 請點我</button>
<body onload="myFunction()">
<body onresize="myFunction()">
<script>
function myFunction()
{
var wi=window.innerWidth;
var hi=window.innerHeight;
var wo=window.outerWidth;
var ho=window.outerHeight;
x=document.getElementById("demo1");
y=document.getElementById("demo2");
x.innerHTML="innerWidth: " + wi + " innerHeigth: " + hi ;
y.innerHTML="outerWidth: " + wo + " outerHeigth: " + ho ;

}
</script>
</body>
</html>
