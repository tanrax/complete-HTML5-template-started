# complete-HTML5-template-started

Modern and complete HTML5 template to start your web pages


<a download target="_blank" href="https://raw.githubusercontent.com/tanrax/complete-HTML5-template-started/master/complete-html5-template-started.html">Descarga versión sin comentarios</a>


## Explanation: Spanish

```html
<!DOCTYPE html>
<!-- Hace saber al navegador que la página esta en castellano -->
<html lang="es">
	<!--Configuraciones-->
	<head>
			<!-- Permite carácteres extraños del alfabeto americano: ñ, á, é... -->
			<meta charset="utf-8">
			<!--Título que aparecerá en la pestaña - La estructura será el nombre de la página actual + Descripción del sitio-->
			<title>Inicio</title>
			<!-- Icono que acompañará al title. También será el icono que se guardará a la hora de que hagan un marcador. Se recomienda un tamaño de 32x32 y en PNG	-->
			<link rel="icon" type="image/png" href="favicon.png">
			<!-- (Opcional) Sugiere un color al navegador para personalizar la ventana en global -->
			<meta name="theme-color" content="#3c790a">
			<!-- (Opcional) Sugiere un color al navegador para personalizar la ventana en modo claro -->
			<meta name="theme-color" 
			      content="#ecd96f" 
			      media="(prefers-color-scheme: light)">
			<!-- (Opcional) Sugiere un color al navegador para personalizar la ventana en modo OSCURO -->
			<meta name="theme-color" 
			      content="#0b3e05" 
			      media="(prefers-color-scheme: dark)">
			<!-- Bloquea el zoom en smartphones-->
			<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no, shrink-to-fit=no">
			<!--Declara quien es el autor. Sin utilidad práctica -->
			<meta name="author" content="Tu nombre">
			<!-- (Opcional) Indica con que tecnologias se ha generado el HTML -->
			<meta name="generator" content="Clojure">
			<!-- Declara palabras claves -->
			<meta name="keywords" content="html, css, javascript">
			<!-- Declara la descripción de la web. Es utilizado por los motores de busqueda para la previa -->
			<meta name="description" content="Descripcion de tu web">
			<!-- Open Graph y Twitter card: Declara como se mostrará la previa del enlace si es compartida por Facebook o alguna otra red social -->
			<meta property="og:image" content="img/miniatura.png">
			<meta property="og:title" content="The Rock">
			<!-- website, video, audio, article, book o profile -->
			<meta property="og:type" content="website">
			<meta property="og:url" content="http://www.imdb.com/title/tt0117500/">
			<meta name="twitter:card" content="summary">
			<meta name="twitter:site" content="@cuenta">
			<meta name="twitter:creator" content="@cuenta">
			<!-- Open Graph Imagen completa (Opcional) -->
			<meta property="og:image:secure_url" content="https://secure.example.com/ogp.jpg">
			<meta property="og:image:type" content="image/jpeg">
			<meta property="og:image:width" content="400">
			<meta property="og:image:height" content="300">
			<meta property="og:image:alt" content="A shiny red apple with a bite taken out">
			<!-- Normalizador normalize.css: Equilibra los estilos entre los Navegadores -->
			<link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.1/normalize.min.css">
			<!-- Normalizador symbiosis.css: Arregla problemas en versiones de Smartphone -->
                        <link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/gh/sapps-studio/symbiosis-css/symbiosis.min.css">
			<!-- Tus archivos CSS -->
			<link rel="stylesheet" type="text/css" href="css/main.css">
		</head>	
	<!--Contenido de la web-->
	<body>
		Tu HTML
	</body>	
</html>

```
