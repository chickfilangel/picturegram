# picturegram<!DOCTYPE html>
<html>
<head>
	<title>Picturegram</title>

	<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet">


	<style type="text/css">
	 *{
	 	box-sizing: border-box;
	 }
	 h1{
	 	text-align: center;
	 	font-family: Lobster;
	 	font-size: 50px;
	 	margin:0;
	 }
		img {
			width: 200px;
			height:auto;
		}

		#mainpic {
			 width: calc(100% - 10px);
			 height:auto;
			 margin: 5px;
		}

		.smallpic {
			width: calc(33.3333333% - 13px);
			 height: auto;
			 margin: 5px;
		}

		*{box-sizing: border-box;  }
		img:hover {border:2px solid blue;
			cursor: pointer;}

	</style>
	
</head>
<body>
<h1>Picturegram</h1>

<img src="IMG_9027.jpg" id="mainpic"> 
<img src="imagesquare.jpg" class="smallpic"> 
<img src="IMG_8956.jpg" class="smallpic">
<img src="IMG_9026.jpg" class="smallpic">
<img src="IMG_9028.jpg" class="smallpic">
<img src="IMG_9029.jpg" class="smallpic">
<img src="IMG_9031.jpg" class="smallpic">
</body>
</html>
