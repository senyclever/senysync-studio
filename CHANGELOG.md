# Changelog · SenySync Studio

Todos los cambios notables de este proyecto se documentan aquí.
All notable changes to this project are documented here.

## [1] · Build 1

### Español

**Núcleo**
- Reloj dual BPM / CSV de Sonic Visualiser con rejilla irregular, span automático, offset propio y jerarquía configurable.
- Vídeo importado como reloj maestro, con gestión de medios y avisos de coexistencia.
- Timeline con bandas dinámicas, zoom suavizado, pinch, pulsación larga, doble tap, vibración al snap y seguir aguja.
- Guías visuales en ambos bordes al arrastrar una barra completa.
- Loop de 6 estados anclado al compás, snap cíclico y candado D.
- Partición con techo D, reindexado atómico, partición en frontera musical y reordenación en dos modos.
- Firma de autor en la cabecera del Timeline y barra de transporte móvil sin tiempo duplicado ni recortado.

**Creación**
- Contratos LEAN y RICH desde un único compilador, con paridad garantizada entre compilador y esqueletos.
- LEX como fuente única de cláusulas canónicas y precedencia escrita en prosa dentro de readFirst.
- Motivo M0-M11 con leyenda por proyecto y taxonomía de planos en 6 categorías.
- Referencias de personaje con roles, matriz de continuidad y tres modos de almacenamiento.
- Centinelas, checklist de 5 estados y notas por clip.

**Imagen**
- Texto v2 con una única función de layout para canvas y SVG: paridad exacta preview / PNG / SVG.
- Motor de movimiento por capas con parallax, pulso al reloj, partículas y glow.
- Blindaje nivel 2 de solo lectura y no bloqueante, con catálogo de avisos y remedio.
- Escenas base y portadas en espacio normalizado de 480.

**Salida**
- MP4 H.264 offline con WebCodecs y multiplexor MP4 nativo, con fallback Annex-B a AVCC.
- WebM en tiempo real con audio y secuencia PNG en ZIP por lotes.
- SRT / VTT / ASS, marcadores en 7 formatos, informe TXT y manual TXT / PDF bilingüe.
- Capítulos de YouTube válidos con formato de horas y mínimo de 10 segundos.

**Ayuda y datos**
- Buscador transversal, glosario de 26 términos, 9 recetas y ruta guiada de 8 pasos.
- Fichas de ayuda con índice interno y avisos accionables con salto al control.
- Registros locales de uso y de lote: opcionales, separados del proyecto, exportables y purgables.
- Cola de importación explícita y tolerancia a prólogo XML y DOCTYPE con subconjunto interno.
- Autoguardado con marca de sucio y respaldo que espera la hidratación de IndexedDB.
- Diálogos accesibles con rol, etiqueta bilingüe y trampa de foco.
- Manual completo con índice rápido y cobertura de todas las funciones.
- 153 pruebas internas.

### English

**Core** — dual BPM / CSV clock, imported video as master clock, professional timeline with dual edge guides, 6-state bar-anchored loop, ceiling-D partition with atomic reindex, author credit in the Timeline header and a mobile transport bar without duplicated or clipped time.

**Creation** — LEAN / RICH contracts from a single compiler with skeleton parity, LEX as the single source of canonical clauses, prose precedence, motif M0-M11, 6-category shot taxonomy, character references, sentinels and 5-stage checklist.

**Image** — Text v2 with one layout function for canvas and SVG, layered motion engine, read-only non-blocking armor level 2, base scenes in normalized 480 space.

**Output** — offline H.264 MP4 with a native muxer, realtime WebM with audio, batched PNG in ZIP, SRT / VTT / ASS, 7 marker formats, bilingual report and manual, valid YouTube chapters.

**Help and data** — cross-search, 26-term glossary, 9 recipes, 8-step guided route, indexed help cards, actionable warnings, optional local ledgers, explicit import queue with XML prolog and DOCTYPE tolerance, dirty-tracked autosave, hydration-aware backup, accessible dialogs, complete manual with quick index, 153 internal tests.