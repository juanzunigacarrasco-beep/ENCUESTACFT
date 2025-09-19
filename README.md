Encuesta de Satisfacción y Sugerencias Estudiantiles C.F.T

Objetivo del proyecto: 
Diseñar y aplicar una herramienta de evaluación que permita recoger la percepción del alumnado en áreas clave de su experiencia educativa, con el fin de identificar oportunidades de mejora concretas, fortalecer la calidad institucional y fomentar una cultura de participación activa y retroalimentación continua.

Introducción
Para nuestro Centro de Formación Técnica C.F.T; la opinión de nuestros estudiantes es el pilar para la mejora continua.
Este formulario es una invitación para que nos entregues tu valiosa retroalimentación sobre tu experiencia educativa, la calidad de nuestros servicios y las áreas que podemos fortalecer. Tus sugerencias y observaciones nos permiten implementar cambios efectivos que respondan a las necesidades de nuestro alumnado.
Agradecemos sinceramente tu participación. La información recopilada será tratada de forma confidencial y es fundamental para nuestro plan de mejoras.

Instrucciones:
El estudiante deberá leer y calificar digitalmente los siguientes enunciados utilizando la escala: “Conforme”, “No conforme”, “Sin interés” o “No sabe”.
Las afirmaciones están agrupadas en tres áreas de relevancia, con el propósito de recoger la percepción estudiantil y detectar oportunidades de mejora que contribuyan al fortalecimiento de la experiencia formativa.

Resumen de Códigos Relevantes en el Diseño

Este diseño de "Encuesta de Satisfacción y Sugerencias Estudiantiles" está construido usando HTML para la estructura y contenido, y CSS para el estilo y la responsividad.
1.	HTML (Estructura y Contenido):
o	<!DOCTYPE html>, <html>, <head>, <body>: La estructura básica de cualquier página web moderna. lang="es" especifica el idioma.
o	<meta charset="UTF-8">: Asegura que los caracteres especiales (acentos, ñ) se muestren correctamente.
o	<meta name="viewport" ...>: Esencial para el diseño responsivo, haciendo que la página se adapte a diferentes tamaños de pantalla (móviles, tablets, escritorio).
o	<title>: El título de la pestaña del navegador.
o	<div> con clases como container, header, intro, area, question, options, etc.: Estos son los contenedores principales que organizan todo el contenido de la encuesta, permitiendo aplicar estilos de manera granular.
o	<h1>, <h2>, <h3>, <p>: Encabezados y párrafos para los títulos y descripciones.
o	<img> src="logo3.png" alt="...": Para mostrar el logo del CFT. El atributo alt es importante para la accesibilidad.
o	<form>: El contenedor para todos los elementos de entrada de la encuesta.
o	<label>, <input type="radio">, <textarea>: Los elementos de formulario clave para la interacción del usuario:
	label asocia texto descriptivo a las opciones de radio y áreas de texto.
	input type="radio" permite seleccionar una única opción por pregunta. Los atributos name los agrupan y required los hace obligatorios.
	textarea para comentarios extensos, con minlength y maxlength para limitar la entrada.
o	<button type="submit">: El botón para enviar el formulario.


2.	CSS (Estilo, Diseño y Responsividad):
o	* { box-sizing: border-box; margin: 0; padding: 0; }: Un "reset" inicial para asegurar que la página se vea consistente en todos los navegadores, estableciendo un modelo de caja más fácil de trabajar.
o	body: Define el estilo general de la página:
	font-family: Usa fuentes modernas y legibles (Segoe UI).
	background: linear-gradient(...): Un degradado de color naranja oscuro para el fondo de la página.
	display: flex; justify-content: center; align-items: center;: Utiliza Flexbox para centrar vertical y horizontalmente el contenedor principal de la encuesta en la pantalla.
o	.container: El contenedor central de la encuesta:
	max-width, width, margin: 0 auto;: Lo centra y limita su ancho para una mejor lectura en pantallas grandes.
	background: white; border-radius: 15px; box-shadow: ...;: Le da un fondo blanco, esquinas redondeadas y una sombra sutil para que "flote" sobre el fondo degradado.
o	linear-gradient en .header y .area-header: Proporciona degradados de color diferentes para los encabezados de la encuesta y de cada sección, dándoles un aspecto moderno.
o	border-radius y box-shadow en varios elementos: Usados extensivamente para crear un diseño suave, moderno y con sensación de profundidad (por ejemplo, en las secciones de preguntas y en el botón de envío).
o	display: grid; grid-template-columns: repeat(auto-fit, minmax(120px, 1fr)); en .options: Esto es CSS Grid Layout y es clave para el diseño de las opciones de respuesta. Permite que las opciones se organicen en columnas que se ajustan automáticamente al espacio disponible, haciéndolas responsivas sin esfuerzo.
o	transition: all 0.3s ease; en .option y .submit-btn: Crea animaciones suaves al interactuar (pasar el ratón por encima o seleccionar) para una mejor experiencia de usuario.
o	accent-color en input[type="radio"]: Permite colorear el círculo interior de los botones de radio para que coincida con la paleta de colores del diseño.
o	@media (max-width: 768px) { ... }: Una Media Query fundamental para el diseño responsivo. Dentro de este bloque, se aplican estilos específicos cuando la pantalla tiene 768 píxeles de ancho o menos (típicamente para dispositivos móviles), ajustando márgenes, tamaños de fuente y cambiando la cuadrícula de opciones a una sola columna (grid-template-columns: 1fr;) para mejorar la legibilidad y usabilidad en pantallas pequeñas.
o	
Concluyendo:
El diseño realizado como trabajo solicitado; es un ejemplo claro de una página web moderna y responsiva, que utiliza HTML para una estructura clara y CSS para una presentación visualmente atractiva y adaptable a cualquier dispositivo.


Detalle y áreas a calificar.

Área de Interés
Área 1: Infraestructura y Recursos de Aprendizaje
Esta área se enfoca en evaluar las instalaciones y los materiales que el centro pone a disposición de los estudiantes.
1.	¿Cómo calificarías el estado y la comodidad de las salas de clases y talleres?
2.	¿Consideras que los equipos, herramientas y maquinarias utilizados en tus clases prácticas están actualizados y en buen estado?
3.	¿El acceso a computadores, software y conexión a internet en el centro es adecuado para tus necesidades académicas?
4.	¿Los materiales de estudio proporcionados por el centro (manuales, guías, etc.) son claros y útiles para tu aprendizaje?
5.	¿Cómo evalúas la limpieza y el orden general de las instalaciones del centro (baños, pasillos, áreas comunes)?
6.	¿La biblioteca o centro de recursos cuenta con el material bibliográfico y digital que necesitas para tus asignaturas?
7.	¿Qué sugerencias tienes para mejorar la infraestructura o los recursos de aprendizaje del centro?

Área 2: Calidad Docente y Proceso de Enseñanza
Esta sección está diseñada para conocer la percepción de los estudiantes sobre sus profesores y las metodologías de enseñanza.
1.	¿Los docentes demuestran un dominio y conocimiento profundo de las materias que imparten?
2.	¿Los profesores utilizan métodos de enseñanza que facilitan tu comprensión y aprendizaje (ejemplos prácticos, uso de tecnología, etc.)?
3.	¿Sientes que los docentes están disponibles para resolver tus dudas y apoyarte en tu proceso de formación?
4.	¿La forma en que se te evalúa (pruebas, trabajos, etc.) es justa y representativa de lo aprendido en clases?
5.	¿Los profesores fomentan un ambiente de respeto y participación en las salas?
6.	¿Recibes retroalimentación útil y a tiempo sobre tu desempeño académico por parte de tus docentes?
7.	¿Tienes alguna sugerencia para mejorar el desempeño de los docentes o la forma en que se imparten las clases?

 	Área 3: Servicios de Apoyo y Vida Estudiantil
El objetivo de esta área es evaluar los servicios de apoyo al estudiante y el ambiente general del centro.
1.	¿Cómo calificarías la atención y la eficiencia del personal administrativo (secretaría, finanzas, etc.)?
2.	¿Los canales de comunicación del centro (página web, redes sociales, correos) te mantienen bien informado sobre noticias y eventos importantes?
3.	¿Sientes que el centro ofrece suficientes oportunidades para el desarrollo de actividades extraprogramáticas (deportes, cultura, etc.)?
4.	¿Conoces y consideras útiles los servicios de apoyo al estudiante que ofrece el centro (apoyo psicológico, becas, bolsa de trabajo, etc.)?
5.	¿El ambiente general en el centro es seguro, inclusivo y fomenta una buena convivencia entre los estudiantes?
6.	¿El proceso de matrícula e inscripción de asignaturas te resultó claro y sencillo?
7.	¿Qué sugerencias tienes para mejorar los servicios de apoyo o la experiencia estudiantil en el centro?
