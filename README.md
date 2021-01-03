# Proyecto1
<!DOCTYPE HTML>
<html lang="es">
<head>
  <title>*Cosmos Designs*</title>
  <meta charset="UTF-8">
  <meta name="description" content="Pagina de ropa para dama, caballero y niños con diseños variados y distintos">
  <style type="text/css">
  
  * {
		padding:0px;
		margin:0px
	}
  
  #header {
		margin:auto;
		width:1018px;
		font-family:Arial,Helvetica,sans-serif;
	}
  
  ul,ol {
		list-style:none;
	}
  
  .nav li a {
		background-color:#000;
		color:#fff;
		text-decoration:none;
		padding:10px 15px;
		display:block;
	}
  
  .nav li a:hover {
		background-color:#434343;
	}
  
  .nav > li {
		float:left;
	}
  
  
	.nav li ul {
		display:none;
		position:absolute;
		min-width:140px;
	}

	.nav li:hover>ul {
		display:block;
	}
	
	.nav li ul li {
		position:relative;
	}
	
	.nav li ul li ul {
		right:-140px;
		top:0px;
	}
	
	[data-content]{
		display:none;
	}
	
	.active[data-content]{
		display:block;
	}
	
  </style>
  
  <script type="text/javascript" defer>
  
	const targets = document.querySelectorAll("[data-target]")
	const content = document.querySelectorAll)("[data-content]")
	targets.ForEach(target => {
		target.addEventListener("click",()=>{
			content.ForEach(c =>{
				c.classList.remove("active")
			})
			const t = document.querySelector(target.dataset.target)
			t.classList.add("active")
		})
	}
  
  </script>
  
</head>
<body bgcolor="black">
	<div id="header">
		<ul class="nav">
			<li><a href="" data-target="#inicio">Inicio</a></li>
			<li><a href="" data-target="#problematica">Problematica Actual</a></li>
			<li><a href="">Informacion de la Empresa</a>
				<ul>
					<li><a href="" data-target="#general">Proceso General</a></li>
					<li><a href="" data-target="#condiciones">Condiciones del Proceso</a></li>
					<li><a href="" data-target="#bloques">Diagrama de Bloques</a></li>
					<li><a href="" data-target="#casero">Diagrama Nivel Casero</a></li>
					<li><a href="" data-target="#laboratorio">Diagrama Nivel Laboratorio</a></li>
					<li><a href="" data-target="#industrial">Diagrama Nivel Industrial</a></li>
					<li><a href="" data-target="#layout">Lay-Out de la Planta</a></li>
					<li><a href="" data-target="#organigrama">Organigrama de la Empresa</a></li>
					<li><a href="" data-target="#escenarios">Escenarios Economicos</a></li>
					<li><a href="" data-target="#control">Control de Calidad</a></li>
				</ul>
			</li>
			<li><a href="" data-target="#productos">Nuestros Productos</a></li>
			<li><a href="">Sensores y Adquisicion de Datos</a>
				<ul>
					<li><a href="" data-target="#sensores">Sensores</a></li>
					<li><a href="" data-target="#compuestos">Sistemas Compuestos</a></li>
				</ul>
			</li>
			<li><a href="" data-target="#contactos">Contactenos</a></li>
		</ul>
	</div>
<div class="content">

	<div data-content id="inicio" class="active">
		<img src="Inicio PW.png">
	</div>
	
	<div data-content id="problematica">
		<img src="Problematica PW.png">
	</div>
	
	<div data-content id="general">
		<img src="Proceso G PW.png">
	</div>
	
	<div data-content id="condiciones">
		<img src="Condiciones del Proceso PW.png">
	</div>
	
	<div data-content id="bloques">
		<img src="Diagrama de Bloques.png">
	</div>
	
	<div data-content id="casero">
		<img src="Informal PW.png">
	</div>
	
	<div data-content id="laboratorio">
		<img src="Laboratorio PW.png">
	</div>
	
	<div data-content id="industrial">
		<img src="Mercado PW.png">
	</div>
	
	<div data-content id="layout">
		<img src="LayOut PW.png">
	</div>
	
	<div data-content id="organigrama">
		<img src="Organigrama PW.png">
	</div>
	
	<div data-content id="escenarios">
		<img src="Escenarios PW.png">
	</div>
	
	<div data-content id="control">
		<img src="Control de Calidad PW.png">
	</div>
	
	<div data-content id="productos">
		<img src="Productos PW.png">
	</div>
	
	<div data-content id="sensores">
		<img src="Sensores PW.png">
	</div>
	
	<div data-content id="compuestos">
		<img src="SC y AD PW.png">
	</div>
	
	<div data-content id="contactos">
		<img src="Contactos PW.png">
	</div>
	
</body>
</html>
