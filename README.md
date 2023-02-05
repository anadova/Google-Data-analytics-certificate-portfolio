# Google-Data-analytics-certificate-portfolio
A data analytics case study that includes R to clean, analyze and process the data, Tableau to create visualizations and a Google Slides presentation.
As the Data Analytics course is in spanish, also is the case study. 



Caso práctico 1: ¿Cómo lograr el éxito rápido de un negocio de bicicletas compartidas?


Introducción
Bienvenido al caso práctico del análisis de bicicletas compartidas Cyclistic. En este caso práctico, realizarás muchas tareas del mundo real, típicas de un analista de datos júnior. Trabajarás para una empresa ficticia llamada Cyclistic y conocerás a diferentes personajes y miembros del equipo. Para responder a las preguntas clave de la empresa, seguirás los pasos del proceso de análisis de datos: preguntar, preparar, procesar, analizar, compartir y actuar. En este proceso, las tablas del mapa de ruta de caso práctico, incluidas las preguntas orientativas y las tareas clave, te ayudarán a mantenerte en el camino correcto.

Al final de esta lección, tendrás un caso práctico listo para el portfolio. Descarga el paquete y consulta los detalles de este caso práctico en cualquier momento. Así, cuando empieces a buscar trabajo, tu caso práctico será una forma tangible de demostrar tus conocimientos y habilidades a los posibles empleadores.


Escenario
Eres un analista de datos júnior que trabaja en el equipo de analistas de marketing de Cyclistic, una empresa de bicicletas compartidas de Chicago. La directora de marketing cree que el éxito futuro de la empresa depende de maximizar la cantidad de membresías anuales. Por lo tanto, tu equipo quiere entender qué diferencias existen en el uso de las bicicletas Cyclistic entre los ciclistas ocasionales y los miembros anuales. A través de estos conocimientos, tu equipo diseñará una nueva estrategia de marketing para convertir a los ciclistas ocasionales en miembros anuales. Sin embargo, antes de eso, los ejecutivos de Cyclistic deben aprobar tus recomendaciones; por eso, debes respaldar tu propuesta con una visión convincente de los datos y visualizaciones profesionales de los mismos.


Personajes y equipos
Cyclistic: Un programa de bicicletas compartidas que incluye 5,800 bicicletas y 600 estaciones. Cyclistic se destaca por ofrecer también bicicletas reclinadas, triciclos manuales y bicicletas de carga que ofrecen un uso más inclusivo de las bicicletas compartidas para las personas con discapacidad y los ciclistas que no pueden utilizar una bicicleta estándar de dos ruedas. La mayoría de los ciclistas eligen las bicicletas tradicionales, alrededor de un 8% de los ciclistas usan las opciones asistidas. Los usuarios de Cyclistic son más propensos a utilizar la bicicleta para recreación, pero alrededor del 30% la utiliza para ir al trabajo cada día.
Lily Moreno: La directora de marketing y tu gerente. Moreno es responsable del desarrollo de campañas e iniciativas para promover el programa de bicicletas compartidas. Las campañas pueden incluir correo electrónico, redes sociales y otros canales.
Equipo de análisis computacional de datos de marketing de Cyclistic: Un equipo de analistas de datos que se encargan de recopilar, analizar e informar datos que ayudan a conducir la estrategia de marketing de Cyclistic. Te incorporaste a este equipo hace seis meses y te has dedicado no solo a conocer la misión y las metas de negocios de Cyclistic, sino también a ver cómo puedes ayudar a Cyclistic a lograrlo, desde tu posición de analista de datos júnior.
Equipo ejecutivo de Cyclistic: El equipo ejecutivo, sumamente detallista, decidirá si aprueba el programa de marketing recomendado.


Acerca de la empresa
En 2016, Cyclistic lanzó una exitosa oferta de bicicletas compartidas. Desde entonces, el programa creció hasta alcanzar una flota de 5,824 bicicletas georreferenciadas y bloqueadas en una red de 692 estaciones en toda Chicago. Las bicicletas se pueden desbloquear desde una estación y devolverse en cualquier otra estación del sistema en cualquier momento.

Hasta ahora, la estrategia de marketing de Cyclistic se basaba en la construcción de un reconocimiento de marca general y en atraer a amplios segmentos de consumidores. Uno de los enfoques que ayudó a hacer esto posible fue la flexibilidad de sus planes de precios: pases de un solo viaje, pases de un día completo y membresías anuales. A los clientes que compran pases de un solo viaje o pases de un día completo se los llama ciclistas ocasionales. Los clientes que compran membresías anuales se llaman miembros de Cyclistic.

Los analistas financieros de Cyclistic llegaron a la conclusión de que los miembros anuales son mucho más rentables que los ciclistas ocasionales. Aunque la flexibilidad de precios ayuda a Cyclistic a atraer más clientes, Moreno cree que maximizar el número de miembros anuales será clave para el crecimiento futuro. En lugar de crear una campaña de marketing que apunte a todos los clientes nuevos, Moreno cree que hay muchas posibilidades de convertir a los ciclistas ocasionales en miembros. Ella señala que los ciclistas ocasionales ya conocen el programa de Cyclistic y han elegido a Cyclistic para sus necesidades de movilidad.

Moreno estableció una meta clara: Diseñar estrategias de marketing orientadas a convertir a los ciclistas ocasionales en miembros anuales. Sin embargo, para hacer eso, el equipo de analistas de marketing necesita entender mejor cómo difieren los miembros anuales y los ciclistas ocasionales, por qué los ciclistas ocasionales comprarían una membresía y cómo los medios digitales podrían afectar sus tácticas de marketing. Moreno y su equipo están interesados en analizar los datos históricos de viajes en bicicleta de Cyclistic para identificar tendencias.

Preguntar
Tres preguntas guiarán el futuro programa de marketing:
¿En qué se diferencian los socios anuales y los ciclistas ocasionales con respecto al uso de las bicicletas de Cyclistic?
¿Por qué los ciclistas ocasionales comprarían membresías anuales de Cyclistic?
¿Cómo puede usar Cyclistic los medios digitales para influenciar a los ciclistas ocasionales a convertirse en miembros?



Moreno te asignó la primera pregunta por responder: ¿En qué se diferencian los socios anuales y los ciclistas ocasionales con respecto al uso de las bicicletas de Cyclistic?

Crearás un informe con los siguientes entregables:
Una instrucción clara de la tarea empresarial
Una descripción de todas las fuentes de datos utilizadas
Documentación de todas las limpiezas y manipulaciones de datos
Un resumen de tu análisis
Visualizaciones de respaldo y hallazgos clave
Las tres recomendaciones más importantes basadas en tu análisis

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
Usarás los datos históricos de los viajes de Cyclistic para analizar e identificar tendencias. Descarga los últimos 12 meses de datos de viajes de Cyclistic  aquí. (Nota: Los conjuntos de datos tienen un nombre diferente porque Cyclistic es una empresa ficticia. A los fines de este caso práctico, los conjuntos de datos son apropiados y te permitirán responder las preguntas de la empresa. Los datos han sido proporcionados por Motivate International Inc. bajo esta licencia.) Estos son datos públicos que puedes usar para explorar cómo difieren los tipos de clientes que usan las bicicletas Cyclistic. Sin embargo, ten en cuenta que, por cuestiones de privacidad de los datos, se te prohíbe usar información de identificación personal de los ciclistas. Esto significa que no podrás conectar las compras de pases con los números de tarjetas de crédito para determinar si los ciclistas ocasionales viven en el área de servicio de Cyclistic o si compraron varios pases de un solo viaje.

Ahora, prepara tus datos para el análisis usando el siguiente mapa de ruta de caso práctico como guía:

Mapa de ruta de caso práctico - Preparar
Preguntas orientativas
¿Dónde se ubican tus datos?
¿Cómo están organizados los datos?
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
Descarga los últimos 12 meses de datos de viajes de Cyclistic.
Descomprime los archivos.
Crea una carpeta en tu escritorio o en Drive para alojar los archivos. Usa convenciones apropiadas de nomenclatura de archivos.
Crea subcarpetas para archivos .CSV y .XLS o Sheets para tener una copia de los datos originales. Mueve los archivos descargados a la subcarpeta apropiada.
Sigue estas instrucciones para Excel (a) o Google Sheets (b):
Inicia Excel, abre cada archivo y elige Guardar como un archivo de Libro de Excel. Colócalo en la subcarpeta que creaste para archivos .XLS.
Abre cada archivo .CSV en Google Sheets y guárdalo en la subcarpeta apropiada.
Abre tu hoja de cálculo y crea una columna que se llame “ride_length”. Calcula la extensión de cada viaje restando la columna “started_at” de la columna “ended_at” (por ejemplo, =D2-C2) y usa el formato HH:MM:SS mediante Formato > Celdas > Hora > 37:30:55.
Crea una columna llamada “day_of_week” y calcula el día de la semana en el que empezó cada viaje mediante el comando “WEEKDAY” (por ejemplo, =WEEKDAY(C2,1)) en cada archivo. Utiliza el formato General o número sin decimales, observa que 1 = domingo y 7 = sábado.
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


Seguir estos pasos para usar hojas de cálculo
Abre tu aplicación de hojas de cálculo, luego completa los siguientes pasos:
Cuando corresponda, haz que las columnas sean coherentes y combínalas en una sola hoja de trabajo.
Limpia y transforma tus datos para prepararlos para el análisis.
Realiza un análisis descriptivo.
Ejecuta algunos cálculos en un archivo para tener una mejor idea de la disposición de los datos. Opciones:
Calcular la media de ride_length
Calcular el máximo de ride_length
Calcular el modo de day_of_week
Crear una tabla dinámica para calcular y visualizar los datos rápidamente. Opciones:
Calcular el promedio de ride_length para miembros y para ciclistas ocasionales. Probar rows = member_casual; Values = Average


of ride_length.
Calcular el promedio de ride_length para usuarios por day_of_week. Probar columns = day_of_week; Rows = member_casual; Values = Average of ride_length.
Calcular el número de viajes para usuarios por day_of_week sumando el recuento de trip_id a Values.
Abrir otro archivo y realizar los mismos pasos de análisis descriptivo. Explorar diferentes temporadas para hacer algunas observaciones iniciales.
Una vez que hayas trabajado durante algún tiempo con las hojas de cálculo individuales, fusiónalas en una vista de todo el año. Haz esto con la herramienta que hayas elegido para realizar tu análisis final, ya sea una hoja de cálculo, una base de datos y SQL o R Studio.
Exporta un archivo de resumen para su posterior análisis.

Sigue estos pasos para usar SQL
Abre la herramienta SQL que prefieras, luego completa los siguientes pasos:
Importa tus datos.
Explora tus datos, quizás mirando el número total de filas, los valores distintos, el máximo, el mínimo o los valores medios.
Cuando corresponda, usa las instrucciones JOIN para combinar tus respectivos datos en una tabla.
Crea estadísticas de resumen.
Investiga las tendencias interesantes y guarda esa información en una tabla.

Sigue estos pasos para usar R
Abre R Studio y usa este script para completar los siguientes pasos:
Importa tus datos.
Organiza las columnas y fusiónalas en un solo marco de datos.
Limpia y añade datos para prepararlos para el análisis.
Realiza un análisis descriptivo.
Exporta un archivo de resumen para su posterior análisis.


Compartir
Como ya has realizado tu análisis y obtenido algunos conocimientos sobre tus datos, ahora crea las visualizaciones para compartir tus hallazgos. Moreno te recordó que los datos deben ser sofisticados y bien pulidos para poder comunicarse efectivamente al equipo ejecutivo. Usa el siguiente mapa de ruta de caso práctico como guía:

Mapa de ruta de caso práctico - Compartir
Preguntas orientativas
¿Pudiste responder la pregunta en qué se diferencian los socios anuales y los ciclistas ocasionales de Cyclistic?
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
Cuando ya hayas elegido una forma visual, abre la herramienta que prefieras y crea tu visualización. Usa un software para presentaciones, por ejemplo,


PowerPoint o Google Slides; tu programa de hojas de cálculo; Tableau o R.
Crea tu visualización de datos, recuerda que se debe usar el contraste para captar la atención de la audiencia y dirigirla hacia los conceptos más importantes. Usa principios artísticos que incluyan el tamaño, el color y la forma.
Garantiza un significado claro mediante el uso adecuado de elementos comunes, por ejemplo, títulos, subtítulos y etiquetas.
Perfecciona la visualización de tus datos mediante una especial atención a los detalles.

Actuar
Ahora que terminaste de crear tus visualizaciones, actúa en función de tus hallazgos. Prepara los entregables que Moreno te pidió que crearas, incluso las tres recomendaciones principales que se basan en tu análisis. Usa el siguiente mapa de ruta de caso práctico como guía:

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
Las tres recomendaciones más importantes basadas en tu análisis


Sigue estos pasos:


Si todavía no tienes un portfolio, crea uno en línea. (Usa Crear un portfolio interactivo con Google Sites o Construir un portfolio con Google Sites.)
Considera cómo quieres presentar tu caso práctico en tu portfolio.
Carga o vincula los hallazgos de tu caso práctico a tu portfolio.
Escribe un párrafo breve que describa el caso práctico, su proceso y tus hallazgos.
Añade el párrafo para presentar tu caso práctico en tu portfolio.

