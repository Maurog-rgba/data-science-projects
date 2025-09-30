# Análise Geográfica do Perfil Educacional dos Eleitores de São Paulo (2022)

![Python](https://img.shields.io/badge/python-v3.8+-blue.svg)
![Jupyter](https://img.shields.io/badge/jupyter-notebook-orange.svg)
![GeoPandas](https://img.shields.io/badge/geopandas-v1.1.1-green.svg)
![Pandas](https://img.shields.io/badge/pandas-v2.3.3-red.svg)

## 📋 Descrição do Projeto

Este projeto realiza uma análise detalhada do perfil educacional dos eleitores do estado de São Paulo utilizando dados públicos do Tribunal Superior Eleitoral (TSE) referentes ao ano de 2022. O objetivo é investigar a distribuição geográfica dos diferentes níveis de escolaridade por todo o estado através de visualizações geoespaciais.

### 🎯 Objetivos

- Analisar a distribuição geográfica dos níveis educacionais dos eleitores paulistas
- Criar mapas coropléticos para visualização dos dados por município
- Processar eficientemente um grande volume de dados (5GB)
- Demonstrar técnicas de análise geoespacial com Python

## 🏗️ Estrutura do Projeto

```
Data-Science-Projects/
├── Análise_do_Perfil_Educacional_dos_Eleitores_de_SP_(2022).ipynb
├── requirements.txt
├── data/
│   └── SP_Municipios_2024.shp
└── README.md
```

## 📊 Dados Utilizados

### Dados Eleitorais do TSE

- **Fonte**: [Repositório de Dados Eleitorais do TSE - Eleitorado 2022](https://dadosabertos.tse.jus.br/dataset/eleitorado-2022/resource/a83ff021-02e3-45b9-8f9a-a17632af9bb8)
- **Arquivo**: `perfil_eleitor_secao_2022_SP.csv`
- **Tamanho**: ~5GB
- **Descrição**: Dados detalhados do perfil dos eleitores por seção eleitoral

### Como Baixar os Dados

1. Acesse o link: https://dadosabertos.tse.jus.br/dataset/eleitorado-2022/resource/a83ff021-02e3-45b9-8f9a-a17632af9bb8
2. Baixe o arquivo CSV do eleitorado de 2022
3. Coloque o arquivo na pasta `data/` com o nome `perfil_eleitor_secao_2022_SP.csv`

### Dados Geoespaciais

- **Arquivo**: `SP_Municipios_2024.shp` (incluído no repositório)
- **Descrição**: Shapefile com os limites dos municípios de São Paulo

## 🛠️ Tecnologias Utilizadas

- **Python 3.8+**
- **Jupyter Notebook**
- **Pandas** - Manipulação e análise de dados
- **GeoPandas** - Análise de dados geoespaciais
- **Matplotlib** - Visualização de dados
- **Shapely** - Operações geométricas

## 🚀 Como Executar

### 1. Pré-requisitos

```bash
# Clone o repositório
git clone https://github.com/Maurog-rgba/Data-Science-Projects.git
cd Data-Science-Projects
```

### 2. Instalação das Dependências

```bash
# Instalar as dependências
pip install -r requirements.txt
```

### 3. Download dos Dados

Baixe o arquivo CSV dos dados eleitorais:

- Acesse: https://dadosabertos.tse.jus.br/dataset/eleitorado-2022/resource/a83ff021-02e3-45b9-8f9a-a17632af9bb8
- Baixe o arquivo e salve como `data/perfil_eleitor_secao_2022_SP.csv`

### 4. Executar o Notebook

```bash
# Iniciar Jupyter Notebook
jupyter notebook

# Abrir o arquivo:
# Análise_do_Perfil_Educacional_dos_Eleitores_de_SP_(2022).ipynb
```

## 📈 Metodologia

### 1. **Processamento Eficiente de Big Data**

- Leitura do arquivo de 5GB em chunks de 500.000 registros
- Seleção apenas das colunas necessárias para análise

### 2. **Agregação de Dados**

- Agrupamento dos dados por município
- Cálculo de proporções de escolaridade por região
- Transformação dos dados para análise geoespacial

### 3. **Visualização Geográfica**

- Criação de mapas coropléticos estáticos
- Análise da distribuição espacial dos níveis educacionais
- Identificação de padrões regionais

## 📊 Principais Análises

O notebook inclui as seguintes análises:

1. **Carregamento e Processamento dos Dados**

   - Técnicas de otimização para big data
   - Filtragem e limpeza dos dados
2. **Agregação por Município**

   - Agrupamento dos dados eleitorais
   - Cálculo de estatísticas educacionais
3. **Visualização Geoespacial**

   - Mapas coropléticos por nível de escolaridade
   - Análise de padrões geográficos

## 🔍 Resultados Esperados

- Mapas que mostram a distribuição geográfica dos níveis educacionais
- Identificação de regiões com maior/menor escolaridade
- Insights sobre padrões socioeconômicos regionais
- Visualizações claras e interpretáveis dos dados

## 📝 Estrutura do Notebook

1. **Introdução** - Contexto e objetivos do projeto
2. **Configuração do Ambiente** - Setup das bibliotecas
3. **Carregamento e Processamento** - Técnicas de big data
4. **Agregação e Transformação** - Preparação dos dados
5. **Visualização Geográfica** - Criação dos mapas
6. **Conclusão** - Insights e próximos passos

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## 👨‍💻 Autor

**Mauro Santos**

- GitHub: [@Maurog-rgba](https://github.com/Maurog-rgba)

## 🔗 Links Úteis

- [TSE - Dados Abertos](https://dadosabertos.tse.jus.br/)
- [GeoPandas Documentation](https://geopandas.org/)
- [Matplotlib Documentation](https://matplotlib.org/)
- [Pandas Documentation](https://pandas.pydata.org/)
