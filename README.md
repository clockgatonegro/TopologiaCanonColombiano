# TopologiaCanonColombiano

Código fuente y análisis de redes (PLN) para la investigación "Topología algorítmica del canon novelístico colombiano" | Python scripts and datasets for the paper "Topología algorítmica del canon novelístico colombiano" (NLP & Network Analysis of 82 novels).

> **Dussán Gómez, C. (2026).** *"Topología algorítmica del canon novelístico colombiano"*. Revista de Humanidades Digitales. 

Este repositorio contiene el pipeline completo utilizado para realizar el análisis estilométrico y la construcción de la red léxica de la literatura colombiana.

## 📂 Contenido del Repositorio

- `canon_colombiano.ipynb` — Pipeline completo de análisis (Jupyter Notebook).
- `resultados_spacy.csv` — Métricas estilométricas extraídas con spaCy.
- `resultados_stanza.csv` — Métricas estilométricas extraídas con Stanza.
- `Rayos_X_Red_Canon.csv` — Matriz de similitud y palabras puente entre obras.
- `Red_Canon_Colombiano.gexf` — Red exportada y lista para su visualización espacial en Gephi.

## ⚙️ Requisitos e Instalación

Para reproducir los resultados o ejecutar el cuaderno, clona este repositorio e instala las dependencias necesarias:

```bash
pip install -r requirements.txt
```

## 📚 Nota sobre el Corpus (Derechos de Autor)

Por motivos de derechos de autor vigentes, no se incluyen los textos originales de las novelas en este repositorio.

El corpus bruto utilizado en la investigación comprende **82 novelas** en formato `.txt`, sumando un total de **6.035.070 tokens**. Sin embargo, los archivos `.csv` y `.gexf` proporcionados en este repositorio contienen todos los datos procesados necesarios para reproducir las gráficas, métricas y redes del artículo sin necesidad de poseer los textos originales.

## 📜 Licencia y Citación

Este proyecto utiliza una doble licencia para adaptarse a los estándares académicos de ciencia abierta:

* **Código fuente (`.ipynb`):** Distribuido bajo la [Licencia MIT](LICENSE). Eres libre de utilizar, modificar y distribuir el código para tus propias investigaciones.
* **Datos y Resultados (`.csv`, `.gexf`):** Distribuidos bajo la licencia [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). 

**Citación:**
Si utilizas el código o los datos de este repositorio en tu investigación, te pedimos que por favor cites el artículo original:
> Dussán Gómez, C. (2026). "Topología algorítmica del canon novelístico colombiano". Revista de Humanidades Digitales.
