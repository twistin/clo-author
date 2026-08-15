# Declaración de uso de IA — borrador

**Formato:** AID Framework (ACRL), seis apartados, al final del documento tras las referencias.
**Fuente:** Corral, C. (14 mayo 2025), «Cómo declarar el uso de IA en trabajos académicos», blog InvestigaUNED, Biblioteca UNED.
**Estado:** BORRADOR — requiere confirmación del autor en los puntos marcados `[VERIFICAR]`.

> **Aviso de alcance.** La entrada de InvestigaUNED es una recomendación de buenas prácticas de
> la Biblioteca, no la normativa de la Escuela Internacional de Doctorado. Antes del depósito hay
> que contrastar esta declaración con el reglamento de la EIDUNED y con el criterio del tutor.

---

## A. Versión para el artículo «¿Auténtica o inauténtica? La Feria de la Chinita venezolana en Galicia»

### Declaración de uso de herramientas de inteligencia artificial

**Herramienta utilizada.** Claude (Anthropic), empleado a través de la interfaz Claude Code sobre
un entorno de trabajo documentado. Whisper (OpenAI), ejecutado localmente, para la transcripción
automática de las grabaciones de entrevista.

**Propósito del uso.** La asistencia se empleó en seis funciones diferenciadas: (1) búsqueda
bibliográfica y elaboración de fichas de lectura; (2) construcción de esquemas y estructura
argumental; (3) pulido gramatical y estilístico de texto dictado por el autor; (4) redacción de
borradores parciales de pasajes descriptivos de la sección etnográfica, a partir de las notas de
observación y del registro audiovisual del autor; (5) crítica y evaluación de borradores propios
mediante rúbricas de calidad definidas por el autor; (6) transcripción automática de las
entrevistas. No se empleó para el diseño de la investigación, la selección de informantes ni la
formulación de las preguntas de investigación.

**Prompts o instrucciones proporcionadas.** El trabajo se organizó mediante agentes con
instrucciones persistentes documentadas en el repositorio del proyecto, no mediante prompts
sueltos. Las instrucciones son de tres tipos, representados por estos ejemplos:

- «Investiga las fuentes primarias sobre [tema]. Devuelve solo fuente, dato clave, fecha y URL.»
- «Redacta el bloque de la sección 4 sobre [elemento observado] a partir de estas notas de campo,
  en descripción densa, separando datos de interpretación.»
- «Evalúa este borrador contra los criterios de credibilidad, transferibilidad, dependabilidad y
  confirmabilidad. No edites el archivo; devuelve deducciones razonadas.»

El registro completo de intervenciones —fecha, función, archivo afectado y decisión editorial
resultante— se conserva en el diario de investigación del proyecto (`research_journal.md`) y está
disponible para la comisión.

**Uso del contenido generado.** El material generado se integró en tres regímenes distintos:

- *Material de trabajo no incorporado.* La bibliografía anotada, el mapa de literatura y las fichas
  de lectura son instrumentos de trabajo interno. Sus formulaciones no pasan al texto del artículo;
  las referencias fueron verificadas contra las fuentes originales antes de citarse.
- *Texto de voz del autor.* Parte de la sección etnográfica se produjo por dictado del autor sobre
  esquema propio, con intervención de la herramienta limitada a la corrección gramatical. La
  formulación es del autor.
- *Borradores reescritos.* Determinados pasajes descriptivos de la sección 4 se redactaron en
  primera versión por la herramienta a partir de notas de observación del autor, y fueron
  posteriormente revisados y reformulados por él. `[VERIFICAR: confirmar que la pasada de revisión
  del autor sobre los cuatro bloques del 20/07/2026 se ha completado; el diario la deja pendiente.]`

**Revisión y edición.** Todo el contenido generado fue sometido a revisión del autor antes de su
incorporación. Las referencias bibliográficas se contrastaron con las fuentes originales; el
proceso detectó y corrigió al menos un error de atribución `[el PDF fichado como Huyssen (2003)
Present Pasts resultó ser un artículo distinto del mismo autor y año]`. Las transcripciones
automáticas se cotejaron con el audio original. La interpretación teórica, la construcción del
argumento y las conclusiones son del autor.

**Limitaciones y consideraciones éticas.** Se identifican cuatro:

1. *Autoría y responsabilidad.* La responsabilidad sobre la autoría, la veracidad y la
   interpretación de los contenidos recae exclusivamente en el autor.
2. *Datos de campo y terceros.* El uso de una herramienta alojada externamente implica que
   materiales de campo —transcripciones, notas de observación y fichas de informantes— han sido
   procesados por un proveedor externo. `[VERIFICAR: contrastar con lo prometido a los informantes
   en el consentimiento informado. Si el consentimiento no contempla el tratamiento por terceros,
   hay que decidir entre (a) restringir el uso de la herramienta al material ya anonimizado, o
   (b) ampliar el consentimiento.]`
3. *Anonimización.* Los informantes aparecen bajo pseudónimo y los datos identificables han sido
   generalizados según el protocolo descrito en el capítulo metodológico.
4. *Marcado del contenido.* Desde agosto de 2026 el proveedor incorpora marcas de agua estadísticas
   en el texto generado. Esta declaración hace innecesaria cualquier inferencia sobre su presencia:
   el uso queda documentado aquí de forma explícita.

---

## B. Notas para la versión de la tesis

La declaración de la tesis no puede ser esta misma con el nombre cambiado. Tres diferencias:

1. **Ubicación doble.** En la tesis, la declaración va al final (tras las referencias), pero el
   capítulo metodológico debe recoger además el uso de IA como parte de la reflexividad del
   investigador — junto al consentimiento, la anonimización y la posición del investigador en el
   campo. `fieldwork.md` ya exige esos tres; este es el cuarto.
2. **Alcance temporal.** La tesis cubrirá varios años de trabajo con configuraciones distintas.
   El diario de investigación es lo que permite declarar por fases en lugar de en bloque.
3. **Normativa aplicable.** Pendiente de verificar el reglamento de la EIDUNED. Si exige un
   formulario propio, este texto se convierte en anexo, no en declaración principal.

---

## Pendientes

- [ ] Verificar el reglamento de la Escuela Internacional de Doctorado de la UNED sobre uso de IA.
- [ ] Consultar el criterio del tutor antes del depósito.
- [ ] Resolver los tres `[VERIFICAR]` del apartado A.
- [ ] Comprobar si los memos analíticos del vault (`ANA_*`) contienen texto generado; si es así,
      ampliar el apartado «Propósito del uso» con la función de análisis.
