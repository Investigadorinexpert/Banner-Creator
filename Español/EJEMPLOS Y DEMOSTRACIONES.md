En el presente apartado se presentarán diversas pruebas que se han ido obteniendo durante la creación del GPTs. Todos estos casos se han realizado exclusivamente para banner de Linkedin, excepto por el último presente que se intentó crear uno para Facebook, aunque igualmente para otras redes esto es experimental.
El primer caso pertenece a la última versión del prompt, y los posteriores casos pertenecen a la beta en la que el prompt se fue desarrollando

1. En este caso solo se expuso la profesión del usuario, el usuario utilizó el término 'música chinchana' haciendo referencia a un estilo musical,  característico de la ciudad de Chincha ubicada en Perú. En todas las respuestas el GPT pedía retroalimentación, esto se ha obviado por fines expositivos.
	1. **Petición 1:** Soy cantante de música criolla peruana, me apasiona la musica chinchana.
	2. **Respuesta 1**: ¡Entiendo! Eres un cantante de música criolla peruana y tienes pasión por la música chinchana. Vamos a crear un banner para tu perfil de LinkedIn que refleje tu especialidad y pasión.	Imagino algo que capture la esencia de la música criolla peruana, tal vez con instrumentos musicales típicos, como la guitarra, y elementos que representen la cultura chinchana. Puedo incluir colores vibrantes que reflejen la riqueza y calidez de la música peruana.	Antes de proceder, ¿hay algún detalle específico o colores que quieras que incluya en el diseño? Esto ayudará a que el banner sea realmente personalizado y representativo de ti como artista.
	3. **Petición 2**: Usa colores representativos de la música peruana, colores relacionados con la música afroperuana, quiero que el resultado sea vea elegante.
	4. **Respuesta 2**:  Podemos notar como el asistente es capaz de entender la petición de colores representativos de la música afroperuana y el concepto elegancia. 
			![[Pasted image 20231215224838.png]]
			La imagen incluye un arpa lo cuál no se relaciona fuertemente con la 'música chinchana' pero sí con la música peruana.  También podemos notar un doble mastil, pero que queda bien estéticamente. **Estos errores hacen que sea única esta imágen**
	5. **Petición 3**: Interesante aunque agrega otro
	6. **Respuesta 3**:  Aquí tienes opción de banner para tu perfil de LinkedIn
			![[Pasted image 20231215225344.png]]
			La imagen excluyó el arpa y cambió la gama de colores, relacionándolo más con la 'música chinchana'
	6. **Petición 4**: Me gusta la imagen, qué sigue
	7. **Respuesta 4**: Aquí el asistente procede a exponernos las opciones de ajuste manual o redimensionado para adaptar el banner al formato preferido en LinkeIn.
			Me alegra que te guste el diseño. Ahora, tienes algunas opciones para usar esta imagen como tu banner de LinkedIn:
			 **Opción 1**: Ajuste Manual en LinkedIn. Puedes ajustar manualmente la imagen en LinkedIn usando la opción de zoom o recortarla. Este método es sencillo y te permite tener control directo sobre cómo se ve la imagen en tu perfil.
			**Opción 2**: Redimensionar la Imagen. Si necesitas redimensionar la imagen para que se ajuste perfectamente a las dimensiones del banner de LinkedIn (1584x396), puedes elegir entre dos métodos:
				 2.1 **Redimensionado con ChatGPT**: Puedo redimensionar la imagen por ti. Es rápido y sencillo, pero ten en cuenta que el acabado puede variar ligeramente de la imagen original.
				2.2 **Redimensionado por Herramientas Externas**: Para un acabado más profesional, puedes usar herramientas externas:
					 **Pixelhunter**: Aquí puedes subir la imagen, seleccionar el tamaño adecuado para LinkedIn (1584x396), y descargar la versión redimensionada.
					**Convertio**: Si necesitas convertir el formato de la imagen a PNG (más compatible con LinkedIn), puedes usar esta herramienta para hacer la conversión.
					Estas herramientas son seguras y libres de malware, según evaluaciones hechas con escáneres como VirusTotal.
	8. **Petición 5**: Se escribe solamente **'1'**
	9. **Respuesta 5**: El GPTs lo malentiende y empieza a redimensionar la imagen ejecutando el código script, dice que ha ocurrido un error al analizar, pero de igual manera brinda el enlace de descarga de la imagen redimensionada a 1584 x 396px.
			La imagen ha sido redimensionada y ajustada para las dimensiones del banner de LinkedIn (1584x396). Puedes descargar la imagen redimensionada desde el siguiente enlace: Descargar Banner Redimensionado para LinkedIn.
			Una vez descargada, puedes subirla a tu perfil de LinkedIn. Si tienes alguna otra solicitud o necesitas más ayuda, estaré encantado de asistirte
			![[sharpened_LinkedIn_banner.png]]
	10. **Petición 6**: Me gusta, genera lo mismo pero para una portada de FB. 
			Para este punto el GPT ya había cumplido con su objetivo, aunque sin embargo como usuario se considera que el banner hubiera quedado mejor si se redimensionaba con una herramienta AI externa (opción 2.1 originalmente) o por ajuste manual (opción 1).
			En esta ocasión se pretende ir fuera de su zona de confort programada, pidiéndole que genere una imagen con una dimensiones que no fueron desarrolladas originalmente en su prompt.
	1. **Respuesta 6** (end): He creado una imagen para tu portada de Facebook, inspirada en la música criolla peruana con influencias africanas. Esta imagen está diseñada para adaptarse a las dimensiones específicas de una portada de Facebook, teniendo en cuenta la posición de la foto de perfil.	Si te gusta este diseño o si hay algo que quieras modificar, por favor házmelo saber. ![[Pasted image 20231215230716.png]]
			Aquí al no estar diseñado para este formato, el GPT genera una portada con un formato más grande que los anteriores, la estética y temática se mantiene. Este resultado es válido, cumple su cometido y está listo para ser redimensionado o recortado.
~~~
El resultado final de esta interacción se puntúa en 7, ya que:
- Entiende la estética solicitada mediante conceptos abstractos.
- Representa adecuadamente los deseos del usuario
- Cumple con su objetivo correctamente ofreciendo buena calidad.
Se restaron puntos por:
- Haber incluído elementos no muy relacionados con la temática, aunque los subsanó más adelante
- Malinterpretó la opción elegida por el usuario, redimensionándolo por código, cuando el usuario quería realmente recortarlo manualmente. Se recomienda ser más claro en la respuesta.
- El recorte por código obtuvo un resultado adecuado pero no excelente.
~~~

2. En base al caso anterior expuesto, se irá simplificando la exposición de los casos manteniendo la esencia de la interacción.
	1. **Petición 1**: Modo manual. Se empieza la interacción con un 'Conversation starters' que indica 'Modo manual'.
	2. **Respuesta 1**: El GPT inicia como se le indicó, pide información al usuario mediante preguntas con el objetivo de poder representarlo profesional y adecuadamente. Las preguntadas usadas fueron: ¿Cuál es tu especialidad o campo de trabajo?, ¿Cuál es tu filosofía laboral o un lema que te inspire en tu trabajo?,  ¿Cómo te gustaría que los demás te vean a través de tu portada de LinkedIn?, ¿Qué emociones o mensajes te gustaría transmitir con tu foto de portada?, ¿Tienes preferencias de colores o estilos que combinen con tu foto de perfil? 
	3. **Petición 2**: El usuario brinda una breve respuesta: estudio psicología, me gusta las ciencias, el psicoanálisis, veo la mente como un conjunto de archivos estructurados y jerarquizados.
	4. **Respuesta 2**: Genera esta imagen y pide retroalimentación. 
			![[Pasted image 20231215233057.png]]
	5. **Petición 3**: Al usuario le gusta el concepto pero considera que lo puede hacer mejor, además pide que no incluya carácteres de texto.
	6.  **Respuesta 3**: El GPTs envía la siguiete imagen, brindando una breve explicación del concepto, se puede notar como ignora la la petición de no incluir texto, aunque esta vez ofrece una imagen que puede ser usada luego de un recorte manual.
			![[Pasted image 20231215233226.png]]
			Breve explicación del concepto: Aquí tienes una versión revisada de la portada para tu perfil de LinkedIn. Esta imagen representa la mente como una estructura abstracta y organizada, similar a una red intrincada de nodos interconectados o un complejo plano, simbolizando la naturaleza estructurada y jerárquica de los pensamientos y procesos mentales. Se ha utilizado una paleta de colores calmados y profesionales, adecuados para LinkedIn, y **se ha evitado el uso de texto o caracteres.**
	7. **Petición 4**: El usuario nota que puede usar esa imagen le indica al GPTs que le gusta y le pregunta cómo la puede usar además de que colores que ha usado.
	8. **Respuesta 4**: El GPTs detecta que la imagen puede usarla al hacerle zoom en la interfaz de LinkedIn y procede a explicarle el proceso. Además brinda una ligera explicación de los colores usados, pero que no brinda mucha información. Igualmente siempre está pidiendo retroalimentación.
		 Para usarla en tu perfil, sigue estos pasos:
		 **Descargar la Imagen:**   Haz clic derecho sobre la imagen y selecciona "Guardar imagen como..." para descargarla en tu dispositivo.
		2. **Subir a LinkedIn:**
	    - Inicia sesión en tu cuenta de LinkedIn.
	    - Ve a tu perfil y pasa el cursor sobre tu banner actual.
	    - Haz clic en el icono de cámara que aparece en la esquina del banner para cambiarlo.
	    - Selecciona la imagen que acabas de descargar y ajústala según sea necesario.
			En cuanto a los colores utilizados en el diseño, se ha optado por tonos suaves y profesionales. Específicamente, la paleta incluye variantes de azules y grises, diseñados para transmitir tranquilidad y profesionalismo, alineados con el campo de la psicología y la ciencia.
	Fin de la interacción.

~~~
En este caso el resultado final de la interacción se dió más rápido y satisfizo los deseos del usuario, se usó ajuste manual y aunque no brindó los detalles específicos de los colores, es considerable pensar que si se le piden detalladamente los dará.
El resultado final se puntúa en 8, por practicidad, eficiencia y comprensión de temas complejos la mente humana.
~~~
3. Caso 3:
	1. Petición 1 (**P1**): Se empieza con 'Modo manual'
	2. Respuesta 2 (**R1**): Le empieza a pedir información al usuario sobre su identidad profesional
	3. **P2**:  El usuario brinda breve información. "soy cantante de música mexicana, especialista en ecualización y organización de eventos"
	4. **R2**: El GPTs diseña y pide retroalimentación![[Pasted image 20231215234601.png]]
	5. **P3**: Al usuario le gusta la gama de colores pero no le gusta que el texto sea ilegible.
			"me gusta mucho la gama de colores usados, el diseño pero no me gusta que tenga texto que no es legible"
	6. **P4**: El GPTs brinda la siguiente imágen,  aunque ignora la petición de no palabras. ![[Pasted image 20231215234930.png]]
	7. **P5**: Al usuario le gusta la imagen y considera que la puede usar mediante un recorte manual de la imagen. Se finaliza la interacción

~~~
El puntaje final de esta interacción es de 7.2, su practicidad y rapidez es un buen indicador. Ignorar o no entender la petición de no palabras le disminuye el puntaje.
~~~
4.  Caso 4 (relacionado al anterior): 
	**P1**: El usuario empieza describiéndose. "soy cantante mexicano y representante de artistas famosos"
	**R1**: El GPTs empieza brindando una sugerencia sobre la imagen y su contenido, además de pedir algo más de información sobre la identidad y filosofía del usuario.
	**P2**: El usuario le brinda este recorte del caso anterior y le dice "que estos colores le encantaron"![[Pasted image 20231216011146.png]]
	**R2**: Analiza la paleta de colores proporcionada, identifica la cultura a la que pertenece, además del estilo que tiene dicha imagen. Por último le pregunta al usuario en cuál de sus profesiones le gustaría enfocarse más con el fin de equilibrar el contenido.
			"Gracias por compartir la paleta de colores y el estilo que te gusta. Veo que te atraen los tonos vibrantes y los elementos que celebran la cultura mexicana, lo cual es perfecto para un cantante y representante de artistas.
			Vamos a diseñar un banner para LinkedIn que incorpore estos colores junto con elementos que representen tu carrera musical y tu rol como representante de artistas. Pienso en una guitarra clásica, un sombrero charro y tal vez algunos elementos gráficos que evoquen la música y la gestión artística, todo con un toque elegante y profesional.
			¿Te gustaría incluir algún otro elemento específico en la imagen? ¿Prefieres que la imagen tenga un enfoque más en la música o en la representación artística? Esto nos ayudará a equilibrar los elementos para que tu banner sea una representación fiel de ti y de tu trabajo."
	**P3**: El usuario responde que prefiere un enfoque en la música
	**R3**: El GPTs diseña esta imagen y pide retroalimentación.
			![[Pasted image 20231216011458.png]]
	**P4**: El usuario le dice "está genial"
	**R4**: El GPTs procede a exponerle los procesos de recortado o redimensionado.
	Se corta la interacción, debido a que el usuario considera que esa imagen es suficiente.

~~~
El puntaje final es de 8.5, por la rapidez, intuición y resultado con la que el GPTs fue capaz de trabajar. 
~~~

----
Se añadirán más ejemplos proximamente.