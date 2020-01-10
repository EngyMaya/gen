<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="UTF-8" name="viewport" content="width=device-width, initial-scale=1"/>
		<link rel="stylesheet" type="text/css" href="css/bootstrap.css"/>
	</head>
<body>
	<nav class="navbar navbar-default"></nav>
	<div class="col-md-3"></div>
	<div class="col-md-6 well">Engy's Creepy Name Gen.</h3>
		<hr style="border-top:1px dotted #ccc;"/>
		<img id="target" height="115px" width="130px"/>
		<h1>The username you could of had.</h1>
		<h5 id="name">user here!</h5>
		<h1>Game you could of made.</h1>
		<h5 id="myHeader">Hello World!</h5>
	</div>
</body>
<script src="JS.js"></script>
<script src="JS2.js"></script>
<script src="JS3.js"></script>
</html>


 
var things = [':)', 'I did the DIE', 'EngyMaya Master!', 'I'm Creepy', 'hmmmmmmmmm...', 'Old roblox is fun, and also creepy.'];
var thing = things[Math.floor(Math.random()*things.length)];
 
document.getElementById("myHeader").innerHTML = [thing];

var usernames = ['SmileForLife', 'DoctorShadow', 'HelpUsWeNeedFriends', 'EngyMaya', 'FrlendsPIease', 'INeedMoreDeadBodys', 'EngyMaya',  'tristanlong2008', 'BOB', 'BADBOB',  'DemonPleaseDie'];
var username = usernames[Math.floor(Math.random()*usernames.length)];
 
document.getElementById("name").innerHTML = [username];
