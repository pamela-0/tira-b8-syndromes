# Síndromes .b8 / .b8 Syndromes

Tira pública de auditoría (formato "TIRA" del Protocolo de Agente Finito, v28 · R1–R232) sobre datos reales de corrección de errores cuánticos.

- **[Versión en español](index.html)**
- **[English version](en.html)**

## Qué es esto

Un análisis independiente de un experimento real de un qubit lógico de superficie (d=3, parche `d3_at_q4_5`, chip de 105 qubits) del dataset publicado junto al paper *"Quantum error correction below the surface code threshold"* (Google Quantum AI, Nature 2024).

Todo número en la tira —p_L, integridad del ZIP (bytes/md5), split train/test, cotas de concentración (Hoeffding/Berry-Esseen/McDiarmid), moving block bootstrap, divergencia KL, entropía binaria— fue recalculado directamente sobre los archivos `.b8` reales y verificado contra las APIs públicas de Zenodo/DataCite/Crossref/Semantic Scholar, no copiado de ninguna fuente secundaria.

## Atribución y licencia

**Análisis independiente, no afiliado ni respaldado por Google Quantum AI.**

- Dataset: [10.5281/zenodo.13273331](https://doi.org/10.5281/zenodo.13273331) — Google Quantum AI, CC-BY-4.0
- Paper: [10.1038/s41586-024-08449-y](https://doi.org/10.1038/s41586-024-08449-y) — Nature
- Este repositorio no redistribuye el ZIP del dataset; solo reporta estadísticas derivadas.

Este contenido se publica bajo [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), la misma licencia del dataset fuente. Ver [LICENSE](LICENSE).

## Código fuente del análisis

El paquete Python que genera y verifica estos números (con tests reales contra los `.b8` y las APIs) vive en un proyecto separado (`agente-finito`), no incluido en este repositorio.
