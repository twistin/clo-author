# Declaración de uso de IA — borrador

**Formato:** AID Framework (ACRL), seis apartados, al final del documento tras las referencias.
**Estado:** BORRADOR — requiere confirmación del autor en los puntos marcados `[VERIFICAR]`.

**Fuentes UNED:**
- Corral, C. (14 mayo 2025), «Cómo declarar el uso de IA en trabajos académicos», InvestigaUNED
  — establece el **formato** (AID Framework de la ACRL).
- Corral, C. (23 julio 2026), «Uso ético de la IA en la redacción científica», InvestigaUNED
  — establece los **criterios sustantivos**: qué usos son legítimos y cuáles no.

> **Aviso de alcance.** Ambas entradas son recomendaciones de buenas prácticas de la Biblioteca,
> no la normativa de la Escuela Internacional de Doctorado. Antes del depósito hay que contrastar
> esta declaración con el reglamento de la EIDUNED y con el criterio del tutor.

---

## Criterios sustantivos (InvestigaUNED, 23/07/2026) aplicados al proyecto

### Usos legítimos — situación actual

| Criterio | Práctica en este proyecto | Estado |
|---|---|---|
| 1.a Corrección lingüística y estilística | §4 dictado por el autor y pulido por el sistema (21/06/2026) | Conforme |
| 1.b Apoyo en la estructuración | Esquemas, coherencia entre secciones, rúbricas de evaluación | Conforme |
| 1.c Síntesis de ideas propias | Bloques de §4 redactados a partir de notas de observación del autor | Conforme, con matiz |

*Matiz sobre 1.c:* el post define el uso legítimo como «resumir un texto previamente escrito por el
propio autor». Los bloques del §4 no resumen un texto previo: expanden notas de campo a prosa. El
contenido es del autor; la formulación, del sistema. Es el límite exterior del 1.c y debe declararse
con esa precisión, sin presentarlo como mera corrección de estilo.

### Prácticas no recomendables — dos frentes abiertos

**2.b Uso de citas no verificadas.** `annotated_bibliography.md` (7.576 palabras) fue generada por
el agente `librarian`. Ya se materializó un error: el PDF fichado como Huyssen (2003) *Present Pasts*
resultó ser un artículo distinto del mismo autor y año. Fue detectado, pero confirma que el riesgo
es real.
→ **Acción obligatoria:** verificar en base de datos académica toda referencia que pase de esa
bibliografía al artículo o a la tesis. Ninguna cita se incorpora sin comprobación contra la fuente.

**2.a Generación sustantiva de contenido original.** `MEMO_synousia_marco_teorico_chinita.md`
(6.253 palabras) está redactado por el sistema: su cabecera registra «este memo conserva todo lo
discutido» y se refiere al autor en tercera persona. Sus epígrafes son «La propuesta conceptual»,
«La jugada propuesta», «Lo que synousia añade frente al canon». De ese memo deriva la §2.5 del
artículo.

`[VERIFICAR — DECISIÓN DEL AUTOR, BLOQUEANTE ANTES DE PUBLICAR]`
¿De quién procede la propuesta de *synousia* como concepto vertebrador del marco teórico?

- *Si es del autor* y el sistema solo la documentó y le buscó apoyo filológico en Pentassuglio:
  se está en el supuesto 1.c. Basta declararlo con precisión.
- *Si procede del sistema* y el autor la validó: se está en el supuesto 2.a, que el post identifica
  como comprometedor de la autoría intelectual. Cabe (a) reformular el marco desde criterio propio,
  o (b) declararlo explícitamente y asumir que el tribunal puede interrogarlo en la defensa.

*Evidencia documentada a favor de la autoría del investigador:*

1. El **diagnóstico** del que nace todo el aparato es suyo: registrado como «el usuario detectó dos
   lesiones del aparato canónico DeNora-Stokes-Hall-Gilroy» —el aplanamiento ontológico de la Feria
   y la elusión de la memoria por temor al esencialismo—. La propuesta conceptual responde a un
   problema que identificó él, no el sistema.
2. El **eje memorial** es formulación literal suya, con fecha (sesión 11/05/2026): «no puede haber
   identidad construida o producida en un espacio sin un marco común de memoria». De ahí deriva la
   incorporación de Connerton.
3. La **decisión ontológica** (posición C secularizada, 15/05/2026, descartando Marion, Henry y
   Pickstock) consta como decisión del autor, no de agente.
4. La **decisión editorial** de recortar §2.5 de 2.200 a 1.100 palabras es suya.
5. Las **lecturas** son suyas: Pentassuglio (2020) leído completo en OpenEdition; Connerton (1989)
   caps. I-III íntegros, con extracción de citas y páginas exactas.

Queda por precisar únicamente si el término *synousia* como etiqueta del concepto-puente lo propuso
el investigador o el sistema. Dado 1-5, la arquitectura teórica —problema, eje memorial, posición
ontológica, alcance— es del investigador aunque la respuesta fuese «el sistema»: se trataría de la
sugerencia de un término para un lugar conceptual ya definido por él, no de la delegación de la
sección teórica que el criterio 2.a prohíbe.

### Evitar la dependencia (§3 del post) — flujo objetivo

El post recomienda redactar borrador propio antes de consultar, usar la herramienta solo en
revisión, comparar siempre original y sugerencia, y limitar el uso en conceptualización. El proyecto
ya tiene identificados los dos flujos que cumplen esto —dictado sobre esquema propio, y corrección
devuelta como lista de cambios en lugar de texto reescrito—. Falta convertirlos en el modo por
defecto del agente `writer`.

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

Por orden de prioridad:

- [ ] **Precisar el origen del término *synousia*** (criterio 2.a). Ya no es bloqueante: la
      evidencia documentada sitúa el diagnóstico, el eje memorial y la decisión ontológica en el
      investigador. Solo hay que redactar la frase que lo declare con exactitud.
- [ ] **Contrastar el consentimiento informado** con el hecho de que los materiales de campo se han
      procesado en un servicio externo. Afecta a lo prometido a E001, E002 y E003.
- [ ] **Verificar toda referencia** procedente de `annotated_bibliography.md` contra base de datos
      académica antes de incorporarla (criterio 2.b).
- [ ] Verificar el reglamento de la Escuela Internacional de Doctorado de la UNED sobre uso de IA.
- [ ] Consultar el criterio del tutor antes del depósito.
- [ ] Confirmar si se completó la revisión del autor sobre los cuatro bloques del §4 (20/07/2026).
- [ ] Comprobar si los memos analíticos del vault (`ANA_*`) contienen texto generado; si es así,
      ampliar el apartado «Propósito del uso» con la función de análisis.
- [ ] Convertir el modo «lista de cambios» en comportamiento por defecto del agente `writer`.
