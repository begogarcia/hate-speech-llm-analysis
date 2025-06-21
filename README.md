# hate-speech-llm-analysis
Notebook del Trabajo de Fin de Máster sobre detección de discurso de odio en redes sociales usando LLMs.
## 📂 Datos

El dataset de entrenamiento (`hateval_train.csv`) ha sido dividido en 7 partes debido a las limitaciones de tamaño de GitHub:

- `hateval_train_part1.csv`
- `hateval_train_part2.csv`
- ...
- `hateval_train_part7.csv`

Estos archivos corresponden al split `train` del dataset [`hateval_enriched`](https://huggingface.co/datasets/hs-knowledge/hateval_enriched) de Hugging Face.

En el notebook se incluye el código para recomponer estos archivos en un único DataFrame.
