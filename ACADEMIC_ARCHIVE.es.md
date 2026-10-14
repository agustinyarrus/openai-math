<p align="right"><sub><a href="ACADEMIC_ARCHIVE.md">English</a> · <b>Español</b></sub></p>

# Archivo académico e iniciativa de verificación independiente

> **Declaración de propósito académico / Statement of Academic Purpose**
>
> Este repositorio se mantiene estrictamente con fines de **investigación académica, preservación científica y verificación matemática independiente**.
>
> *This repository is maintained strictly for **academic research, scientific preservation, and independent mathematical verification**.*

---

## 1. Motivación: «no descartar nada sin verificarlo»

En la matemática pura, la verificación formal y la demostración automática de teoremas, **los intentos sin verificar, los contraejemplos y los manuscritos retirados tienen un valor científico inmenso**:

1. **Transparencia epistemológica:** entender cómo formulan hipótesis los modelos de razonamiento de última generación, cómo construyen cadenas de lemas y dónde aparecen errores sutiles de lógica o de signo es esencial para el futuro de la matemática asistida por computadora.
2. **Evitar que se pierda conocimiento:** con lanzamientos de IA que se suceden tan rápido, los artículos retractados o modificados corren el riesgo de desaparecer detrás de reemplazos mínimos o de repositorios borrados. Preservar los preprints exactos, el código fuente y las trazas de las demostraciones asegura que ningún trabajo se pierda antes de que la comunidad global pueda evaluarlo de forma independiente.
3. **Verificación abierta y escrutinio de pares:** ni los verificadores formales automáticos (como Lean 4) ni las salidas de modelos propietarios deberían aceptarse como oráculos sin revisión humana por pares y sin replicación independiente.

---

## 2. Manuscritos retirados que se preservan (`withdrawn_manuscripts_restored/`)

Tras la actualización de OpenAI del 7 de octubre de 2026, tres manuscritos fueron retractados formalmente por un error de signo en la geometría de las variedades abelianas de dimensión 8. En lugar de descartar estos materiales, este repositorio archiva los PDF originales sin comprimir, las fuentes LaTeX y las figuras en [`withdrawn_manuscripts_restored/`](withdrawn_manuscripts_restored/), para investigación y análisis comparativo:

* **Algebraicity of Weil classes on split abelian eightfolds** (18 de septiembre de 2026)
  * *PDF original (812 KB) y las 12 secciones LaTeX completas.*
  * *Contexto:* el origen de la discrepancia de signo (`+1` vs `-1`) en la traza de estabilización inversa para el conteo de puntos dobles de cúspide.
* **Algebraicity of Kuga-Satake Correspondences for K3 Surfaces** (3 de octubre de 2026)
  * *PDF original (720 KB), figuras y el código fuente completo del manuscrito.*
  * *Contexto:* un artículo dependiente, cuyo lema de cancelación se apoyaba en la construcción de dimensión 8.
* **The rational Hodge conjecture for products of K3 surfaces** (4 de octubre de 2026)
  * *PDF original completo (639 KB) y 13 capítulos LaTeX (de antes de que en el repositorio original se lo reemplazara por un archivo mínimo de 3 KB).*

---

## 3. Integridad académica y aviso sobre citas

* Toda la investigación original, las arquitecturas de los modelos y las demostraciones fueron producidas por OpenAI y sus respectivos autores.
* Este repositorio funciona como un espejo de archivo sin fines comerciales, para ayudar a investigadores, matemáticos y lógicos de todo el mundo a evaluar la matemática generada por IA.
* Si encontrás problemas, reparaciones de demostraciones o contraejemplos en algún manuscrito, aportá documentación o verificaciones formales en Lean 4.

<!-- i18n source=ACADEMIC_ARCHIVE.md sha256=a2cb99d0edcc -->
