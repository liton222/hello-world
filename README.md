<!DOCTYPE html>
<html lang="en-us">
  <head>
    <title>my javascript </title>
  </head>
  <body>
<button onclick="myMessege1()">Click Me</button>
<button onclick="myMessege2()">Click Me</button>
  <p id="para">Demo</p>

<script>
var myTag=document.querySelector("para");

function myMessege1() {
myTag.innerHTML="I am button 1";
}
function myMessege2() {
myTag.innerHTML ="I am button 2";
}
</script>
</body>
</html>
