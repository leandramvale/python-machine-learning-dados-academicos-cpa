# python-machine-learning-dados-academicos-cpa
Avaliação Docente (CPA) - Instituição de Ensino Superior. 

Este protótipo foi desenvolvido com o objetivo de sensibilizar gestores acadêmicos e coordenadores de CPA (comissão própria de avaliação) de Instituições do Ensino Superior da importância de ampliar as análises de dados das avaliações realizadas, sejam elas de cunho instituicional, setorizadas ou de docente por unidade curricular, para o campo da inteligência artificial e machine learning, identificando padrões, avaliando e propondo planos de ação mais assertivos.

Portanto, tem-se 3 arquivos de análise de dados, desenvolvidos em python utilizando o Colab (Google) para ilustrar os procedimentos necessários:

##Colab: 01-Aplicação Prática - CPA (Avaliação Docente) - ETL.ipynb

Código fonte que ilustra um processo de Extração / Transformação / Limpeza de dados de um dataset extraído de uma base de dados que contempla o resultado de uma avaliação da instituição realizada por alunos em relação ao desempenho docente por unidade curricular.

PATH = './datasets/'
DATA_PATH = PATH+'CPA-2024-01-DADOS.csv'

Crie uma pasta “datasets” na raiz do colab
Faça upload do arquivo “CPA-2024-01-DADOS.csv” para esta pasta
Ao final você terá o arquivo de dados para a próxima fase (“CPA-2024-01-DADOS-LIMPOS.csv”)


##Colab: 02-Aplicação Prática - CPA (Avaliação Docente) - Gráficos.ipynb

Código fonte que ilustra um processo de geração de alguns gráficos de análises quantitativas e estatísticas acerca dos dados da avaliação.

PATH = './datasets/'
DATA_PATH = PATH+'CPA-2024-01-DADOS-LIMPOS.csv'


Crie uma pasta “datasets” na raiz do colab
Faça upload do arquivo “CPA-2024-01-DADOS-LIMPOS.csv” para esta pasta
Ao final você terá o arquivo de dados para a próxima fase (“CPA-2024-01-DADOS-SCORE.csv”)


##Colab: 03-Aplicação Prática - CPA (Avaliação Docente) - Machine Learning.ipynb

Código fonte que ilustra um processo de análise dos dados utilizando técnicas de machine learning através do algoritmo k-means.

PATH = './datasets/'
DATA_PATH = PATH+'CPA-2024-01-DADOS-SCORE.csv'

Crie uma pasta “datasets” na raiz do colab
Faça upload do arquivo “CPA-2024-01-DADOS-SCORE.csv” para esta pasta
Faça upload das bibliotecas: hopkins; metric; visual_assessment_of_tendency para a raiz do colab.
