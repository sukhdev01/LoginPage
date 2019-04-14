<!DOCTYPE html>
<html>
	<head>
		<title "First Login Page"></title>
		<h1 style="text-align: center" style="color: red" >LOGIN PAGE</h1><br><br><br>
	</head>
		<meta name="viewport" content="width=device-width, initial-scale=1">
		<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
	<style>
		.loginButton{
			height:50px;
			width:150px;
			font-size:20px;
			background-color: lawngreen;
			text-align: center;
			border-radius: 20px;
		}
		input[type=text]{
			margin: 8px 0;
			border-radius: 8px;
			padding: 12px 20px;
		}
		.fa{
			padding: 20px;
			font-size: 30px;
			width: 50px;
			text-align: center;
			text-decoration: none;
			margin: 5px 2px;
		}
		.fa-facebook{
			background:#3B5998;
  			color: white;
		}
		.fa-twitter {
			background: #55ACEE;
			color: white;
		}
		.fa-google {
  			background: #dd4b39;
  			color: white;
		}
		.socialMediaLabel{
			padding: 200px 100 px;
			font-size:40px;
			text-align: center;
		}
	</style>
	
	<body style="background-color:powderblue">
		<form>
			<center><label class="socialMediaLabel">Login with Social Accounts</label></center>
			<center>
			<a href="#"class="fa fa-facebook"onclick="alert('logged in with facebook ID')"></a>
			<a href="#" class="fa fa-twitter" onclick="alert('logged in with Twitter ID')"></a>
			<a href="#" class="fa fa-google" onclick="alert('logged in with Google ID')"></a></center><br><br><br><br>
			
			<center><label  class="socialMediaLabel">Login with Email</label></center>
			<center><input type="text" width="20px" placeholder="Email-ID"></center>
			<center><input type="text" placeholder="Password"></center><br>
			<center><button class="loginButton" onclick="alert('logged in')">login</button></center>
		</form>
		
	</body>
</html>
