# Uso de IA: normativa aplicable y reglas de trabajo

**Esta regla es vinculante para todos los agentes.** Traduce la normativa de la UNED y las
recomendaciones de la Biblioteca a comportamiento operativo. Documentación de origen en
`master_supporting_docs/normativa_uned/`.

---

## Principio rector

El investigador es el autor. La herramienta asiste, no redacta en su lugar. Ante la duda entre
producir texto y devolver material que el investigador convierta en texto, **siempre lo segundo**.

---

## 1. Modo por defecto del agente `writer`: lista de cambios

Cuando el objetivo sea mejorar texto que ya ha escrito el investigador, **no reescribir el archivo**.
Devolver una tabla:

```
fragmento original | problema | corrección propuesta
```

Ordenada por gravedad. El investigador aplica los cambios. Así el texto final nunca pasa por el
generador y la voz sigue siendo suya.

Solo redactar prosa directamente cuando el investigador lo pida de forma explícita para ese encargo.

## 2. Qué se puede hacer y qué no

**Permitido** (InvestigaUNED 23/07/2026, §1):

- Corrección gramatical, claridad sintáctica, simplificación de frases.
- Esquemas preliminares, reformulación de títulos, coherencia entre secciones.
- Resumir o reformular texto ya escrito por el investigador.
- Buscar, localizar y fichar bibliografía; criticar borradores; estructurar datos.

**No permitido** (§2):

- Redactar secciones teóricas completas, formular hipótesis, interpretar resultados o construir la
  discusión crítica. Es lo que compromete la autoría intelectual.
- Incorporar citas sin verificar.
- Sustituir el análisis crítico del investigador, en especial en diseño metodológico y discusión.

**Zona intermedia que exige aviso explícito:** expandir notas de campo a prosa. El contenido es del
investigador, la formulación no. Si se hace, hay que decirlo en ese momento y registrarlo en el
diario, para que la declaración final pueda describirlo con exactitud.

## 3. Verificación de referencias — obligatoria

Ninguna referencia producida por el agente `librarian` se incorpora al artículo o a la tesis sin
contrastarla con la fuente original. Ya se produjo un error real (una ficha atribuida a Huyssen 2003
*Present Pasts* correspondía a un artículo distinto del mismo autor y año).

Esto responde al criterio de **confiabilidad** del art. 12.5.f del reglamento del CEI, que es el
punto más débil del proyecto.

## 4. Los cinco principios del art. 12.5.f

Todo lo que se produzca debe poder responder a los criterios que el CEI aplicará:

| Principio | Cómo se satisface aquí |
|---|---|
| Supervisión humana | Los críticos puntúan, no editan (ver `agents.md`). Toda decisión editorial es del investigador |
| Transparencia | Declaración de uso de IA en formato AID al final de cada texto publicado |
| Explicabilidad | Registro en `quality_reports/research_journal.md`: agente, fecha, archivo, resultado |
| Confiabilidad | Verificación de referencias (§3) y cotejo de transcripciones con el audio |
| Rendición de cuentas | La responsabilidad sobre autoría, exactitud e interpretación es del investigador |

## 5. Registro en el diario — no opcional

Cada intervención que produzca o modifique texto se anota en `quality_reports/research_journal.md`
indicando qué hizo el agente, sobre qué archivo, y qué decidió el investigador. Ese registro es lo
que sostiene la explicabilidad ante el CEI y lo que permite redactar la declaración con datos reales
en lugar de fórmulas genéricas.

Al anotar, distinguir siempre entre **texto dictado o escrito por el investigador y pulido** y
**texto redactado por el sistema**. Sin esa distinción la declaración final no se puede escribir.

## 6. Materiales de campo y datos personales

Los materiales de campo —transcripciones, notas de observación, fichas de informantes— contienen
datos personales de terceros. Trabajar con ellos implica tratamiento por un proveedor externo.

- Preferir siempre las versiones anonimizadas (`fieldwork/interviews/anonymized/`).
- No copiar nombres reales, contactos ni datos identificables a archivos del repositorio.
- Si un material sin anonimizar es imprescindible para la tarea, avisar al investigador antes de
  procesarlo.
- La transcripción se hace con el modelo local (Whisper), nunca subiendo audio a un servicio externo.

Marco: art. 2.3 del reglamento del CEI, que remite al RGPD y a la LO 3/2018.

## 7. Declaración de uso

Todo texto destinado a publicación o depósito lleva declaración en formato **AID Framework (ACRL)**
—seis apartados: herramienta, propósito, prompts, uso del contenido generado, revisión y edición,
limitaciones y consideraciones éticas— colocada al final, tras las referencias.

En la tesis, además, el uso de IA entra en el capítulo metodológico como cuarta dimensión de la
reflexividad, junto al consentimiento, la anonimización y la posición del investigador en el campo.

Borrador vigente: `quality_reports/declaracion_uso_ia.md`.

## 8. Evitar la dependencia cognitiva

Recomendación del §3 de InvestigaUNED, adoptada como práctica del proyecto:

- Borrador propio antes de consultar.
- La herramienta interviene preferentemente en fase de revisión, no de conceptualización.
- Comparar siempre versión original y sugerida.

En la práctica: el flujo preferente es **dictado del investigador sobre esquema propio**, seguido de
una pasada de limpieza gramatical. Es el que mejor resultado ha dado y el que menos problemas de
autoría plantea.

---

## Pendiente institucional

La tesis debe someterse a evaluación del Comité de Ética de la Investigación (arts. 3.1, 3.2 y 12.5
del reglamento). La solicitud la firma el tutor junto con el estudiante (art. 3.3), y el Comité debe
aprobar los modelos de consentimiento informado (art. 3.2).

**Decisión del investigador (agosto 2026): el asunto se traslada a la tutoría de 2027.** No
replantearlo en cada sesión. Al acercarse esa tutoría, recuperar el guion desde
`quality_reports/declaracion_uso_ia.md` y comprobar si el anteproyecto de reglamento ha sido
aprobado en el BICI.
