

**Chart JS**

Chart js is an alternate and a better option than tables to represent data in a visual manner. 

Canvas: Canvas is almost like img element except it does not have alt or src attribute. Canvas only takes height and width attributes. Canvas in html is typically used for graphics and JavaScript must be used to draw the graphics. An example of how Canvas is defined:

<canvas id="myCanvas" width="200" height="100" style="border:1px solid #000000;">
</canvas>  Taken from w3 school website.

Drawing Shape with Canvas: from w3 schools


<script>
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");
ctx.moveTo(0, 0);
ctx.lineTo(200, 100);
ctx.stroke();
</script>

Applying Colors: 

<script>
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");

// Create gradient
var grd = ctx.createLinearGradient(0, 0, 200, 0);
grd.addColorStop(0, "red");
grd.addColorStop(1, "white");

// Fill with gradient
ctx.fillStyle = grd;
ctx.fillRect(10, 10, 150, 80);
</script>


Drawing text:

<script>
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");
ctx.font = "30px Arial";
ctx.fillText("Hello World", 10, 50);
</script>