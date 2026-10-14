<p align="right"><sub><a href="README.md">English</a> · <b>Español</b></sub></p>

# OpenAI Math: archivo académico y espejo de verificación

> [!NOTE]
> **Aviso de preservación y verificación académica / Academic Preservation & Verification Notice**
> Este espejo está curado para la **investigación académica, la reproducibilidad y la verificación matemática independiente**. Preserva los más de 749 manuscritos, los artefactos formales de Lean 4 y las trazas de razonamiento, sin descartar los intentos sin verificar ni los artículos retirados.
> 🔍 *La fundamentación científica completa está en [ACADEMIC_ARCHIVE.es.md](ACADEMIC_ARCHIVE.es.md).*
> 📁 *Los 3 artículos originales retirados, con sus fuentes LaTeX completas, están archivados en [`withdrawn_manuscripts_restored/`](withdrawn_manuscripts_restored/).*

---

# Léame

Este repositorio contiene manuscritos matemáticos y artefactos de demostración complementarios producidos por un modelo interno de OpenAI.

Como parte del desarrollo de modelos, evaluamos nuestros modelos con problemas de investigación abiertos. Ampliamos estas evaluaciones cuando el rendimiento en nuestras evaluaciones matemáticas existentes llegó a la saturación. Algunos resultados se apoyan en resultados anteriores producidos por los modelos.

Esta colección incluye resultados en distintas etapas de verificación. No todos vienen acompañados de formalizaciones en Lean. Vamos a seguir actualizando este repositorio con formalizaciones en Lean a medida que las obtengamos.

Algunos de los resultados no formalizados podrían tener problemas. Nos vamos a esforzar por corregir rápido cualquier problema de ese tipo.
También estamos explorando repositorios alojados por la comunidad para estos materiales.

## Cómo recorrer la colección

El catálogo actual contiene 719 manuscritos organizados en 372 familias. Una familia agrupa artículos relacionados, que pueden incluir un resultado principal, argumentos complementarios, consecuencias o demostraciones alternativas. Cada familia está clasificada por disciplina matemática.

- El [panorama general](overview.pdf) es el punto de partida: describe cada una de las familias.
- El [mapa de manuscritos](CONTENTS.md) sirve para encontrar cada artículo y sus materiales complementarios.
- El directorio [`preprints/`](preprints/) contiene los PDF, los archivos fuente y, para cada manuscrito, sus instrucciones de cita y de compilación.
- La [biblioteca de Lean](lean/README.md) y el [catálogo de formalizaciones](lean/formalization.yaml) describen las demostraciones formales disponibles, los artículos asociados y las configuraciones de verificación. Las [instrucciones del Comparator](lean/ComparatorChallenges/README.md) agregan más formas de verificar. El repositorio tiene formalizados ~42 % de los resultados principales.
- Las actualizaciones del repositorio se describen en el [historial](history.md).

### Resúmenes del razonamiento

También publicamos resúmenes abreviados del razonamiento del modelo, que cubren los siguientes resultados:

| Familia | Tema |
|---|---|
| 007 | [Correlaciones ordinarias de dos puntos de funciones multiplicativas](reasoning_traces/ordinary-two-point-correlations.pdf) |
| 017 | [El exponente de irracionalidad de π](reasoning_traces/irrationality-exponent-of-pi.pdf) |
| 087 | [Las conjeturas de Mahler simétrica y general](reasoning_traces/symmetric-and-general-mahler-conjectures.pdf) |
| 102 | [NP-dificultad ordinaria en el umbral semidefinido básico](reasoning_traces/basic-semidefinite-threshold-np-hardness.pdf) |
| 159 | [Cotas cuasipolinomiales para progresiones aritméticas](reasoning_traces/quasipolynomial-arithmetic-progressions.pdf) |
| 197 | [La conjetura de finitud directa de Kaplansky en característica dos](reasoning_traces/kaplansky-direct-finiteness-characteristic-two.pdf) |
| 221 | [La fórmula de Mézard–Parisi para vidrios de espín diluidos](reasoning_traces/mezard-parisi-formula.pdf) |
| 271 | [Magnetización espontánea en el ferromagneto cuántico de Heisenberg](reasoning_traces/spontaneous-magnetization-quantum-heisenberg-ferromagnet.pdf) |
| 287 | [El isomorfismo de los factores de grupos libres](reasoning_traces/free-group-factor-isomorphism.pdf) |
| 362 | [El sistema relativista de Vlasov–Maxwell en tres dimensiones](reasoning_traces/relativistic-vlasov-maxwell.pdf) |


## Cómo se produjeron los resultados

La gran mayoría de los resultados se obtuvo con el mismo procedimiento, usando un modelo interno de OpenAI que no fue publicado. En promedio, cada resultado usó tres horas de cómputo de razonamiento de ChatGPT Pro con ese modelo. A lo largo de la evaluación se le plantearon al modelo unos 4000 problemas. Agrupar lo producido en familias de resultados y manuscritos, y exigir un nivel de relevancia adecuado, llevó al catálogo descrito más arriba.

Las excepciones a este procedimiento fijo incluyen el trabajo sobre una región libre de ceros para la función zeta de Riemann y la demostración de la conjetura de Hodge para variedades abelianas CM. Además, la redacción sobre la región libre de ceros Re(s) > 11/12 para la función zeta de Riemann fue editada por personas para hacerla más legible.


## Versiones y citas

Vamos a preservar el historial público de publicaciones de esta colección. Las correcciones y revisiones van a quedar registradas como versiones nuevas, y las versiones publicadas antes van a seguir accesibles.

Para citar un manuscrito en particular, se usa el bloque BibTeX de su directorio.

<!-- i18n source=README.md sha256=f610ea66ce94 -->
