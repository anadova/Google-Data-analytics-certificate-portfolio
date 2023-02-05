# Google-Data-analytics-certificate-portfolio
A data analytics case study that includes R to clean, analyze and process the data, Tableau to create visualizations and a Google Slides presentation.
As the Data Analytics course is in spanish, also is the case study. 


Caso práctico 2: ¿Cómo puede hacer una empresa tecnología para el bienestar para tomar decisiones inteligentes?


Introducción
¡Bienvenido al caso práctico de análisis de datos de Bellabeat! En este caso práctico, realizarás muchas tareas del mundo real, típicas de un analista de datos júnior. Imaginarás que trabajas para Bellabeat, un fabricante de productos de alta tecnología orientados a la salud de la mujer, y conocerás a diferentes personajes y miembros del equipo. Para responder a las preguntas clave de la empresa, seguirás los pasos del proceso de análisis de datos: preguntar, preparar, procesar, analizar, compartir y actuar. En este proceso, las tablas del mapa de ruta de caso práctico, incluidas las preguntas orientativas y las tareas clave, te ayudarán a mantenerte en el camino correcto.

Al final de esta lección, tendrás un caso práctico listo para el portfolio. Descarga el paquete y consulta los detalles de este caso práctico en cualquier momento. Así, cuando empieces a buscar trabajo, tu caso práctico será una forma tangible de demostrar tus conocimientos y habilidades a los posibles empleadores.

Escenario
Eres un analista de datos júnior que trabaja en el equipo de analistas de marketing de Bellabeat, fabricante de productos de alta tecnología orientados a la salud de la mujer. Bellabeat es una empresa pequeña exitosa, pero tiene el potencial para convertirse en un actor más grande en el


mercado global de dispositivos inteligentes. Urška Sršen, cofundadora y directora creativa de Bellabeat, cree que analizar los datos de actividad física de los dispositivos inteligentes podría desplegar nuevas oportunidades de negocio para la empresa. Te han pedido que te concentres en uno de los productos de Bellabeat y analices los datos de los dispositivos inteligentes para conocer el uso que hacen los consumidores de sus dispositivos inteligentes. Los hallazgos que descubras ayudarán a orientar la estrategia de marketing de la empresa. Presentarás tu análisis al equipo ejecutivo de Bellabeat junto con tus recomendaciones de alto nivel para la estrategia de marketing de Bellabeat.

Personajes y productos
Personajes
Urška Sršen: Cofundadora y directora creativa de Bellabeat
Sando Mur: Matemático y cofundador de Bellabeat, miembro clave del equipo ejecutivo de Bellabeat.
Equipo de análisis computacional de datos de marketing de Bellabeat: Un equipo de analistas de datos que se encarga de recopilar, analizar e informar datos que ayudan a conducir la estrategia de marketing de Bellabeat. Te incorporaste a este equipo hace seis meses y te has dedicado a conocer la misión y las metas de negocios de Bellabeat, y a ver cómo puedes ayudar a la empresa a lograr estos objetivos desde tu lugar de analista de datos júnior.
Productos
Aplicación Bellabeat: La aplicación Bellabeat proporciona a los usuarios datos de salud relacionados con su actividad física, sueño, estrés, ciclo menstrual y hábitos de conciencia plena. Estos datos pueden ayudar a los usuarios a comprender sus hábitos actuales y adoptar decisiones saludables. La aplicación Bellabeat se conecta a su línea de productos de bienestar inteligentes.
Leaf: Dispositivo de seguimiento clásico de bienestar de Bellabeat que se puede usar como pulsera, collar o clip. El dispositivo Leaf se conecta a la aplicación Bellabeat para hacer un seguimiento de la actividad física, el sueño y el estrés.
Time: Este reloj de bienestar combina el aspecto intemporal de un reloj clásico con la tecnología inteligente para hacer el seguimiento de la actividad física, el sueño y el estrés del usuario. El reloj Time se conecta a la aplicación Bellabeat para proporcionar información sobre el bienestar diario.
Spring: Es una botella de agua que hace el seguimiento diario del consumo de agua mediante el uso de tecnología inteligente para garantizar la hidratación adecuada a lo largo del día. La botella Spring se conecta a la aplicación Bellabeat para hacer el seguimiento de los niveles de hidratación.


Membresía de Bellabeat: Bellabeat también ofrece a los usuarios un programa de membresía mediante suscripción. La membresía brinda a los usuarios un acceso 24/7 a una orientación totalmente personalizada sobre nutrición, actividad física, sueño, salud y belleza y conciencia plena según el estilo de vida y las metas del usuario.

Acerca de la empresa
Urška Sršen y Sando Mur fundaron Bellabeat, una empresa de alta tecnología que fabrica productos inteligentes focalizados en el cuidado de la salud. Sršen usó su experiencia como artista para desarrollar una tecnología con un bonito diseño que informará e inspirará a las mujeres de todo el mundo. Recopilar datos sobre la actividad física, el sueño, el estrés y la salud reproductiva le ha permitido a Bellabeat proporcionar a las mujeres conocimientos sobre su propia salud y sus hábitos. Desde su fundación, en 2013, Bellabeat creció a un ritmo vertiginoso y rápidamente se posicionó como empresa de bienestar impulsada por la tecnología para las mujeres.

En 2016, Bellabeat ya había inaugurado oficinas en todo el mundo y lanzado múltiples productos. Los productos Bellabeat pasaron a estar disponibles en línea a través de un creciente número de comerciantes minoristas además del canal de comercio electrónico propio de Bellabeat en su sitio web. La empresa invirtió en medios publicitarios tradicionales, como radio, cartelería en la vía pública, prensa gráfica y televisión, pero se centra mayormente en el marketing digital. Bellabeat invierte todo el año en Google Search, mantiene activas las páginas de Facebook e Instagram e interactúa de manera constante con los consumidores en Twitter. A su vez, Bellabeat publica anuncios por video en YouTube y avisos publicitarios en Red de Display de Google para apoyar las campañas en fechas de marketing claves.

Sršen sabe que el análisis de los datos de consumo disponibles de Bellabeat revelaría nuevas oportunidades de crecimiento. Ella le pidió al equipo de análisis computacional de datos de marketing que se concentrara en un producto Bellabeat y analizara los datos de uso de dispositivos inteligentes para conocer cómo las personas están usando sus dispositivos inteligentes. Después, con esta información, le gustaría recibir recomendaciones de alto nivel sobre cómo estas tendencias pueden colaborar en la estrategia de marketing de Bellabeat.

Preguntar
Sršen te pide que analices los datos de uso de los dispositivos inteligentes para saber cómo usan los consumidores los dispositivos inteligentes que no son de Bellabeat. Después, quiere que selecciones un producto Bellabeat para aplicar estos conocimientos en tu presentación. Estas preguntas orientarán tu análisis:



¿Cuáles son algunas tendencias de uso de los dispositivos inteligentes?
¿Cómo se podrían aplicar estas tendencias a los clientes de Bellabeat?
¿Cómo podrían ayudar estas tendencias a influir en la estrategia de marketing de Bellabeat?

Crearás un informe con los siguientes entregables:
Un resumen claro de la tarea empresarial
Una descripción de todas las fuentes de datos utilizadas
Documentación de todas las limpiezas y manipulaciones de datos
Un resumen de tu análisis
Visualizaciones de respaldo y hallazgos clave
Las tres recomendaciones de contenido de alto nivel basadas en tu análisis

Usa el siguiente mapa de ruta de caso práctico como guía. Nota: Completar este caso práctico en una semana es una buena meta.

Mapa de ruta de caso práctico - Preguntar
Preguntas orientativas
¿Cuál es el problema que intentas resolver?
¿Cómo tus conocimientos pueden impulsar las decisiones empresariales?
Tareas clave
Identificar la tarea empresarial
Considerar a los interesados clave
Entregable
Una instrucción clara de la tarea empresarial




Preparar
Sršen te alienta a que uses datos públicos que exploren los hábitos cotidianos de los usuarios de dispositivos inteligentes. Ella te señala un conjunto de datos específicos:
Datos de seguimiento de actividad física de Fitbit (CC0: Dominio público, conjunto de datos disponibles a través de Mobius): Este conjunto de datos de Kaggle contiene el seguimiento de la actividad física personal en treinta usuarios de Fitbit. Treinta usuarios elegibles de Fitbit prestaron su consentimiento para el envío de datos personales de seguimiento que incluyen rendimiento de la actividad física en minutos, ritmo cardíaco y monitoreo del sueño. Incluye información sobre la actividad diaria, pasos y ritmo cardíaco que se puede usar para explorar los hábitos de los usuarios.
Sršen te comenta que este conjunto de datos podría tener ciertas limitaciones y te alienta a considerar la posibilidad de agregar otros datos que te ayuden a resolver esas limitaciones a medida que profundices en el trabajo con los datos.

Ahora, prepara tus datos para el análisis usando el siguiente mapa de ruta de caso práctico como guía:

Mapa de ruta de caso práctico - Preparar
Preguntas orientativas
¿Dónde se almacenan tus datos?
¿Cómo están organizados los datos? ¿Están en formato largo o ancho?
¿Hay problemas con el sesgo o la credibilidad de estos datos? ¿Tus datos son confiables, originales, integrales, actuales y citados (ROCCC)?
¿Cómo estás abordando la autorización, la privacidad, la seguridad y la accesibilidad?
¿Cómo verificaste la integridad de los datos?
¿De qué manera te ayuda a responder tu pregunta?
¿Existe algún problema con los datos?
Tareas clave
Descarga los datos y almacénalos adecuadamente.
Identifica cómo están organizados.
Ordena y filtra los datos.




4. Determina la credibilidad de los datos.
Entregable
Una descripción de todas las fuentes de datos utilizadas


Procesar
Ahora, procesa tus datos para el análisis usando como guía el siguiente mapa de ruta de caso práctico:

Mapa de ruta de caso práctico - Procesar
Preguntas orientativas
¿Qué herramientas eliges y por qué?
¿Has garantizado la integridad de los datos?
¿Qué pasos seguiste para garantizar que tus datos están limpios?
¿Cómo puedes verificar que tus datos están limpios y listos para analizar?
¿Documentaste tu proceso de limpieza para poder revisar y compartir estos resultados?
Tareas clave
Verifica si hay errores en los datos.
Elige tus herramientas.
Transforma los datos para que puedas trabajar con ellos eficazmente.
Documenta el proceso de limpieza.
Entregable
Documentación de todas las limpiezas y manipulaciones de datos


Sigue estos pasos:


Descarga el conjunto de datos.
Descomprime los archivos.
Crea una carpeta en tu escritorio o en Drive para alojar los archivos. Usa convenciones apropiadas de nomenclatura de archivos. Si necesitas hacer un repaso sobre las convenciones de nomenclatura de archivos, vuelve a ver el video “Todo con respecto a la nomenclatura de los archivos” o la lectura “Pautas de  organización” .
Carga los datos a la herramienta que prefieras. Para repasar las distintas formas de hacerlo, siéntete libre de consultar cualquiera de los siguientes recursos sobre cómo empezar en las siguientes herramientas:

Hojas de cálculo
SQL
R
Importar datos desde hojas de cálculo: Este video del Curso 3 te guiará en los pasos que debes seguir para importar datos a tu hoja de cálculo. Esto es útil si deseas realizar la limpieza y el análisis de tus hojas de cálculo.
Cargar un archivo CSV en BigQuery: Estas instrucciones detalladas te guiarán en cada paso del proceso de carga de tu archivo CSV en BigQuery para que puedas empezar a trabajar con tus datos en SQL.
Conceptos básicos de la importación de datos: Esta lectura del Curso 7 repasará la importación de datos en R para que puedas empezar a limpiarlos y analizarlos. Si planeas usar R para tu caso práctico, este es un punto de partida útil.
Características de la limpieza de datos en las hojas de cálculo: Este video del Curso 4 describe las funciones básicas de limpieza de datos en las hojas de cálculo; este es un excelente repaso si necesitas rever el tema.
Limpieza de variables en cadena con SQL: Este video del Curso 4 abarca algunas técnicas de limpieza clave para datos en cadena en SQL.
Limpieza con lo básico: Este video del Curso 7 te guiará a través de algunas funciones básicas de limpieza en R que necesitarás para procesar tus datos para el análisis.
Más técnicas de limpieza de datos: Este video del Curso 4 abarca incluso más técnicas que puedes usar para limpiar tus datos y prepararlos para el análisis.
Funciones avanzadas de limpieza de datos  parte 1 y parte 2: Estos videos tratan sobre funciones de limpieza más avanzadas y son excelentes si necesitas repasar el tema a medida que comienzas a trabajar de modo más preciso
Transformación de datos: Este video del Curso 7 se aboca a la transformación de datos en R para que estén organizados y formateados y faciliten así el análisis.






con tus datos.




Avanza al paso de análisis.

Si quieres, sigue trabajando con los datos para familiarizarte mejor y, tal vez, incluso identificar nuevos enfoques para responder a las preguntas empresariales.

Analizar
Ahora que tus datos están almacenados adecuadamente y listos para el análisis, empieza a ponerlos en funcionamiento. Usa el siguiente mapa de ruta de caso práctico como guía:

Mapa de ruta de caso práctico - Analizar
Preguntas orientativas
¿Cómo deberías organizar tus datos para realizar un análisis?
¿Tus datos tienen el formato correcto?
¿Qué sorpresas descubriste en los datos?
¿Qué tendencias o relaciones encontraste en los datos?
¿Cómo te ayudarán estos conocimientos para responder a tus preguntas empresariales?
Tareas clave
Consolida tus datos para que sean útiles y accesibles.
Organiza y formatea tus datos.
Realiza cálculos.
Identifica tendencias y relaciones.




Entregable
Un resumen de tu análisis


Sigue estos pasos para usar SQL
Aquí hay un script de muestra que puede ayudarte a hacer lo siguiente:
Para usar el script de muestra, haz clic en este enlace y selecciona “Usar plantilla”.

Importa tus datos.
Explora tus datos, quizás mirando el número total de filas, los valores distintos, el máximo, el mínimo o los valores medios.
Cuando corresponda, usa las instrucciones JOIN para combinar tus respectivos datos en diferentes tablas según las necesidades de tus análisis.
Crea estadísticas de resumen.
Investiga las tendencias interesantes y guarda esa información en una tabla.

Para dar los primeros pasos en R
Aquí hay un script de muestra que puede ayudarte a hacer lo siguiente:
Empezar a importar tus datos.
Explorar tus datos, recopilar y resumir estadísticas.
Limpiar y transformar tus datos para prepararlos para el análisis.
Crear algunas visualizaciones exploratorias iniciales.


Compartir
Una vez que hayas completado tu análisis, crea tus visualizaciones de datos. Las visualizaciones deben comunicar claramente tus conclusiones y recomendaciones de alto nivel. Usa el siguiente mapa de ruta de caso práctico como guía:


Mapa de ruta de caso práctico - Compartir
Preguntas orientativas
¿Pudiste responder estas preguntas empresariales?
¿Qué historia cuentan tus datos?
¿De qué manera tus hallazgos se relacionan con tu pregunta original?
¿Cuál es tu audiencia? ¿Cuál es la mejor manera de comunicarte con ella?
¿La visualización de datos puede ayudarte a compartir tus hallazgos?
¿Tu representación es accesible para tu público?
Tareas clave
Determina la mejor manera de compartir tus hallazgos.
Crea visualizaciones de datos efectivas.
Presenta tus hallazgos.
Garantiza que tu trabajo sea accesible.
Entregable
Visualizaciones de respaldo y hallazgos clave


Sigue estos pasos:
Toma una hoja de papel y una lapicera y bosqueja algunas ideas sobre cómo visualizarás los datos.
Cuando ya hayas elegido una forma visual, abre la herramienta que prefieras y crea tu visualización. Usa un software para presentaciones, por ejemplo, PowerPoint o Google Slides; tu programa de hojas de cálculo; Tableau o R.
Crea tu visualización de datos, recuerda que se debe usar el contraste para captar la atención de la audiencia y dirigirla hacia los conceptos más importantes. Usa principios artísticos que incluyan el tamaño, el color y la forma.
Garantiza un significado claro mediante el uso adecuado de elementos comunes, por ejemplo, títulos, subtítulos y etiquetas.
Perfecciona la visualización de tus datos mediante una especial atención a los detalles.


Actuar
Ahora que terminaste de crear tus visualizaciones, actúa en función de tus hallazgos. Prepara los entregables que te han pedido que crearas, incluso las tres recomendaciones de alto nivel que se basan en tu análisis. Usa el siguiente mapa de ruta de caso práctico como guía:

Mapa de ruta de caso práctico - Actuar
Preguntas orientativas
¿Cuál es tu conclusión en función de tu análisis?
¿Cómo podrían tu equipo y tu empresa aplicar tus conclusiones?
¿Qué próximos pasos tú o los interesados podrían adoptar en función de tus hallazgos?
¿Existen datos adicionales que podrías utilizar para ampliar tus hallazgos?
Tareas clave
Crea tu portfolio.
Agrega tu caso práctico.
Practica presentando tu caso práctico a un amigo o familiar.
Entregable
Tus conclusiones de alto nivel más importantes basadas en tu análisis


Sigue estos pasos:
Si todavía no tienes un portfolio, crea uno en línea. (Usa Crear un portfolio interactivo con Google Sites o Construir un portfolio con Google Sites.)
Considera cómo quieres presentar tu caso práctico en tu portfolio.
Carga o vincula los hallazgos de tu caso práctico a tu portfolio.
Escribe un párrafo breve que describa el caso práctico, su proceso y tus hallazgos.
Añade el párrafo para presentar tu caso práctico en tu portfolio.



