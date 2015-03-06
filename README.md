# Aula-1-Container

~ HTML ~ 

<!DOCTYPE html>

<html>
<head>
	<title> Atividade </title>
	
	<meta charset="UTF-8" />
	<link rel="stylesheet" href="css/estilos.css" />
	
</head>

<body>
	<div class="container">
		<div class="row">
			<div class="grid12 altura" style="background: green">
			<h1> OlÁ </h1>
			</div>
		</div>
		<div class="row">
			<div class="grid4 altura" style="background: red;">
			<h1> OlÁ </h1>
			</div>
			<div class="grid4 altura" style="background: red;">
			 <h1> OlÁ </h1>
			</div>
			<div class="grid4 altura" style="background: red;">
			<h1> OlÁ </h1>
			</div>
		</div>
		<div class="row">
			<div class="grid6 altura" style="background: yellow">
			<h1> OlÁ </h1>
			</div>
			<div class="grid6 altura" style="background: yellow">
			<h1> OlÁ </h1>
			</div>
		</div>
		<div class="row">
			<div class="grid3 altura" style="background: #FF6600">
			<h1> OlÁ </h1>
			</div>
			<div class="grid3 altura" style="background: #FF6600">
			<h1> OlÁ </h1>
			</div>
			<div class="grid3 altura" style="background: #FF6600">
			<h1> OlÁ </h1>
			</div>
			<div class="grid3 altura" style="background: #FF6600">
			<h1> OlÁ </h1>
			</div>
		</div>
		<div class="row">
			<div class="grid12 altura" style="background: blue">
			<h1> OlÁ </h1>
			</div>
		</div>
	</div>

</body>

</html>

~ FIM HTML ~ 

~ CSS ~ 

body{background: #000;}

.container{
	position: relative;
	margin: 0px auto;
	width: 80%;
	height: auto;
	border: 1px solid #111;
}

.container h1, h2{color: white;}
.container p{color: white;}

.row {
	width: 100%; 
	clear: both; 
}

.container .grid4, .grid6, .grid8, .grid12, .grid3
{
	position: relative;
	float: left;
	height: 200px;	
}

.container .grid3   {width: 24.82%; border: 1px solid #111;}
.container .grid4    {width: 33.15%; border: 1px solid #111;}
.container .grid6    {width: 49.80%; border: 1px solid #111;}
.container .grid12  {width: 99.83%; border: 1px solid #111;}

/* Formatacao Geral */

.container .ftbanner{
	padding-top: 10px;
	padding-bottom: 10px;
	width: 100%; 
	height: 100%;
}

.container .ftfilmes{
	padding-top: 10px;
	padding-bottom: 10px;
	width: 250px; 
	height: 300px;
	padding: 10px;
	margin: 0px;
}

.bkwhite{background: #FFF; display: table;}

.container h1, h2, h3, h4, h5, h6, p{
	padding: 7px;
	margin: 0px;
}

.margintop{margin-top: 15px;}
.paragrafo h2 {font-size:30px; margin-top: 50px; margin-left: 50px;color: #000;background: #FFF; border: 1px solid red;}
.paragrafo p {color: #000; font-size:17px; margin-left: 50px;}
.paragrafo a {color: #CCC; font-size:15px; margin-left: 50px; text-decoration: none;}
.paragrafo a:hover {color: #ccc; font-size:15px; margin-left: 50px; text-decoration: underline;}

/*CALENDARIO*/
.backcompras h3{text-align: center; color: #777;}
.backcompras p{margin-left: 25%; color: #000; margin-top: -15px;}
/*FIM CALENDARIO*/

/* GALERIA */
#galeriaimg img{
	opacity: 0.5;
}

#galeriaimg img:hover{
	opacity: 1.0;	
}
/* FIM GALERIA */

/* BEBIDAS */
.parbebi h2{color: #FF6600;}
.parbebi p{color: #777;}
/* BEBIDAS */

/* HISTORIA */
.hist{color: #000;}	
/* HISTORIA */

/* RODAPE */
.rodape{
	background: #FFF;
	color: #FF6600;
}
.rodape h3{
	text-decoration:underline;
}
.parroda p{ color: #BBB;}
.parroda p:hover{ color: #000; text-decoration: none;}
/* RODAPE */

~ FIM CSS ~ 
