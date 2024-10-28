# consumidorgov
Projeto de Análise de Reclamações
Este projeto, desenvolvido em Python com Streamlit, Plotly e Selenium, permite realizar a análise de dados de reclamações de clientes, gerando visualizações gráficas interativas e intuitivas. Com recursos para filtrar dados por datas e visualizar frequências e classificações, o projeto é útil para equipes de atendimento ao cliente e qualidade que buscam insights sobre problemas recorrentes e a satisfação dos consumidores.

Funcionalidades
Análise de Frequência das Reclamações:

Utiliza gráficos de pizza para ilustrar a distribuição das avaliações das reclamações.
Comparação de Problemas e Notas:

Exibe médias das notas dos consumidores por grupos de problemas em gráficos de barras.
Satisfação por Tipo de Compra:

Analisa a satisfação dos clientes com base no modo de aquisição do produto/serviço, exibindo a nota média de satisfação.
Estrutura do Código
Importações e Configuração de Estilo
O projeto utiliza as seguintes bibliotecas:

streamlit: Interface de usuário e interatividade.
plotly: Visualizações gráficas.
selenium: Automatização de navegação para coleta de dados.
re: Expressões regulares para extração e manipulação de dados.
Principais Funções e Componentes
Filtragem de Dados: O filtro por data permite ajustar o intervalo de análise.
Visualizações Gráficas: Usando gráficos de barras e pizza, facilita a interpretação de métricas como frequência de reclamações e média das notas.
Interatividade com Gráficos: Os gráficos exibem informações adicionais ao passar o cursor, como o número de reclamações e notas médias.
Implementação
O arquivo principal (kk.py) inclui:

Configuração de Layout: Define uma página de layout amplo com CSS customizado.
Input de Filtros: Permite ao usuário ajustar o intervalo de datas.
Gráficos: Utiliza Plotly para criar gráficos de barras e pizza com cores específicas, oferecendo uma visualização intuitiva.
Estrutura do Projeto
kk.py: Código principal do Streamlit com visualizações e filtragem.
requirements.txt: Arquivo de dependências para o ambiente virtual.
Executando o Projeto
Requisitos
Docker ou Python 3.8+
Dependências: Listadas em requirements.txt
