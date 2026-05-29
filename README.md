# 🖥️ Presentación de tesis - Bioética
[Abrir diagrama](https://leirylauramc.github.io/Presentacion_tesis_bioetica/)

# Diapositiva 1 — Portada
Buenos días. Mi nombre es Leiry Mares y hoy les voy a presentar mi propuesta de investigación de maestría, que trata sobre el diseño y validación biomecánica de una órtesis patelofemoral personalizada mediante modelación computacional. Aunque el proyecto en sí es de ingeniería biomédica, hoy quiero enfocarme en algo que considero igual de importante: las implicaciones éticas de hacer investigación con personas.

# Diapositiva 2 — Contexto
Para entender el proyecto, necesito situarlos un poco. La rodilla tiene una articulación que se llama patelofemoral, que es la que se forma entre la rótula y el fémur. Cuando esa articulación no funciona bien, aparece lo que se conoce como síndrome de dolor patelofemoral, que representa entre el 11 y el 17% de todas las consultas por dolor de rodilla. Afecta principalmente a mujeres jóvenes y personas activas, y si no se trata bien, puede volverse crónico.
El tratamiento incluye el uso de órtesis, que son dispositivos externos que se ponen sobre la rodilla para mejorar su funcionamiento. El problema es que las que existen hoy en el mercado son genéricas: están diseñadas para el promedio de la población, no para cada persona. Y eso explica por qué algunas personas mejoran con una órtesis y otras no. Mi propuesta es diseñar un dispositivo personalizado, adaptado a la anatomía específica de cada usuario.

# Diapositiva 3 — Planteamiento del problema
Ahora bien, ¿cuál es exactamente el problema que quiero resolver? Hay una revisión Cochrane, que es uno de los estudios de mayor rigor en medicina, que encontró algo que me parece muy revelador: ningún ensayo clínico sobre órtesis patelofemoral ha medido si el dispositivo realmente cambia cómo se mueve la rótula o qué presiones soporta el cartílago. Solo han medido si el paciente dice que le duele menos. Eso es una brecha enorme.
Mi pregunta de investigación es esta: ¿puede una órtesis personalizada, diseñada desde la modelación computacional, reducir las cargas sobre la articulación sin alterar el movimiento natural ni la función muscular? Eso es lo que busco responder.

# Diapositiva 4 — Justificación
¿Por qué vale la pena hacer esta investigación? Desde el punto de vista científico, porque va a generar datos sobre lo que ocurre dentro de la articulación, algo que no se puede medir sin cirugía. Desde lo social, porque si logramos un dispositivo más efectivo y fabricado con impresión 3D de bajo costo, se puede democratizar el acceso al tratamiento ortésico en Colombia, donde los dispositivos personalizados son costosos y poco accesibles.
Y desde la ética, que es lo que más nos interesa hoy, porque la forma en que está planteado el estudio pone la seguridad del participante por delante. La primera fase es completamente computacional: primero optimizamos el dispositivo en el computador, y solo cuando tengamos un diseño validado pasamos a trabajar con personas. Eso no es solo una decisión técnica, es una decisión ética.

# Diapositiva 5 — Hipótesis
La hipótesis que guía todo el trabajo es que una órtesis personalizada, optimizada computacionalmente, puede reducir los momentos articulares en actividades como bajar escaleras o hacer sentadilla, sin restringir el movimiento ni afectar la activación del cuádriceps. En otras palabras: que el dispositivo ayuda sin interferir.
Lo que varía en el estudio es la configuración del dispositivo, su geometría y sus materiales. Y lo que medimos es cómo cambia la mecánica de la rodilla al usarlo.

# Diapositiva 6 — Objetivos
El objetivo general es diseñar y validar computacionalmente esa órtesis personalizada. Para llegar ahí, tengo tres objetivos específicos: primero, construir un modelo computacional de la rodilla del participante; segundo, diseñar la órtesis adaptada a su anatomía; y tercero, evaluar mediante simulación si el dispositivo cumple lo que promete, antes de fabricarlo físicamente.
Noten que los tres objetivos son previos a la fabricación. Esa secuencia no es casual, es deliberada: queremos tener certeza computacional antes de poner cualquier cosa sobre una persona.

# Diapositiva 7 — Metodología
La metodología sigue cinco etapas. Primero capturamos los datos del participante: su movimiento, las fuerzas que ejerce al caminar, y la geometría de su pierna mediante escaneo 3D. Con eso construimos el modelo musculoesquelético en OpenSim, que es un software de código abierto. Luego diseñamos la órtesis en CAD, adaptada a ese modelo. Antes de fabricarla, la sometemos a un análisis de elementos finitos para verificar que aguanta las cargas sin romperse. Y finalmente comparamos computacionalmente cómo se comporta la rodilla con y sin órtesis.
Un punto importante para esta materia: la captura de datos con participantes humanos solo ocurre en la primera etapa, y solo después de que el Comité de Ética Institucional de la Universidad del Norte haya aprobado el protocolo. No antes.

# Diapositiva 8 — Marco normativo
En cuanto al marco normativo que rige esta investigación, hay cuatro referentes fundamentales.
La Resolución 8430 de 1993 es la norma colombiana que regula la investigación en salud. Bajo esa norma, este estudio se clasifica como de riesgo mínimo, porque la captura de movimiento es superficial y no invasiva. Aun así, exige consentimiento informado y aprobación del comité de ética.
La Ley 1581 de 2012 regula la protección de datos personales. Los datos de movimiento y de imagen corporal que recolectamos son datos personales, y deben manejarse con finalidad definida, consentimiento explícito y respeto al habeas data.
La Declaración de Helsinki es el referente internacional por excelencia para investigación con seres humanos. Fundamenta los principios de beneficencia, no maleficencia, autonomía y justicia que estructuran todo nuestro protocolo.
Y el estándar ASME V&V 40 establece cómo se debe verificar y validar un modelo computacional cuando ese modelo va a usarse para tomar decisiones sobre un dispositivo médico. Nos obliga a documentar la credibilidad del modelo antes de usarlo para diseñar algo que va a estar en contacto con una persona.

# Diapositiva 9 — Principios bioéticos
Más allá de las normas, quiero hablar de los principios éticos concretos que guían las decisiones del estudio.
Beneficencia y no maleficencia: la razón por la que hacemos toda la validación computacional primero es precisamente esta. No queremos que nadie use un dispositivo que no hemos probado. El modelo computacional nos permite cometer errores de diseño en la pantalla, no en la rodilla de un paciente.
Autonomía: los participantes van a recibir toda la información sobre qué implica participar, en lenguaje que puedan entender, y van a poder retirarse en cualquier momento sin ninguna consecuencia.
Justicia: los criterios para seleccionar participantes serán objetivos, clínicos y biomecánicos. No va a haber ningún criterio que excluya a alguien por su condición económica, género o etnia.
Y el consentimiento informado: vamos a elaborar un formulario claro, accesible, que cumpla con la Resolución 8430 y con la Ley 1581 en materia de datos personales.
Todo esto, además, tiene que pasar por el Comité de Ética Institucional antes de que empiece cualquier fase experimental.

# Diapositiva 10 — Cierre
Para cerrar, quiero dejar esta idea: hacer ciencia con rigor ético no es un trámite ni un requisito que se cumple para poder publicar. Es la única manera responsable de trabajar con personas. En este proyecto, cada decisión metodológica tiene un correlato ético, y eso es algo que construimos desde el diseño, no algo que añadimos al final.
Quedo disponible para sus preguntas.
