Projeto de análise exploratória com base em dados de vídeos e canais do YouTube, com foco em entender padrões de visualização, engajamento e desempenho dos conteúdos.

Objetivo
Explorar dados do YouTube para identificar:

Vídeos com maior e menor performance

Correlações entre visualizações, likes, dislikes e comentários

Tendências por tempo de publicação ou categorias

Estratégias de crescimento com base em dados reais

Tecnologias utilizadas:
PySpark • Pandas • Spark SQL • Gdown • Python

Principais etapas:

ETL: Leitura de arquivos CSV e preparação de dados com Pandas e PySpark
EDA: Exploração de métricas como visualizações, likes e comentários para entender padrões e comportamento dos usuários
Otimização: Técnicas de performance com uso inteligente da memória e limitação de colunas para acelerar o processamento

Vídeos com mais engajamento tendem a ter títulos curtos e thumbnails atrativas
Publicações entre determinados horários ou dias geram mais visualizações
Alta correlação entre número de comentários e likes, indicando engajamento real

Como Executar

 Clone o repositório:

git clone https://github.com/BrunoBmassa/Analise-dados-Youtube.git

Instale as dependências:
pip install pandas matplotlib seaborn plotly jupyter

Execute o notebook:
jupyter notebook notebook/analise_youtube.ipynb
