# YouTube Data Processing Pipeline (PySpark)

Este projeto consiste em um pipeline completo utilizando **PySpark** para processar, analisar e modelar dados relacionados a vídeos e comentários do YouTube. Inclui etapas de leitura, limpeza, transformação, engenharia de atributos e análise estatística.

---

## Tecnologias Utilizadas

- Python 3.11+
- PySpark (Spark MLlib, DataFrame API)
- Google Drive (`gdown` para download de arquivos)
- Pandas (opcional, para comparação)
- Jupyter / Google Colab (ambiente de execução)

---

## Estrutura do Projeto

youtube-pyspark-pipeline
┣ data
┃ ┗ videos.csv
┃ ┗ comentarios.csv
┣ main.py
┣ README.md


---

##  Funcionalidades

-  **Download automático de dados** via `gdown`
-  **Limpeza e tratamento** dos dados
-  **Estatísticas agregadas** por canal, categoria e data
-  **Engenharia de atributos** com transformações em colunas de texto e data
-  **Modelagem com regressão linear** para prever visualizações
-  **Redução de dimensionalidade** com PCA
-  **Normalização de dados** com MinMaxScaler
-  **Avaliação de variância, média, contagem e outliers**

---

## ⚙ Como Executar

1. Clone o repositório:

git clone https://github.com/seu-usuario/youtube-pyspark-pipeline.git
cd youtube-pyspark-pipeline

Instale os requisitos:

pip install pyspark gdown

Execute o pipeline:

python main.py

## Author

Bruno Brehmer Massaneiro


