<!DOCTYPE html>
<html>
<head>
<style>
	
h1 {
  position: absolute;
  left: 45%;
}
</style>
</head>
<body>
	<title> The Button </title>
		
	<h1>Are you dumb?</h1>
</body>
<style>



	div {
  width: 100px;
  height: 100px;
  background-color: red;
  position: relative;
  animation-name: example;
  animation-duration: 4s;
  animation-iteration-count: infinite;	
}



.button {
  background-color: #4CAF50; /* Green */
  border: none;
  color: white;
  padding: 10px 24px;
  border-radius: 4px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  transition-duration: 0.4s;
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2), 0 6px 20px 0 rgba(0,0,0,0.19)
}

.button1 {
  background-color: #4CAF50; 
  color: white; 
  position: absolute;
  left: 45%;
  top: 10%;
}

.button1:hover {
  background-color: white;
  color: black;
  border: 4px solid #4CAF50	
}

.button3 {
  background-color: #f44336; 
  color: white;
  position: absolute;
  right: 45%;
  top: 10%;

}

.button3:hover {
  background-color: white;
  color: black; 
  border: 4px solid #f44336;
}

p{
  position: absolute;
  left: 22%;
  top: 15%;
}


</style>

<body>
	<a href="https://m.youtube.com/watch?v=Yb6dZ1IFlKc&ab_channel=ZincMusicProductions">
	<button class="button button1">Yes</button>
	</a>
	
	
	<button class="button button3" onclick="Something()" id ="test">No</button>
	<b>
	<p id = "Hello" style="font-size:700%;"> </p>
 	</b>
	<script>
	function Something(){
	document.getElementById("Hello").innerHTML = "Stop Lying To Yourself!"
	
	}
        </script>
	
	
<html>
