<!doctype html>
<html lang="en">
 <head>
  <meta charset="UTF-8">
  <style>
	{
		margin:0;
		padding:0;
	}
	#box{
		/*background-color:red;*/
		width:auto;
		height:auto;
		position:fixed;
		left:50%;
		top:50%;
		margin-left:-175px;
		margin-top:-75px;
	}
	.bule{
		float:left;
		width:100px;
		height:100px;
		border:10px solid #30f;
		border-radius:50%;
		z-index:2;
	}
	.black{
		float:left;
		margin-left:25px;
		width:100px;
		height:100px;
		border:10px solid black;
		border-radius:50%;
		z-index:0;
	}
	.red{
		float:left;
		margin-left:25px;
		width:100px;
		height:100px;
		border:10px solid red;
		border-radius:50%;
		z-index:1;
	}
	.yellow{
		float:left;
		margin-top:50px;
		margin-left:-340px;
		width:100px;
		height:100px;
		border:10px solid #ff0;
		border-radius:50%;
		z-index:4;
	}
	.green{
		float:left;
		margin-top:50px;
		margin-left:-190px;
		width:100px;
		height:100px;
		border:10px solid #6f0;
		border-radius:50%;
		z-index:5;
	}
	
	
  </style>
  <title>Document</title>
 </head>
 <body>
 	<h1><center>This is the Olympic rings.</center> </h1>
 	<div id="box">
		<span class="bule"></span>
		<span class="black"></span>
		<span class="red"></span>
		<span class="yellow"></span>
		<span class="green"></span>
	</div>
 </body>
</html>

