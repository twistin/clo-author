# Declaración de uso de IA — borrador

**Formato:** AID Framework (ACRL), seis apartados, al final del documento tras las referencias.
**Estado:** BORRADOR — requiere confirmación del autor en los puntos marcados `[VERIFICAR]`.

## Marco normativo aplicable, por peso

| Fuente | Naturaleza | Qué aporta |
|---|---|---|
| **Reglamento del CEI de la UNED** — anteproyecto de reforma, Vicerrectorado de Investigación | Norma **en tramitación**, no vigente. Derogaría el reglamento de 2018 (mod. 2019 y 2021) | Obligación de someter la tesis al CEI; criterios éticos sobre IA (art. 12.5.f) |
| Corral, C. (23 jul 2026), «Uso ético de la IA en la redacción científica», InvestigaUNED | Recomendación de la Biblioteca | Criterios sustantivos: usos legítimos vs. no recomendables |
| Corral, C. (14 may 2025), «Cómo declarar el uso de IA en trabajos académicos», InvestigaUNED | Recomendación de la Biblioteca | Formato de declaración (AID Framework, ACRL) |

Normativa externa invocada por el reglamento: RD 905/2025 de 7 de octubre (que modifica el art. 19
del RD 640/2021), Reglamento (UE) 2016/679 (RGPD) y Ley Orgánica 3/2018 de protección de datos.

> **Estado del reglamento del CEI.** El texto disponible es un anteproyecto en trámite de
> información pública. Sus criterios no obligan todavía, pero marcan la dirección y previsiblemente
> estarán vigentes antes del depósito. Conviene tratarlos como requisito, no como orientación.

---

## Obligación de evaluación ética de la tesis (reglamento del CEI)

Independiente de la cuestión de la IA, y **más urgente que ella**:

- **Art. 3.1 y 3.2 + art. 12.5.** Las tesis doctorales «en las que participen seres humanos […] o
  sus datos personales» se someten a evaluación del CEI, Sección Primera de Investigación en Seres
  Humanos (SISH). Esta tesis entra de lleno: entrevistas en profundidad, fichas de informantes,
  grabaciones y datos personales de E001, E002 y E003.
- **Art. 3.3.** La solicitud **la presenta el tutor o director**, firmada por él y por el estudiante.
  No es un trámite que el doctorando pueda iniciar por su cuenta.
- **Art. 3.2.** El CEI **debe aprobar los modelos de consentimiento informado**. Los consentimientos
  actualmente en uso no constan aprobados.
- **Art. 5.2.** Cualquier modificación sustancial en duración o contenidos se comunica al CEI. El
  alcance de esta tesis está pendiente de confirmar con el tutor, de modo que conviene fijarlo antes
  de solicitar la evaluación y no después.
- **Art. 6.3.** Mínimo seis reuniones ordinarias por curso; el calendario con las fechas máximas de
  recepción se publica en septiembre en la página del CEI.

`[VERIFICAR — PRIORITARIO]` ¿Se ha sometido ya esta tesis al CEI? El checklist de `fieldwork.md`
deja sin marcar «mención de la aprobación ética institucional». Si no se ha hecho y ya hay tres
entrevistas realizadas, hay que plantearlo con el tutor cuanto antes: bajo el reglamento vigente
(2021) la evaluación de tesis está redactada como posibilidad («pudieran ser, en su caso,
sometidas»), lo que da margen; bajo el anteproyecto pasa a ser exigencia.

---

## Criterios éticos sobre IA del CEI (art. 12.5.f) aplicados al proyecto

El artículo enumera cinco principios que la Sección Primera considerará cuando la iniciativa use
técnicas de inteligencia artificial. La declaración debe poder responder a los cinco:

| Principio | Situación en este proyecto | Evidencia |
|---|---|---|
| **Supervisión humana** | Toda salida pasa por decisión del autor; los críticos no editan archivos, solo puntúan | Separación de poderes en `agents.md`; decisiones editoriales registradas en el diario |
| **Transparencia** | Cubierta por esta declaración en formato AID | Pendiente de incorporar al artículo y a la tesis |
| **Explicabilidad** | El diario de investigación registra qué agente intervino, sobre qué archivo y con qué resultado | `quality_reports/research_journal.md` |
| **Confiabilidad** | Parcialmente comprometida: la generación de referencias produjo un error real (ficha de Huyssen) | Exige la verificación sistemática de citas |
| **Rendición de cuentas** | La responsabilidad sobre autoría, exactitud e interpretación recae en el investigador | Debe declararse de forma expresa |

El punto débil es **confiabilidad**. Es el único de los cinco con un fallo documentado, y se corrige
con el mismo procedimiento ya previsto: ninguna referencia se incorpora sin contraste con la fuente.

El art. 12.1.c encarga al Pleno del CEI elaborar «parámetros e indicadores» de integridad científica
sobre uso y limitaciones de la IA. Esos criterios detallados no existen aún; conviene revisar la
página del CEI antes del depósito.

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
   procesados por un proveedor externo. Esto no es solo una cuestión de palabra dada a los
   informantes: el art. 2.3 del reglamento del CEI remite expresamente al RGPD y a la LO 3/2018, y
   el art. 3.2 reserva al Comité la aprobación de los modelos de consentimiento.
   `[VERIFICAR: contrastar con lo prometido a los informantes en el consentimiento. Si este no
   contempla el tratamiento por terceros, decidir entre (a) restringir el uso de la herramienta al
   material ya anonimizado, o (b) ampliar el consentimiento y someter el nuevo modelo al CEI.]`
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

**Con el tutor, cuanto antes:**

- [ ] **Determinar si la tesis debe someterse ya al CEI** y, en su caso, iniciar el expediente. La
      solicitud la firma el tutor (art. 3.3). Comprobar el calendario de la Sección Primera, que se
      publica en septiembre.
- [ ] **Someter los modelos de consentimiento informado** a aprobación del CEI (art. 3.2), con la
      previsión de tratamiento por terceros ya incorporada.
- [ ] **Fijar el alcance de la tesis** antes de solicitar la evaluación: una modificación sustancial
      posterior obliga a comunicarla al CEI (art. 5.2).

**Antes de publicar el artículo:**

- [ ] **Verificar toda referencia** procedente de `annotated_bibliography.md` contra base de datos
      académica. Es el punto donde el proyecto falla el criterio de *confiabilidad* del art. 12.5.f.
- [ ] **Precisar el origen del término *synousia*** (criterio 2.a de InvestigaUNED). No bloqueante:
      la evidencia documentada sitúa el diagnóstico, el eje memorial y la decisión ontológica en el
      investigador. Basta redactar la frase que lo declare con exactitud.
- [ ] Confirmar si se completó la revisión del autor sobre los cuatro bloques del §4 (20/07/2026).
- [ ] Incorporar la declaración al final del artículo, tras las referencias.

**De fondo:**

- [ ] Vigilar la aprobación definitiva del reglamento del CEI y los «parámetros e indicadores» sobre
      IA que debe elaborar el Pleno (art. 12.1.c).
- [ ] Comprobar si los memos analíticos del vault (`ANA_*`) contienen texto generado; si es así,
      ampliar el apartado «Propósito del uso» con la función de análisis.
- [ ] Convertir el modo «lista de cambios» en comportamiento por defecto del agente `writer`.
- [ ] Actualizar las rutas del vault en `CLAUDE.md` y `fieldwork.md`: apuntan a
      `/Users/sdcarr/Documents/UNED-investigacion`, que ya no existe.
