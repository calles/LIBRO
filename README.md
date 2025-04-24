# NHSN
# RED NACIONAL DE SEGURIDAD EN LA ATENCIÓN MÉDICA
# Evento de Infección del Sitio Quirúrgico (ISQ)
# Enero 2025

## Tabla de Contenidos

*   Introducción .......................................................................................................................................... 1
*   Ámbitos (Settings) ................................................................................................................................ 2
*   Requisitos ............................................................................................................................................... 2
*   Métodos de Vigilancia ............................................................................................................................ 3
*   Códigos de Procedimientos Quirúrgicos .............................................................................................. 3
*   Definición de un Procedimiento Quirúrgico NHSN .............................................................................. 4
*   Detalles del Evento de ISQ .................................................................................................................... 5
*   Detalles del Denominador para el Procedimiento ............................................................................... 7
*   Tabla 1. Criterios de Infección del Sitio Quirúrgico ............................................................................ 11
*   Tabla 2. Períodos de Vigilancia para ISQ Después de Categorías Seleccionadas de Procedimientos Quirúrgicos NHSN ..... 16
*   Tabla 3. Sitios Específicos de una ISQ de Órgano/Espacio ................................................................. 17
*   Reporte de Evento de ISQ (Numerador) ............................................................................................ 18
*   Tabla 4. Lista de Selección de Categoría Principal de Procedimiento Quirúrgico NHSN .................. 23
*   Reporte del Denominador para el Procedimiento ............................................................................. 24
*   Análisis de Datos ................................................................................................................................. 27
*   Tabla 5. Criterios de Inclusión de ISQ en Modelos SIR ..................................................................... 30
*   Tabla 6. Criterios de Exclusión Universal para Procedimientos Quirúrgicos NHSN ............................ 31
*   Referencias .......................................................................................................................................... 33
*   APÉNDICE A .......................................................................................................................................... 34
*   APÉNDICE B .......................................................................................................................................... 40

---

## Introducción:

La encuesta de prevalencia de infecciones asociadas a la atención médica (IAAS) de los CDC encontró que hubo aproximadamente 110,800 infecciones del sitio quirúrgico (ISQ) asociadas con cirugías en pacientes hospitalizados en 2015¹. Basado en los resultados de datos de IAAS de 2023 publicados en el Informe de Progreso de IAAS de NHSN, hubo aproximadamente un aumento del 2% en la razón de infección estandarizada (SIR) de ISQ relacionada con todas las categorías de procedimientos quirúrgicos NHSN combinadas en comparación con el año anterior². Además, los datos de IAAS de 2023 encontraron un aumento significativo del 3% en la SIR relacionada con las categorías de procedimientos quirúrgicos NHSN del Proyecto de Mejora del Cuidado Quirúrgico (SCIP) en comparación con el año anterior². Se pueden encontrar datos adicionales sobre IAAS por ISQ en el Informe Anual de Progreso de IAAS².

Aunque se han logrado avances en las prácticas de control de infecciones, incluyendo la mejora de la ventilación del quirófano, métodos de esterilización, barreras, técnica quirúrgica y disponibilidad de profilaxis antimicrobiana, las ISQ siguen siendo una causa sustancial de morbilidad, hospitalización prolongada y mortalidad. Se informa que las ISQ representan el 20% de todas las IAAS y se asocian con un aumento de 2 a 11 veces en el riesgo de mortalidad, con el 75% de las muertes asociadas a ISQ directamente atribuibles a la ISQ³,⁴. La ISQ es el tipo de IAAS más costoso, con un costo anual estimado de $3.3 mil millones, y extiende la duración de la estancia hospitalaria en 9.7 días, con un costo de hospitalización aumentado en más de $20,000 por admisión³,⁵.

Se ha demostrado que la vigilancia de las ISQ con retroalimentación de datos apropiados a los cirujanos es un componente importante de las estrategias para reducir el riesgo de ISQ⁶⁻⁹. Un programa de vigilancia exitoso incluye el uso de definiciones de infección epidemiológicamente sólidas y métodos de vigilancia efectivos, estratificación de las tasas de ISQ según los factores de riesgo asociados con el desarrollo de ISQ y retroalimentación de datos⁷,⁸. La Guía del Comité Asesor de Prácticas de Control de Infecciones en la Atención Médica (HICPAC) de los CDC para la Prevención de la Infección del Sitio Quirúrgico proporciona estrategias basadas en evidencia para la prevención de ISQ⁹. Más recientemente, se publicó la actualización de 2022 de "Strategies to prevent surgical site infections in acute-care hospitals" (Estrategias para prevenir infecciones del sitio quirúrgico en hospitales de cuidados agudos), que ofrece recomendaciones para la prevención de ISQ en hospitales de cuidados agudos¹⁰.

---

## Ámbitos (Settings):

La vigilancia de pacientes quirúrgicos ocurrirá en cualquier instalación de hospitalización y/o departamento de procedimientos ambulatorios del hospital (HOPD) donde se realicen los procedimientos quirúrgicos NHSN seleccionados.

**Nota:** Los Centros de Cirugía Ambulatoria (CCA) que reportan a NHSN deben usar el Componente de Procedimiento Ambulatorio (OPC) para realizar la vigilancia de ISQ.

---

## Requisitos:

*   Realizar vigilancia de ISQ siguiendo al menos una categoría de procedimiento quirúrgico NHSN (utilizando los códigos de procedimiento quirúrgico NHSN asociados) según se indica en el Plan de Reporte Mensual de Seguridad del Paciente (CDC 57.106).
*   Recopilar datos de eventos de ISQ (numerador) y de procedimientos quirúrgicos (denominador) sobre todos los procedimientos incluidos en las categorías de procedimientos quirúrgicos seleccionadas indicadas en el plan de reporte mensual de la instalación.
*   Todos los procedimientos incluidos en el plan de vigilancia mensual de NHSN se monitorean para eventos de ISQ incisional superficial, incisional profunda y de órgano/espacio, y el tipo de ISQ reportado debe reflejar el nivel de tejido más profundo donde se cumplen los criterios de ISQ durante el período de vigilancia.
*   Los eventos de ISQ y los procedimientos a los que están vinculados se reportan a NHSN independientemente de la evidencia de infección notada en el momento de la cirugía.
*   Un evento de ISQ se atribuye a la instalación en la que se realiza el procedimiento quirúrgico NHSN.

---

## Métodos de Vigilancia:

El monitoreo de ISQ requiere una vigilancia activa, prospectiva y basada en el paciente. Se deben utilizar métodos de vigilancia concurrentes y posteriores al alta para detectar ISQ después de procedimientos quirúrgicos hospitalarios y ambulatorios.

Por ejemplo, estos métodos incluyen:
*   Revisión de historias clínicas o registros de pacientes de clínicas quirúrgicas
    *   Registros de admisión, readmisión, urgencias (ED) y quirófano (OR)
    *   Signos y síntomas de ISQ reportados por el paciente
    *   Informes de laboratorio, imagenología y otras pruebas diagnósticas
    *   Notas de clínicos/profesionales de la salud
    *   Códigos de Diagnóstico de Infección CIE-10-MC (ICD-10-CM) para impulsar una revisión adicional
*   Visitar la UCI y las salas – hablar con el personal de atención primaria
*   Encuestas a cirujanos por correo o teléfono
*   Encuestas a pacientes por correo o teléfono (aunque los pacientes pueden tener dificultades para evaluar sus infecciones).

Cualquier combinación de estos métodos (u otros métodos identificados por la instalación) con la capacidad de identificar todas las ISQ es aceptable para su uso; sin embargo, se deben utilizar los criterios de ISQ de NHSN. Para minimizar la carga de trabajo de los Prevencionistas de Infecciones (IP) en la recopilación de datos del denominador, los datos de procedimientos quirúrgicos pueden importarse. Consulte las especificaciones del archivo en: https://www.cdc.gov/nhsn/pdfs/ps-analysis-resources/ImportingProcedureData.pdf.

---

## Códigos de Procedimientos Quirúrgicos:

Los códigos de procedimientos quirúrgicos se utilizan en entornos de atención médica para comunicar información uniforme. Este amplio uso de códigos de procedimientos quirúrgicos permite a NHSN incorporar los códigos de procedimientos quirúrgicos para estandarizar el reporte de vigilancia de ISQ de NHSN. Los códigos de procedimientos quirúrgicos son **requeridos** para determinar la categoría correcta de procedimiento quirúrgico NHSN a reportar. Ingresar el código de procedimiento quirúrgico en la aplicación NHSN sigue siendo opcional pero se recomienda.

NHSN utiliza los siguientes sistemas de codificación de procedimientos quirúrgicos:

*   Clasificación Internacional de Enfermedades, 10ª Revisión, Modificaciones Clínicas/Sistema de Codificación de Procedimientos (CIE-10-MC/SCP), según lo definido por el Comité de Coordinación y Mantenimiento de CIE-10 del Centro Nacional de Estadísticas de Salud y los Centros de Servicios de Medicare y Medicaid (CMS).
*   Terminología de Procedimientos Actual (CPT), según lo definido por la Asociación Médica Americana (AMA).

La correspondencia (mapping) para los procedimientos quirúrgicos NHSN de CIE-10-SCP y CPT se encuentra en la sección "Documentos de Códigos de Procedimientos Quirúrgicos" de la página de Eventos de Infección del Sitio Quirúrgico (ISQ) en el sitio web de NHSN. Los documentos de correspondencia incluyen una definición general para cada categoría de procedimiento quirúrgico NHSN, así como una descripción para cada código de procedimiento quirúrgico individual.

**Nota:** Para fines de reporte en el plan, solo los procedimientos quirúrgicos NHSN se incluyen en la vigilancia de ISQ. Una infección asociada con un procedimiento que no está incluido en una de las categorías de procedimientos quirúrgicos NHSN no se considera una ISQ de NHSN, aunque la infección puede investigarse como una infección asociada a la atención médica (IAAS). Los eventos de ISQ solo pueden atribuirse a procedimientos quirúrgicos NHSN.

---

## Definición de un Procedimiento Quirúrgico NHSN:

Un Procedimiento Quirúrgico NHSN es un procedimiento:

*   que está incluido en la correspondencia de códigos de procedimientos quirúrgicos NHSN de CIE-10-SCP y/o CPT
    **Y**
*   se realiza durante una operación donde se hace al menos una incisión (incluyendo abordaje laparoscópico y orificios de trépano craneal) a través de la piel o membrana mucosa, o la entrada es a través de una incisión existente (como una incisión de un procedimiento quirúrgico previo)
    **Y**
*   se realiza en un quirófano (Q), definido como un área de atención al paciente que cumplía con los criterios del Instituto de Guías de Instalaciones (FGI) o del Instituto Americano de Arquitectos (AIA) para un quirófano cuando se construyó o renovó¹¹. Esto puede incluir un quirófano, sala de cesáreas, sala de radiología intervencionista o un laboratorio de cateterismo cardíaco.

---

## Detalles del Evento de ISQ

Las definiciones de período de ventana de infección (IWP), presente al ingreso (POA), infección asociada a la atención médica (IAAS) y marco de tiempo de infección repetida (RIT) **no aplican** al protocolo de ISQ. Para detalles adicionales sobre POA, consulte la Instrucción de Reporte de Evento de ISQ #2. Para detalles relacionados con la infección presente en el momento de la cirugía (PATOS), consulte la Instrucción de Reporte de Evento de ISQ #3.

### Período de Vigilancia para ISQ:

El marco de tiempo posterior a un procedimiento quirúrgico NHSN para monitorear e identificar un evento de ISQ. El período de vigilancia está determinado por la categoría del procedimiento quirúrgico NHSN (por ejemplo, COLO tiene un período de vigilancia de ISQ de 30 días y KPRO tiene un período de vigilancia de ISQ de 90 días, ver Tabla 2). Las ISQ incisionales superficiales se monitorean durante un período de 30 días para todos los tipos de procedimientos. Las ISQ incisionales secundarias se monitorean durante un período de 30 días independientemente del período de vigilancia para el sitio primario.

Cada viaje al quirófano para un procedimiento quirúrgico NHSN establece un período de vigilancia de ISQ para el sitio quirúrgico.

*   Si un paciente regresa al quirófano para un procedimiento quirúrgico **NHSN** y se ingresa al mismo sitio quirúrgico, el período de vigilancia del procedimiento quirúrgico NHSN anterior finaliza y comienza un **nuevo período de vigilancia de ISQ** al concluir el procedimiento.
*   Si dentro del período de vigilancia posterior a un procedimiento quirúrgico NHSN se realiza un procedimiento quirúrgico **no NHSN**, y se ingresan los tres niveles de tejido, el período de vigilancia de ISQ para el procedimiento quirúrgico NHSN finaliza al concluir el procedimiento quirúrgico no NHSN. El período de vigilancia de ISQ continúa para los niveles de tejido no ingresados durante el procedimiento quirúrgico no NHSN. No se establece un nuevo período de vigilancia después de un procedimiento quirúrgico no NHSN.

### Fecha del Evento (FDE) para ISQ:

Para una ISQ, la FDE es la fecha en que ocurre por primera vez el primer elemento utilizado para cumplir con el criterio de infección ISQ durante el período de vigilancia de ISQ. La FDE debe ocurrir dentro del período de vigilancia de ISQ para cumplir con los criterios de ISQ. El tipo de ISQ (incisional superficial, incisional profunda u órgano/espacio) reportado y la FDE asignada deben reflejar el nivel de tejido más profundo donde se cumplen los criterios de ISQ durante el período de vigilancia. Sinónimo: fecha de infección.

### Marco de Tiempo para elementos de ISQ:

Las definiciones de Período de Ventana de Infección (IWP), Presente al Ingreso (POA), Infección Asociada a la Atención Médica (IAAS) y Marco de Tiempo de Infección Repetida (RIT) **no aplican** a la vigilancia de ISQ. La vigilancia de ISQ se basa en un período de vigilancia de ISQ de 30 o 90 días, que está determinado por la categoría del procedimiento quirúrgico NHSN y el nivel de tejido del evento de ISQ. Las directrices de ISQ **no ofrecen un marco de tiempo estricto** para que ocurran los elementos de los criterios, pero históricamente, todos los elementos utilizados para cumplir un criterio de ISQ generalmente ocurren dentro de un marco de tiempo de 7 a 10 días. Para asegurar que todos los elementos se asocien a la ISQ, los elementos deben estar relacionados entre sí. Cada caso difiere según los elementos individuales que ocurren y el tipo de ISQ, pero la FDE para una ISQ debe ocurrir dentro del período de vigilancia de ISQ apropiado de 30 o 90 días.

### Escenarios de Bacteriemia Secundaria (BSI) para ISQ:

Para que una infección del torrente sanguíneo (BSI) se determine como secundaria a una ISQ, debe cumplirse uno de los siguientes escenarios:

**Escenario 1 (Todos los niveles de ISQ):** Al menos un organismo de la muestra de sangre coincide con un organismo identificado en la muestra específica del sitio que se utiliza como elemento para cumplir el criterio de ISQ de NHSN **Y** la muestra de sangre se recolecta durante el período de atribución de BSI secundaria. El período de atribución de BSI secundaria para ISQ es un período de 17 días que incluye la FDE de la ISQ, 3 días antes y 13 días después.

**O**

**Escenario 2 (Solo ISQ de Órgano/Espacio):** Un organismo identificado en la muestra de sangre es un elemento que se utiliza para cumplir el criterio de infección específico del sitio de ISQ de Órgano/Espacio de NHSN y se recolecta durante el marco de tiempo para los elementos de ISQ.

Para obtener instrucciones detalladas sobre cómo determinar si la identificación de organismos de una muestra de sangre representa una BSI secundaria, consulte la Guía de BSI Secundaria (Apéndice que se encuentra dentro del Protocolo de Evento de BSI).

---

## Detalles Requeridos del Denominador para el Procedimiento

Se puede encontrar orientación adicional en las Instrucciones para Completar el Formulario del Denominador para el Procedimiento (CDC 57.121).

### Estado físico ASA:

Evaluación por el anestesiólogo de la condición física preoperatoria del paciente utilizando el Sistema de Clasificación del Estado Físico de la Sociedad Americana de Anestesiólogos (ASA)¹². A los pacientes se les asigna una puntuación ASA de 1 a 6 en el momento de la cirugía. Los pacientes con una puntuación ASA de 1 a 5 son elegibles para la vigilancia de ISQ de NHSN. Los pacientes a los que se les asigna una puntuación ASA de 6 (un paciente declarado con muerte cerebral cuyos órganos se extraen con fines de donación) **no** son elegibles para la vigilancia de ISQ de NHSN.

### Diabetes:

La definición de vigilancia de ISQ de NHSN para diabetes indica que el paciente tiene un diagnóstico de diabetes que requiere manejo con insulina o un agente antidiabético no insulínico. Esto incluye:
*   Pacientes con "resistencia a la insulina" que están en manejo con agentes antidiabéticos.
*   Pacientes con diabetes gestacional.
*   Pacientes que no cumplen con sus medicamentos para la diabetes.

Los códigos de diagnóstico CIE-10-MC que reflejan el diagnóstico de diabetes también son aceptables para responder SÍ al campo de diabetes en la entrada del denominador del procedimiento si los códigos se documentan durante la admisión donde se realiza el procedimiento. Estos códigos se encuentran en la sección de la página de Eventos de Infección del Sitio Quirúrgico (ISQ) del sitio web de NHSN bajo "Documentos de Códigos de Procedimientos Quirúrgicos".

Algunos pacientes pueden recibir medicamentos para la diabetes por indicaciones distintas a la diabetes. Para fines de reporte de NHSN, el campo Diabetes = NO, si no hay diagnóstico de diabetes.

### Duración del procedimiento quirúrgico:

El intervalo en horas y minutos entre la Hora de Inicio del Procedimiento/Cirugía y la Hora de Finalización del Procedimiento/Cirugía, según lo definido por la Asociación de Directores Clínicos de Anestesia (AACD)¹³:
*   **Hora de Inicio del Procedimiento/Cirugía (PST):** Hora en que se inicia el procedimiento (por ejemplo, incisión para un procedimiento quirúrgico).
*   **Hora de Finalización del Procedimiento/Cirugía (PF):** Hora en que se completan y verifican como correctos todos los recuentos de instrumentos y esponjas, se completan todos los estudios radiológicos postoperatorios a realizar en el quirófano, se aseguran todos los apósitos y drenajes, y los médicos/cirujanos han completado todas las actividades relacionadas con el procedimiento en el paciente.

### Procedimiento quirúrgico de emergencia:

Un procedimiento que se documenta según el protocolo de la instalación como un procedimiento de Emergencia o Urgente.

### Anestesia general:

La administración de fármacos o gases que ingresan a la circulación general y afectan el sistema nervioso central para dejar al paciente sin dolor, amnésico, inconsciente y, a menudo, paralizado con músculos relajados. Esto no incluye la sedación consciente.

### Altura:

La altura más reciente del paciente documentada en el expediente médico en pies (ft.) y pulgadas (in.), o metros (m).

### Procedimiento Quirúrgico NHSN de Paciente Hospitalizado (Inpatient):

Un procedimiento quirúrgico NHSN realizado en un paciente cuya fecha de admisión a la instalación de atención médica y la fecha de alta son días calendario diferentes.

### Procedimiento Quirúrgico NHSN de Paciente Ambulatorio (Outpatient):

Un procedimiento quirúrgico NHSN realizado en un paciente cuya fecha de admisión a la instalación de atención médica y fecha de alta son el mismo día calendario.

### Cierre No Primario:

El cierre de la herida quirúrgica de una manera que deja el nivel de la piel completamente abierto después de la cirugía. El cierre de cualquier porción de la piel representa un cierre primario (ver definición de Cierre Primario a continuación). Para cirugías con cierre no primario, las capas de tejido profundo pueden cerrarse por algún medio (dejando el nivel de la piel abierto), o las capas profundas y superficiales pueden dejarse ambas completamente abiertas. Las heridas con cierre no primario pueden o no describirse como "empaquetadas" con gasa u otro material, y pueden o no cubrirse con plástico, "vacs de herida" u otros dispositivos o materiales sintéticos.
Ejemplos:
*   Laparotomía en la que la incisión se cerró hasta el nivel de las capas de tejido profundo, a veces llamadas "capas fasciales" o "fascia profunda", pero el nivel de la piel se dejó abierto.
*   El abdomen se deja completamente abierto después de la cirugía (un "abdomen abierto").

### Cierre Primario:

El cierre del nivel de la piel durante la cirugía original, independientemente de la presencia de alambres, mechas, drenajes u otros dispositivos u objetos que sobresalgan a través de la incisión. Esta categoría incluye cirugías donde la piel se cierra por algún medio. Por lo tanto, si alguna porción de la incisión se cierra a nivel de la piel, de cualquier manera, se debe asignar una designación de cierre primario a la cirugía.

**Nota:** Cuando un procedimiento tiene múltiples sitios de incisión/trócar laparoscópico y cualquiera de las incisiones se cierra primariamente, entonces la técnica del procedimiento se registra como cierre primario.

### Uso de Endoscopio/Laparoscopio (Scope):

Un instrumento utilizado para alcanzar y visualizar el sitio del procedimiento quirúrgico. En el contexto de un procedimiento quirúrgico NHSN, el uso de un endoscopio/laparoscopio implica la creación de varias incisiones pequeñas para realizar o ayudar en la realización de una operación en lugar del uso de una incisión tradicional más grande (específicamente, abordaje abierto).

Los códigos CIE-10-SCP pueden ser útiles para responder a esta pregunta sobre el scope. El quinto carácter indica el abordaje para llegar al sitio del procedimiento:

| 5º Carácter CIE-10 | Abordaje                                                                                                   | Designación NHSN Scope |
| :----------------- | :--------------------------------------------------------------------------------------------------------- | :--------------------- |
| 0                  | Abierto                                                                                                    | NO                     |
| 3                  | Percutáneo (Incluido solo en categorías CRAN y VSHN - procedimientos con orificios de TRÉPANO)             | NO                     |
| 4                  | Endoscópico percutáneo                                                                                     | SÍ                     |
| 7                  | Vía orificio natural o artificial                                                                          | NO                     |
| 8                  | Vía orificio natural o artificial con endoscopia                                                           | NO                     |
| F                  | Vía orificio natural o artificial con asistencia endoscópica percutánea                                    | SÍ                     |

Para los códigos CPT, la pregunta sobre el scope puede responderse basándose en la descripción del código del procedimiento. Usando el código HYST 58570 como ejemplo, la descripción del código indica Laparoscopia, quirúrgica, con histerectomía total. Laparoscopia es Scope = SÍ.

| HYST | 58570 | Laparoscopia, quirúrgica, con histerectomía total, para útero de 250 g o menos |
| :--- | :---- | :--------------------------------------------------------------------------- |

**Nota:** El Scope se reporta basándose en el sitio de la incisión primaria. Si se asigna un código abierto y un código de scope a procedimientos en la misma categoría de procedimiento NHSN, entonces el procedimiento debe reportarse a NHSN como Scope = NO. La designación abierta se considera un procedimiento de mayor riesgo.

### Trauma:

Lesión contusa o penetrante que ocurre antes del inicio del procedimiento. Los casos de trauma complejo pueden requerir múltiples viajes al quirófano durante la misma admisión para reparar el trauma inicial. En tales casos, Trauma = SÍ.

### Peso:

El peso más reciente del paciente documentado en el expediente médico en libras (lbs.) o kilogramos (kg) antes del procedimiento o lo más cercano posible a este.

### Clasificación de la herida:

Una evaluación del grado de contaminación de una herida quirúrgica en el momento del procedimiento quirúrgico. La clasificación de la herida es asignada por una persona involucrada en el procedimiento quirúrgico (por ejemplo, cirujano, enfermera circulante, etc.) basándose en el esquema de clasificación de heridas que se adopta dentro de cada organización. Las cuatro clasificaciones de heridas disponibles dentro de la aplicación NHSN son:
Limpia (L), Limpia-Contaminada (LC), Contaminada (CO) y Sucia/Infectada (S/I).

Las siguientes categorías de procedimientos quirúrgicos no pueden registrarse como limpias (L) dentro de la aplicación: APPY, BILI, CHOL, COLO, REC, SB y VHYS. Si se asignó una clasificación de herida limpia (L) a un procedimiento en una de estas categorías, el procedimiento no puede incluirse en el denominador para los datos del procedimiento. El IP no debe modificar la clasificación de la herida.

---

*(Las Tablas 1, 2, 3, 4, 5 y 6 y los Apéndices A y B contienen información muy detallada y específica, como listas de procedimientos, criterios exactos y variables. Traducirlas completamente y formatearlas correctamente en Markdown aquí sería extremadamente largo y propenso a errores. Se recomienda consultar las tablas y apéndices directamente en el documento original para obtener esa información específica. La traducción se centrará en las secciones de texto explicativo.)*

---

## Reporte de Evento de ISQ (Numerador)

### Datos del Numerador:
Todos los pacientes sometidos a cualquiera de los procedimientos incluidos en la(s) categoría(s) de procedimientos quirúrgicos NHSN seleccionadas son monitoreados para ISQ. Se completa el formulario de Infección del Sitio Quirúrgico (ISQ) (CDC 57.120) para cada ISQ. Si no se identifican eventos de ISQ durante el mes de vigilancia, marque la casilla "Reportar Cero Eventos" en la pestaña Eventos PA Faltantes de la Lista Incompleta/Faltante.

Las Instrucciones para Completar el Formulario de Infección del Sitio Quirúrgico (CDC 57.120) incluyen instrucciones breves para la recopilación y entrada de cada elemento de datos en el formulario. El formulario de ISQ incluye información demográfica del paciente y detalles específicos del evento que pertenecen al evento de ISQ.

### Instrucciones para el Reporte de Eventos de ISQ:

1.  **Organismos excluidos:** Organismos bien conocidos asociados a la comunidad (organismos pertenecientes a los siguientes géneros: *Blastomyces, Histoplasma, Coccidioides, Paracoccidioides, Cryptococcus* y *Pneumocystis*) y/o organismos asociados con infecciones latentes (por ejemplo, herpes, herpes zóster, sífilis o tuberculosis) están excluidos de cumplir los criterios de ISQ.
2.  **Atribución de ISQ a un procedimiento quirúrgico NHSN cuando hay evidencia de infección en el momento de la cirugía primaria:** La definición de presente al ingreso (POA) no se aplica al protocolo de ISQ. Si hay evidencia de infección presente en el momento del procedimiento y el paciente cumple los criterios de ISQ dentro del período de vigilancia de ISQ posterior al procedimiento, se atribuye una ISQ al procedimiento (para obtener orientación sobre la determinación de PATOS, consulte la Instrucción de Reporte de Evento de ISQ #3).
3.  **Infección presente en el momento de la cirugía (PATOS):** PATOS es un campo SÍ/NO que se encuentra en el formulario de evento de ISQ. PATOS denota que hubo evidencia de infección visualizada (vista) durante el procedimiento quirúrgico al que se atribuye una ISQ posterior. La evidencia de infección debe notarse intraoperatoriamente y documentarse dentro de la porción narrativa de la nota quirúrgica o informe de cirugía para ser elegible para PATOS (diagnósticos pre/post operatorios, 'indicación para cirugía' y otros encabezados incluidos rutinariamente en una nota quirúrgica no son elegibles para responder PATOS).
    *   Puntos clave para consideración:
        a)  Solo seleccione PATOS = SÍ cuando aplique a la profundidad de la ISQ que se está atribuyendo al procedimiento. Ejemplos:
            *   Cuando un paciente tiene documentación de una infección intraabdominal en el momento de la cirugía y luego regresa con una ISQ de órgano/espacio, PATOS = SÍ.
            *   Cuando un paciente tiene documentación de una infección intraabdominal en el momento de la cirugía y luego regresa con una ISQ incisional superficial o profunda, PATOS = NO.
        b)  Ejemplos de lenguaje que se considera evidencia de infección incluyen, pero no se limitan a: absceso, infección, purulencia/pus, flemón, osteomielitis o "peritonitis feculenta". Un apéndice roto/perforado es evidencia de infección a nivel de órgano/espacio.
        c)  Ejemplos de lenguaje que **no** se considera evidencia de infección incluyen, pero no se limitan a: perforación de colon, contaminación, necrosis, gangrena, derrame fecal, intestino lesionado durante el procedimiento, líquido turbio o documentación de inflamación.
        d)  El uso del sufijo "itis" en una nota/informe quirúrgico no cumple automáticamente con PATOS, ya que solo puede reflejar inflamación que no es de naturaleza infecciosa (por ejemplo, diverticulitis, peritonitis y apendicitis).
        e)  Los hallazgos del informe de patología y los hallazgos de pruebas de imagen no pueden utilizarse para la determinación de PATOS.
        f)  La identificación de un organismo mediante cultivo o método de prueba microbiológica sin cultivo o en un informe de patología de una muestra quirúrgica no puede utilizarse para la determinación de PATOS.
        g)  La asignación de la clasificación de la herida no puede utilizarse para la determinación de PATOS.
        h)  El trauma que resulta en un caso contaminado no cumple automáticamente el requisito de PATOS. Por ejemplo, una herida de bala reciente en el abdomen puede ser un trauma con una alta clasificación de herida, pero no habría tiempo para que se desarrolle una infección.
    *   Ejemplos de aplicación de PATOS:
        *   Un paciente se somete a una XLAP donde se encuentra un apéndice roto y se realiza una APPY. Dos semanas después, el paciente cumple los criterios para una ISQ IAB de órgano/espacio. El campo PATOS se selecciona como SÍ, ya que se notó un apéndice roto en el momento de la cirugía en el mismo nivel de tejido que la ISQ posterior.
        *   Durante un procedimiento COLO, el cirujano documenta múltiples abscesos en la cavidad intraabdominal. El paciente regresa tres semanas después y cumple los criterios para una ISQ incisional superficial. El campo PATOS se selecciona como NO, ya que no hubo documentación de evidencia de infección de los tejidos superficiales en el momento del COLO.
        *   Durante una CSEC, el cirujano lesiona el intestino y hay contaminación de la cavidad intraabdominal. Una semana después, la paciente cumple los criterios para una ISQ OREP de órgano/espacio. El campo PATOS se selecciona como NO, ya que no hay documentación de evidencia de infección en el momento de la CSEC. La lesión del colon es una complicación, pero no hay infección presente en el momento de la cirugía.
        *   Paciente se somete a una AMP debido a isquemia crónica. El paciente regresa dos semanas después y cumple los criterios para una ISQ incisional profunda. El campo PATOS se selecciona como NO, ya que no hay documentación de evidencia de infección en el momento de la AMP. La isquemia crónica no es suficiente como evidencia de infección.
    **Nota:** Para obtener más información sobre PATOS, consulte el Quick Learn titulado "Surgical Site Infection (SSI) Event PATOS – Infection Present at Time of Surgery".
4.  **Múltiples niveles de tejido están involucrados en la infección:** El tipo de ISQ (incisional superficial, incisional profunda u órgano/espacio) reportado debe reflejar el nivel de tejido más profundo donde se cumplen los criterios de ISQ durante el período de vigilancia. La FDE asignada es la fecha del primer elemento utilizado para cumplir los criterios de ISQ en el nivel de tejido más profundo que se cumple.
    *   Reporte la infección que cumple los criterios para ISQ de órgano/espacio como una ISQ de órgano/espacio, independientemente de la afectación del tejido superficial o profundo.
    *   Reporte la infección que cumple los criterios para ISQ incisional profunda como una ISQ incisional profunda, independientemente de la afectación del tejido superficial.
    *   Si un paciente cumple los criterios para una ISQ incisional profunda el día 10 del período de vigilancia de ISQ y una semana después (día 17 del período de vigilancia de ISQ) el paciente cumple los criterios para una ISQ de órgano/espacio, la FDE asignada es la fecha de la ISQ de órgano/espacio.
5.  **Atribución de ISQ a un procedimiento NHSN cuando se realizan varios en fechas diferentes:** Cuando un paciente tiene varios procedimientos quirúrgicos NHSN realizados en fechas diferentes, atribuya la ISQ al procedimiento quirúrgico NHSN realizado más recientemente.
    **Nota:** Para múltiples procedimientos quirúrgicos NHSN realizados dentro de un período de 24 horas, consulte la Instrucción de Reporte del Denominador #7.
6.  **Atribución de ISQ a procedimientos NHSN que involucran múltiples sitios de incisión primaria:** Cuando múltiples sitios de incisión primaria del mismo procedimiento quirúrgico NHSN se infectan, reporte como una única ISQ y asigne el tipo de ISQ (incisional superficial, incisional profunda u órgano/espacio) que represente el nivel de tejido más profundo donde se cumplen los criterios de ISQ en cualquiera de los sitios de incisión primaria involucrados durante el período de vigilancia. Ejemplos:
    *   Si una incisión laparoscópica cumple los criterios para una ISQ incisional superficial y otra incisión laparoscópica cumple los criterios para una ISQ incisional profunda, reporte una ISQ incisional profunda.
    *   Si uno o más sitios de incisión laparoscópica cumplen los criterios para ISQ incisional superficial pero el paciente también tiene una ISQ de órgano/espacio relacionada con el procedimiento, reporte una ISQ de órgano/espacio.
    *   Si un procedimiento quirúrgico se limita a una sola mama e involucra múltiples incisiones en esa mama que se infectan, reporte una única ISQ.
    *   En un procedimiento de formación o reversión de colostomía (desmontaje), el estoma y otros sitios de incisión abdominal se consideran incisiones primarias. Si tanto el estoma como otro sitio de incisión abdominal desarrollan ISQ incisional superficial, reporte como una ISQ (SIP).
7.  **Atribución de ISQ a procedimientos quirúrgicos NHSN que tienen sitios de incisión secundarios:** Ciertos procedimientos pueden involucrar incisiones secundarias (específicamente, BRST, CBGB, CEA, FUSN, PVBY, REC y VSHN). Los sitios de incisión secundarios se monitorean para ISQ Incisional Secundaria Superficial (SIS) e ISQ Incisional Secundaria Profunda (DIS). El período de vigilancia para todos los sitios de incisión secundarios es de 30 días, independientemente del período de vigilancia de ISQ incisional profunda o de órgano/espacio requerido para el(los) sitio(s) de incisión primaria (Tabla 2). Los procedimientos que cumplen esta designación se reportan como un procedimiento quirúrgico, aunque se pueden reportar hasta dos eventos de ISQ vinculados al procedimiento (una ISQ del sitio de incisión primaria y una ISQ del sitio de incisión secundaria). Por ejemplo:
    *   Un sitio de incisión de extracción de vena safena en un procedimiento CBGB se considera el sitio de incisión secundario. Se reporta un procedimiento CBGB, el sitio de extracción de vena safena se monitorea durante 30 días después de la cirugía para ISQ, y la incisión torácica se monitorea durante 90 días después de la cirugía para ISQ. Si el paciente cumple los criterios para una ISQ en el sitio de extracción de vena safena (como una ISQ incisional superficial) y cumple los criterios para una ISQ en el sitio torácico (como una ISQ incisional profunda), se reportan dos ISQ y se vinculan al procedimiento CBGB.
    *   Un sitio de extracción de tejido (por ejemplo, colgajo Miocutáneo Transverso del Recto Abdominal [TRAM]) en un procedimiento BRST se considera el sitio de incisión secundario. Se reporta un procedimiento BRST, y si el sitio de incisión secundario se infecta, repórtelo como SIS o DIS según corresponda.
8.  **ISQ detectada en otra instalación:** Un evento de ISQ es reportado por la instalación donde se realizó el procedimiento quirúrgico NHSN. Cuando se detecta una ISQ potencial en una instalación diferente a aquella donde se realizó el procedimiento, se debe proporcionar suficiente detalle a la instalación informante en caso de que se deba reportar una ISQ a NHSN. Si se determina una ISQ, la instalación informante debe indicar Detectado = RO (readmisión del paciente a una instalación distinta a donde se realizó el procedimiento) en el formulario de evento de ISQ al reportar la ISQ.
9.  **Atribución de ISQ después de que se realizan múltiples categorías de procedimientos NHSN durante un solo viaje al quirófano:** Cuando se realiza más de una categoría de procedimiento quirúrgico NHSN a través de un(os) único(s) sitio(s) de incisión/laparoscópico durante un solo viaje al quirófano, atribuya la ISQ al procedimiento asociado con la infección. Cuando la atribución no está clara, utilice las Listas de Selección de Categoría Principal de Procedimiento Quirúrgico NHSN (Tabla 4) para seleccionar el procedimiento quirúrgico al que se debe atribuir la ISQ. Por ejemplo, cuando un paciente cumple los criterios para una ISQ después de un solo viaje al quirófano en el que se realizaron tanto un COLO como un SB, y el origen de la ISQ no es aparente, asigne la ISQ al procedimiento COLO según la Tabla 4. La decisión final para la atribución de la ISQ recae en la instalación local basándose en los detalles completos del caso.
10. **ISQ después de manipulación invasiva o acceso al sitio quirúrgico:** Una ISQ **NO** se atribuirá cuando se cumplan **TODOS** los siguientes 3 criterios:
    *   durante el período postoperatorio no hay sospecha ni evidencia de infección relacionada con el sitio/espacio quirúrgico.
        **Y**
    *   se realiza una manipulación invasiva o acceso al sitio/espacio con fines diagnósticos o terapéuticos (por ejemplo, aspiración con aguja, acceso a derivaciones ventriculares, acceso a expansores mamarios).
        **Y**
    *   posteriormente se desarrolla una infección en un nivel de tejido al que se accedió durante la manipulación/acceso.
    *   **Notas:**
        *   La sospecha o evidencia de infección puede incluir signos y síntomas de infección (por ejemplo, fiebre, dolor abdominal) dependiendo del sitio del procedimiento.
        *   Los niveles de tejido no manipulados/accedidos siguen siendo elegibles para ISQ. Por ejemplo, un desbridamiento superficial después de un procedimiento COLO, donde no se ingresa al músculo/fascia y órgano/espacio, una ISQ incisional profunda u órgano/espacio posterior al desbridamiento puede ser una ISQ atribuible al procedimiento COLO.
        *   Esta instrucción de reporte NO se aplica a la manipulación cerrada (por ejemplo, reducción cerrada de una cadera dislocada después de un procedimiento ortopédico).
        *   La manipulación invasiva no incluye el empaquetamiento de heridas o el cambio de materiales de empaquetamiento de heridas como parte del cuidado postoperatorio.
        *   El lavado rutinario de catéteres como parte del cuidado y mantenimiento estándar de la instalación no se considera manipulación invasiva.
11. **Instrucciones de reporte para escenarios de infección postoperatoria:** Una ISQ debe reportarse a NHSN sin tener en cuenta accidentes postoperatorios, caídas, prácticas inadecuadas de ducha o baño, u otras ocurrencias que puedan o no ser atribuibles a acciones postoperatorias intencionales o no intencionales de los pacientes. También se debe reportar una ISQ independientemente de la presencia de ciertas afecciones de la piel (por ejemplo, dermatitis, ampollas, impétigo) notadas cerca de una incisión, e independientemente de la posible ocurrencia de un evento de "siembra" desde un procedimiento no relacionado (por ejemplo, trabajo dental). Esta instrucción relativa a diversas circunstancias postoperatorias es necesaria para reducir la subjetividad y la carga de recopilación de datos.

---

## Reporte del Denominador para el Procedimiento

### Datos del Denominador:
Se recopilan datos del denominador para cada categoría individual de procedimiento quirúrgico NHSN seleccionada para monitoreo en el Plan de Reporte Mensual de Seguridad del Paciente. Para todos los pacientes que tengan alguno de los procedimientos incluidos en la(s) categoría(s) de procedimientos quirúrgicos NHSN para los cuales se realiza vigilancia de ISQ durante el mes, complete el formulario Denominador para Procedimiento. Se requiere un código de procedimiento quirúrgico (CIE-10-SCP y/o CPT) para determinar la categoría correcta de procedimiento quirúrgico NHSN a reportar. Las Instrucciones para Completar el Formulario del Denominador para Procedimiento (57.121) incluyen instrucciones breves para la recopilación y entrada de cada elemento de datos en el formulario.

### Instrucciones para el Reporte del Denominador:

1.  **Diferentes categorías de procedimientos quirúrgicos realizadas durante el mismo viaje al quirófano:** Cuando se realizan procedimientos en más de una categoría de procedimiento quirúrgico NHSN durante el mismo viaje al quirófano a través de la misma o diferentes incisiones, se completa un formulario Denominador para Procedimiento para cada categoría de procedimiento quirúrgico NHSN que se está monitoreando en el Plan de Reporte Mensual.
    *   Por ejemplo: Si se realizan un CARD y un CBGC a través de la misma incisión durante el mismo viaje al quirófano, y ambos procedimientos se monitorean en el Plan de Reporte Mensual, complete un formulario Denominador para Procedimiento para cada procedimiento.
    *   Por ejemplo: Si después de un accidente automovilístico, un paciente tiene un FX y un SPLE realizados durante el mismo viaje al quirófano, y ambos procedimientos se monitorean en el Plan de Reporte Mensual, complete un formulario Denominador para Procedimiento para cada procedimiento.
    *   **EXCEPCIÓN:** Si un paciente tiene tanto un CBGC como un CBGB durante el mismo viaje al quirófano, reporte solo como CBGB. Solo reporte como CBGC si hay únicamente una incisión en el pecho. CBGB y CBGC nunca se reportan para el mismo paciente para el mismo viaje al quirófano.
2.  **Duración de los procedimientos quirúrgicos cuando se realiza más de una categoría de procedimiento NHSN a través de la misma incisión:** Si se realiza más de una categoría de procedimiento quirúrgico NHSN a través de la misma incisión durante el mismo viaje al quirófano, registre la duración combinada de todos los procedimientos, que es el tiempo desde la hora de inicio del procedimiento/cirugía hasta la hora de finalización del procedimiento/cirugía. Por ejemplo, si se realizan un CBGC y un CARD en un paciente durante el mismo viaje al quirófano, el tiempo desde la hora de inicio hasta la hora de finalización se reporta para ambos procedimientos quirúrgicos.
3.  **Duración de los procedimientos quirúrgicos si el paciente tiene dos procedimientos quirúrgicos NHSN diferentes realizados a través de incisiones separadas en el mismo viaje al quirófano:** Intente determinar la duración correcta para cada procedimiento separado (si está documentado); de lo contrario, tome el tiempo para ambos procedimientos y divídalo equitativamente entre los dos. Por ejemplo, si se realizan un AMP y un SPLE durante el mismo viaje al quirófano.
4.  **Misma categoría de procedimiento quirúrgico pero diferentes códigos CIE-10-SCP o CPT durante el mismo viaje al quirófano:** Si se realizan procedimientos de diferentes códigos CIE-10-SCP o CPT de la misma categoría de procedimiento quirúrgico NHSN a través de los mismos sitios de incisión/laparoscópicos, registre un procedimiento para esa categoría. Por ejemplo, una instalación está realizando vigilancia para procedimientos CARD y un paciente se somete a un reemplazo de las válvulas mitral y tricúspide durante el mismo viaje al quirófano (se asignan dos códigos de procedimiento CARD). Complete un formulario CARD Denominador para Procedimiento porque ambos procedimientos están en la misma categoría de procedimiento quirúrgico (CARD).
5.  **Para procedimientos de revisión HPRO y KPRO:** Si se realiza una revisión total o parcial de HPRO o KPRO, determine si alguno de los códigos de diagnóstico o procedimiento CIE-10-PCS/CM que indican infección (ver enlace a continuación) se asignó a la articulación índice en los 90 días anteriores e incluyendo la revisión índice de HPRO o KPRO. Si alguno de los códigos especificados se asigna al procedimiento, indique en el formulario Denominador para Procedimiento que la revisión se asoció con 'infección previa en la articulación índice' = SÍ. La variable 'infección previa en la articulación índice' solo se aplica a la revisión HPRO y KPRO. Los casos designados como 'infección previa en la articulación índice' = SÍ deben validarse antes de enviar el procedimiento a NHSN. Esta validación es necesaria para garantizar que el código esté alineado con la revisión de la articulación índice. La guía de mapeo de códigos CIE-10-PCS/CM se encuentra en el sitio web de NHSN en la sección de ISQ bajo "Documentos de Códigos de Procedimientos Quirúrgicos".
6.  **Misma categoría de procedimiento quirúrgico NHSN a través de incisiones separadas:** Para procedimientos quirúrgicos que pueden realizarse a través de incisiones separadas durante el mismo viaje al quirófano (específicamente los siguientes, AMP, BRST, CEA, FUSN, FX, HER, HPRO, KPRO, LAM, NEPH, OVRY, PVBY), se completan formularios Denominador para Procedimiento separados. Para documentar la duración de los procedimientos, indique la hora de inicio del procedimiento/cirugía hasta la hora de finalización del procedimiento/cirugía para cada procedimiento por separado o, alternativamente, tome el tiempo total para los procedimientos y divídalo equitativamente entre los procedimientos. El **Apéndice B** proporciona orientación para las 12 categorías de procedimientos quirúrgicos NHSN que pueden tener múltiples procedimientos reportados por categoría por paciente por día calendario.
    *   **Notas:**
        *   Un procedimiento COLO con formación de colostomía se considera un procedimiento COLO con múltiples sitios de incisión primaria.
        *   Las reparaciones de hernia laparoscópicas se consideran un procedimiento HER, independientemente del número de hernias reparadas en un viaje al quirófano. En la mayoría de los casos, solo habrá un tiempo de incisión documentado para este procedimiento. Si se documenta más de un tiempo, sume las duraciones. Las reparaciones de hernia abiertas (específicamente, no laparoscópicas) se reportan como un procedimiento HER por cada hernia reparada a través de una incisión separada (específicamente, si se hacen dos incisiones para reparar dos defectos, entonces se reportan dos procedimientos HER). Se anticipa que se registrarán tiempos de incisión separados para estos procedimientos. Si no, tome el tiempo total para ambos procedimientos y divídalo equitativamente entre los dos.
7.  **Más de un procedimiento quirúrgico a través de la misma incisión/espacio quirúrgico dentro de las 24 horas:** Cuando un paciente tiene más de un procedimiento quirúrgico a través de la misma incisión o en el mismo espacio quirúrgico y la hora de inicio del segundo procedimiento es dentro de las 24 horas de la hora de finalización del primer procedimiento, reporte un formulario Denominador para Procedimiento para el procedimiento **original**, combinando las duraciones de ambos procedimientos basándose en las horas de inicio y finalización del procedimiento para ambos procedimientos.
    *   Por ejemplo, un paciente tiene un CBGB que dura 4 horas y regresa al quirófano seis horas después para otro procedimiento quirúrgico a través de la misma incisión (por ejemplo, CARD). La segunda operación tiene una duración de 1.5 horas. Registre el procedimiento quirúrgico como un CBGB y la duración de la operación como 5 horas y 30 minutos. Si la clasificación de la herida ha cambiado, reporte la clasificación de herida más alta. No reporte el procedimiento CARD en sus datos de denominador.
    *   **Notas:**
        *   Si el primer procedimiento no es un procedimiento quirúrgico NHSN, esta guía no aplica.
        *   Cuando el paciente regresa al quirófano dentro de las 24 horas del final del primer procedimiento, asigne la técnica de cierre de la herida quirúrgica que aplica cuando el paciente sale del quirófano del primer procedimiento quirúrgico.
8.  **El paciente fallece en el quirófano:** Si un paciente fallece en el quirófano, no complete un formulario Denominador para Procedimiento. Este procedimiento quirúrgico se excluye del denominador.
9.  **HYST o VHYS:** Para fines de reporte de ISQ de NHSN, los códigos de procedimiento de histerectomía que involucran una incisión realizada en el abdomen, incluyendo la inserción de trócares, se enumeran en la categoría de histerectomía abdominal (HYST). Los códigos correctos de procedimiento de histerectomía CPT deben ser asignados por un codificador de registros médicos utilizando las directrices y convenciones actuales. Los procedimientos de histerectomía deben designarse como HYST o VHYS, basándose en el abordaje del procedimiento (5º carácter del código de procedimiento quirúrgico CIE-10) que asigna el codificador médico de la instalación al procedimiento de histerectomía.

    | Procedimiento | 5º Carácter CIE-10 | Abordaje                                                              |
    | :------------ | :------------------ | :-------------------------------------------------------------------- |
    | HYST          | 0                   | Abierto                                                               |
    |               | 4                   | Endoscópico percutáneo                                                |
    |               | F                   | Vía orificio natural o artificial con asistencia endoscópica percutánea |
    | VHYS          | 7                   | Vía orificio natural o artificial                                     |
    |               | 8                   | Vía orificio natural o artificial con endoscopia                      |

---

## Análisis de Datos

Una vez que los datos del procedimiento (denominador) y de ISQ (numerador) se recopilan y se ingresan en NHSN, los datos pueden analizarse/visualizarse de varias maneras, incluyendo informes de análisis descriptivos e informes de Razón de Infección Estandarizada (SIR).

### Tipos de Informes de Análisis de ISQ

**Informes de análisis descriptivos**
Las opciones de informes de análisis descriptivos, como listados lineales, tablas de frecuencia y gráficos de barras y circulares, están disponibles para los datos del numerador y del denominador.
También hay disponibles listados lineales, tablas de frecuencia y tablas de tasas para analizar los patógenos y los datos de susceptibilidad antimicrobiana reportados para cada ISQ. Se pueden encontrar guías de referencia rápida sobre estos informes al final de esta página: https://www.cdc.gov/nhsn/ps-analysis-resources/reference-guides.html

**Informes de Índice de Tasa Básica de ISQ**
Las tasas de ISQ por 100 procedimientos quirúrgicos se calculan dividiendo el número de ISQ por el número de procedimientos quirúrgicos y multiplicando los resultados por 100. Las ISQ se incluirán en el numerador de una tasa basándose en la fecha del procedimiento, no en la fecha del evento (FDE). Los cálculos de tasas de ISQ se pueden realizar por separado para los diferentes tipos de procedimientos quirúrgicos y estratificarse por el índice de riesgo básico utilizando los informes de Tabla de Tasas ubicados en la subcarpeta de ISQ de la carpeta Todos los Eventos Asociados a Procedimientos en los Informes Detallados de IAAS (Lista Lineal, Tablas de Tasas, etc.) en la función Informes de Análisis de la aplicación NHSN. Los criterios de exclusión universal y los criterios de inclusión de SIR no se aplican en el cálculo de la tasa de ISQ. La tasa de ISQ incluye eventos PATOS y procedimientos ambulatorios, pero excluye procedimientos con técnicas de cierre no primario. Se puede encontrar información adicional sobre el cálculo del índice de riesgo básico en el documento: https://www.cdc.gov/nhsn/pdfs/datastat/2009NHSNReport.pdf

**Informes SIR de ISQ**
El SIR se calcula dividiendo el número de infecciones observadas por el número de infecciones predichas. El SIR se calculará solo si el número de IAAS predichas ("numPred" en la aplicación NHSN) es ≥ 1 para ayudar a aplicar un criterio mínimo de precisión.

SIR = Observadas (O) IAAS / Predichas (P) IAAS

El número de infecciones predichas se calcula utilizando probabilidades de ISQ estimadas a partir de modelos de regresión logística multivariante construidos a partir de datos de NHSN durante un período de tiempo de referencia, que representa la experiencia de ISQ de una población estándar. Los procedimientos/ISQ que ocurren en adultos se modelan por separado de los que ocurren en pediatría. Además, los procedimientos/ISQ que ocurren en el ámbito hospitalario (inpatient) se modelan por separado de los que ocurren en el departamento de procedimientos ambulatorios del hospital (HOPD).

El SIR de ISQ se puede generar para procedimientos individuales para diferentes períodos de tiempo de resumen. Si bien el SIR de ISQ se puede calcular para categorías de procedimientos únicas y para cirujanos específicos, la medida también le permite resumir sus datos en múltiples categorías de procedimientos mientras se ajusta por las diferencias en la probabilidad estimada de infección entre los pacientes incluidos en las categorías de procedimientos. Por ejemplo, podrá obtener un SIR de ISQ ajustando para todos los procedimientos reportados. Alternativamente, puede obtener un SIR de ISQ solo para COLO dentro de su instalación.

**Notas Adicionales sobre los SIR de ISQ**

1.  **Técnica de cierre:** Todos los SIR de ISQ que utilizan los datos de referencia de ISQ de 2006-2008 (conjunto de referencia 1 o BS1) incluirán solo aquellos procedimientos que se reportaron con un método de cierre primario. De lo contrario, todos los demás datos de referencia incluirán todos los procedimientos que se reportaron con métodos de cierre primario o no primario.
2.  **Infección presente en el momento de la cirugía (PATOS):**
    a.  Todos los informes SIR de ISQ que utilizan la línea base de ISQ 2006-2008 (BS1) incluirán las ISQ que se reportan como presentes en el momento de la cirugía. Esto significa que el evento PATOS se incluye en el numerador del SIR y el procedimiento del cual ocurrió el evento se incluye en el denominador del SIR.
    b.  Todos los informes SIR de ISQ, distintos del conjunto de referencia 1, excluirán las ISQ que se reportan como presentes en el momento de la cirugía del numerador y los procedimientos a los que están vinculados del denominador. Por lo tanto, los eventos PATOS y sus procedimientos vinculados no se incluyen en ninguno de los informes SIR no BS1.
3.  **SIR basados en la Fecha del Procedimiento:** Las ISQ se incluirán en el numerador de un SIR basándose en la fecha del procedimiento, no en la FDE. Esto se debe a que el procedimiento conlleva el riesgo de infección/ISQ.

**Modelos e Informes SIR de ISQ**
Hay tres modelos principales de SIR de ISQ disponibles en NHSN, cada uno descrito brevemente en la tabla a continuación (Tabla 5). Los dos primeros modelos, el SIR All-SSI y los modelos SIR Complex A/R SSI, están disponibles para todos los procedimientos quirúrgicos/ISQ de NHSN que ocurren tanto en pacientes adultos como pediátricos, mientras que el tercer modelo, el SIR Complex 30-day SSI, está disponible solo para procedimientos de colon e histerectomía abdominal/ISQ que ocurren solo en adultos. Consulte la Guía SIR de NHSN para obtener información más específica del modelo: https://www.cdc.gov/nhsn/pdfs/ps-analysis-resources/nhsn-sir-guide.pdf

*(Tabla 5: Criterios de Inclusión de ISQ en Modelos SIR - Consulte el documento original para detalles)*
*(Tabla 6: Criterios de Exclusión Universal para Procedimientos Quirúrgicos NHSN - Consulte el documento original para detalles)*

---

## Análisis de Grupo NHSN:

Los Usuarios de Grupo de NHSN pueden realizar los mismos análisis que los usuarios a nivel de instalación en NHSN. A continuación, se enumeran algunas herramientas útiles en NHSN para grupos. Estas herramientas son guías sobre cómo iniciar y unirse a un Grupo; cómo crear una plantilla para solicitar datos de las instalaciones; cómo determinar el nivel de acceso otorgado por la instalación siguiendo los pasos anteriores y cómo analizar los datos de las instalaciones.

**Recursos de Análisis de Grupo:**
*   Enlace web de Usuarios de Grupo de NHSN: https://www.cdc.gov/nhsn/group-users/index.html
*   Guía del Usuario de Grupo para el Informe de Derechos de Membresía:
    *   https://www.cdc.gov/nhsn/pdfs/ps-analysis-resources/GroupAnalysisWebinar.pdf
*   Guía del Usuario de Grupo para las Alertas de Participación de Listado Lineal:
    *   https://www.cdc.gov/nhsn/pdfs/ps-analysis-resources/group-alerts.pdf
*   Guía del Usuario de Grupo para Generar Alertas de Participación
    *   https://www.cdc.gov/nhsn/pdfs/ps-analysis-resources/participationalerts-dataset-508.pdf
    *   https://www.cdc.gov/nhsn/pdfs/ps-analysis-resources/group-alerts.pdf

**Recursos Adicionales:**
*   Recursos de Análisis:
    *   https://www.cdc.gov/nhsn/ps-analysis-resources/index.html
    *   https://www.cdc.gov/nhsn/PS-Analysis-resources/reference-guides.html
*   Capacitación NHSN: https://www.cdc.gov/nhsn/training/index.html

---

## Referencias

*(La lista de referencias se mantiene en su formato original ya que son citas estándar en inglés)*
¹Magill, SS, O'Leary, E, Janelle, SJ, et al., "Changes in Prevalence of Health Care-Associated Infection in U.S. Hospitals". N Engl J Med, 379(18): (2018): 1732-44.
²CDC National and State Healthcare-Associated Infections Progress Report, published April 2024, available from: https://www.cdc.gov/healthcare-associated-infections/php/data/progress-report.html?CDC_AAref_Val=https://www.cdc.gov/hai/data/portal/progress-report.html#cdc_report_pub_study_section_2-2022-hai-progress-report
³Ban, KA, Minei JP, Laronga C, et al., "American College of Surgeons and Surgical Infection Society: Surgical Site Infection Guidelines, 2016 Update". J Am Coll Surg, 224(1): (2017): 59-74.
⁴Awad, SS, "Adherence to surgical care improvement project measures and post-operative surgical site infections". Surgical Infect (Larchmt), 13(4): (2012): 234-7.
⁵Zimlichman, E, Henderson D, Tamir O, et al., "Health care-associated infections. a meta-analysis of costs and financial impact on the US health care system". JAMA Intern Med, 173(22): (2013): 2039-46.
⁶Condon, RE, Schulte WJ, Malangoni MA, et al., "Effectiveness of a surgical wound surveillance program". Arch Surg, 118(3): (1983): 303-7.
⁷Consensus paper on the surveillance of surgical wound infections. The Society for Hospital Epidemiology of America; The Association for Practitioners in Infection Control; The Centers for Disease Control; The Surgical Infection Society. Infect Control Hosp Epidemiol, 13(10): (1992): 599-605.
⁸Haley, RW, Culver, DH,White, JW, et al., "The efficacy of infection surveillance and control programs in preventing nosocomial infections in US hospitals". Am J Epidemiol, 121(2): (1985):182-205.
⁹Berríos-Torres, SI, Umscheid CA, Bratzler DW, et al. "Centers for Disease Control and Prevention Guideline for the Prevention of Surgical Site Infection". JAMA Surg, 152(8): (2017):784-91.
¹⁰Calderwood MS, Anderson DJ, Bratzler DW, et al. "Strategies to prevent surgical site infections in acute-care hospitals: 2022 Update". Infection Control & Hospital Epidemiology, 44: (2023):695-720.
¹¹The Facility Guidelines Institute, Guidelines for Design and Construction of Hospitals. 2022, St. Louis, MO: Facility Guidelines Institute.
¹²American Society of Anesthesiologists. ASA Physical Status Classification System. Available from: https://www.asahq.org/standards-and-practice-parameters/statement-on-asa-physical-status-classification-system.
¹³Donham, RT, Mazzei WJ, and Jones RL, "Association of Anesthesia Clinical Directors' Procedure Times Glossary". Am J Anesthesiol, 23(5S): (1996):S1-S12.

---

*(Apéndice A: Tipos de eventos específicos disponibles para atribución de ISQ por categoría de procedimiento NHSN - Consulte el documento original para la lista detallada)*

---

*(Apéndice B: Guía para el Reporte de Múltiples Procedimientos - Consulte el documento original para la tabla detallada con explicaciones por categoría)*
