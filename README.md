<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>LibFT</title>
</head>
<style>
	#header 
	{
  		background-color: #000000; /* Grey background */
  		padding: 50px 10px; /* Some padding */
  		color: #ffffff;
  		text-align: center; /* Centered text */
		font-family:Monaco;
  		font-size: 70px; /* Big font size */
  		font-weight: bold;
  		position: fixed; /* Fixed position - sit on top of the page */
  		top: 0;
  		width: 100%; /* Full width */
  		transition: 0.2s; /* Add a transition effect (when scrolling - and font size is decreased) */
	}
	p 
	{
		font-family:Monaco;
	    text-align: justify;
	}
	ul 
	{
  		display: block;
  		list-style-type: square;
  		margin-top: 1em;
 		margin-bottom: 1 em;
		margin-left: 0;
		margin-right: 0;
		padding-left: 40px;
	}
	body 
	{
		background-color: #000000;
		color: #ffffff;
	}
</style>
<body>
	<div id="header">LibFT</div>

<div style="margin-top:200px;padding:15px 15px 2500px;font-size:15px">
  <p><b>After passing through the Piscine this was my first project.</b></p>
  <p>In this library you will find the following functions, working as intended:</p>
  <ul>
	<li>sdesds</li>
  </ul></div>
  
  <p>Scroll to the top to remove the effect.</p>
  <p>Lorem ipsum dolor dummy text sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>


<script>
// When the user scrolls down 50px from the top of the document, resize the header's font size
window.onscroll = function() {scrollFunction()};

function scrollFunction() {
  if (document.body.scrollTop > 30 || document.documentElement.scrollTop > 30) {
    document.getElementById("header").style.fontSize = "30px";
  } else {
    document.getElementById("header").style.fontSize = "70px";
  }
}
</script>

</body>
</html>
