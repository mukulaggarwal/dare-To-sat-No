<html>
<head>
<style>
#n {
	position: absolute;
	top:100px;
	left: 50px;
	background-color: red;
	color: black;
}
#y {
	position: absolute;
	top:100px;
	left: 100px;
	background-color: green;
	color: black;
}
</style>
	<title> Will you be my girlfriend</title>
</head>
<body>
  <h1> Will you be my girlfriend ?</h1>
  <button type="button" id="y" onclick="myyesFunction()"> Yes</button>
  <button type="button" id="n" onmouseover="myFunction()">No</button>
  <p id="para"> </p>
  <script>
        var i=0;
	function myFunction(){
		document.getElementById("n").style.left = (Math.random() * 500) + "px";
		document.getElementById("n").style.top = (Math.random() * 500) + "px";
		
	}
</script>
<script>
       function myyesFunction() {
       	i = Math.floor(Math.random() * 50) + 1;
	    document.getElementById("para").innerHTML = "You are in waiting list number "+i;
	    alert("BETTER LUCK NEXT TIME....");
	}
</script>
</body>
</html>

