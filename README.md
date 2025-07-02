# EBAC-Natalidade-RO-Desvendada
Mod06 Tarefa 3

## 👶📊 Módulo 6 Tarefa 3: Análise de Dados de Nascidos Vivos

Este projeto contém uma análise de dados de nascidos vivos 🤱 utilizando o dataset `sinasc_RO_2019.csv` do DataSUS. O objetivo é explorar a relação entre diversas variáveis, como APGAR5, sexo, tempo de gestação e peso do bebê. ⚖️

### Tabela de Conteúdo

  - [Descrição do Projeto]📄
  - [Fonte dos Dados] 💾
  - [Tecnologias Utilizadas] 🛠️
  - [Etapas da Análise] 📈
  - [Como Executar] 🚀

### Descrição do Projeto

Este Jupyter Notebook realiza uma série de análises exploratórias sobre dados de nascidos vivos. As principais tarefas incluem:

1.  Carregamento e visualização inicial do dataset. 🔍
2.  Categorização da variável `APGAR5` em grupos como 'asfixia grave' (0-3), 'asfixia moderada' (4-5), 'asfixia leve' (6-7) e 'normal' (8-10). ✅
3.  Comparação da distribuição de `APGAR5` por sexo para diferentes grupos de tempo de gestação. ♂️♀️
4.  Criação de tabelas cruzadas (`crosstab`) entre `APGAR5` e `GESTACAO`. ✖️
5.  Cálculo de percentuais de linha para a tabela cruzada, mostrando a distribuição de `APGAR5` para cada classe de `GESTACAO`. 💯
6.  Análise gráfica da relação entre `APGAR5` e tempo de gestação, com foco na classificação de partos prematuros. ⏳
7.  Investigação da relação entre `APGAR5` e o peso do bebê através de um gráfico de box plot. 📦

### Fonte dos Dados

Os dados utilizados neste projeto são provenientes do sistema de nascidos vivos (SINASC) do DataSUS, contidos no arquivo `sinasc_RO_2019.csv`. O dicionário de dados detalhado pode ser encontrado no arquivo `Estrutura_SINASC_para_CD.pdf` (não fornecido neste repositório). 📖

### Tecnologias Utilizadas

  * Python 🐍
  * Pandas 🐼
  * Matplotlib 📊
  * Seaborn  seaborn 📈
  * Jupyter Notebook 📓

### Etapas da Análise

O notebook está estruturado nas seguintes seções:

1.  **Carregamento dos Dados**: O arquivo `sinasc_RO_2019.csv` é carregado em um DataFrame do Pandas. 📥
2.  **Categorização de APGAR5**: A variável `APGAR5` é categorizada em quatro grupos com base em intervalos específicos: 'asfixia grave', 'asfixia moderada', 'asfixia leve' e 'normal'. 🏷️
3.  **Gráfico de Distribuição de APGAR5 por Sexo e Gestação**: Um gráfico de barras é gerado para comparar a distribuição de `APGAR5_CATEGORIA` por `SEXO` para todos os tempos de gestação. 📊
4.  **Tabela Cruzada APGAR5 x GESTACAO**: É criada uma tabela cruzada mostrando a frequência de `APGAR5` para cada `GESTACAO`. ➕
5.  **Percentuais de Linha da Tabela Cruzada**: Os percentuais de linha são calculados a partir da tabela cruzada anterior, indicando a distribuição de `APGAR5` dentro de cada categoria de `GESTACAO`. 📏
6.  **Gráfico de Barras e Conclusão sobre Parto Prematuro**: Um gráfico de barras empilhadas é gerado a partir da tabela cruzada para visualizar a distribuição de `APGAR5` por tempo de gestação, com uma discussão sobre a afirmação médica de parto prematuro (\<37 semanas). 👶🗓️
7.  **Relação entre APGAR5 e Peso do Bebê**: Um box plot é utilizado para explorar a distribuição do peso dos bebês (`PESO`) em relação às diferentes pontuações de `APGAR5`. ⚖️📈

### Como Executar

Para executar este projeto, siga os passos abaixo:

1.  **Clone o repositório** (assumindo que você o enviará para o GitHub):
    ```bash
    git clone https://github.com/seu-usuario/seu-repositorio.git
    cd seu-repositorio
    ```
2.  **Certifique-se de ter o arquivo de dados**: O arquivo `SINASC_RO_2019.csv` deve estar na mesma pasta que o notebook `mod06 Tarefa 3.ipynb`. 📁
3.  **Instale as dependências**:
    ```bash
    pip install pandas matplotlib seaborn jupyter
    ```
4.  **Abra o Jupyter Notebook**:
    ```bash
    jupyter notebook
    ```
5.  No navegador, navegue até `mod06 Tarefa 3.ipynb` e abra-o. Você pode então executar as células sequencialmente para reproduzir a análise. ▶️

