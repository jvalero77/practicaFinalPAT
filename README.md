# practicaFinalPAT

ÁGORA: Marketplace de productos software

Decripción:

	-Frontend consistente en una serie de pagina desarrolladas haciendo uso de HTML, CSS y JS
		-> página principal : index.html
	-Backend consitente en una API REST desarrollada en JAVA dentro del framework SPRINGBOOT
	-Persistencia implementada con H2 (al inicializar la aplicaión, se añade una serie de entradas a cada tabla del modelo de datos
		-> ver archivo inicializaciondb.sql


Funcionalidad implementada:

-Carga por defecto de los 6 productos más recientemente añadidos y los 6 productos mejor valorados
-Función de login -> Necesario estar loggeado para algunas funcionalidades -> Seguridad implementada mediante uso de tokens
	-> Por defecto, se puede probar con username= 'Usuario1', password= 'pass1'
-Función de registro de usuario
-Función de búsqueda de producto por nombre (barra de búsqueda)
-Página de detalle con información del usuario loggeado
	->Botón MiPerfil en barra de navegación
-Página de detalle con información de cada producto
	-> Botón 'Ver más' en tarjeta de cada producto
-Función de descarga de un producto 
	-> Se incluirá dicho producto en el registro de productos por el usuario, visible en la página MiPerfil
