# Análise de Letras das Músicas do TOP Brasil Spotify

Este projeto realiza análises quantitativas e qualitativas sobre o conteúdo das letras das músicas da playlist TOP Brasil do Spotify.

## Objetivos
- Realizar análises de texto, como contagem de palavras, palavras únicas, frequência de termos, análise de sentimento e repetição.
- Visualizar os resultados em gráficos interativos e estáticos.

## Estrutura do Projeto
```
Analise_de_Letras_TOP_Brasil_Spotify/
├── top_brasil_spotify.csv    # Arquivo com músicas, artistas e letras
├── Analise_de_Letras_TOP_Brasil_Spotify.ipynb  # Notebook de análise exploratória
└── README.md
```

## Como executar
### 1. Instale as dependências
Recomenda-se o uso de um ambiente virtual.

```bash
pip install pandas nltk matplotlib seaborn plotly textblob notebook
```

### 2. Execute o notebook de análise
Abra o arquivo `Analise_de_Letras_TOP_Brasil_Spotify.ipynb` no Jupyter Notebook ou VS Code e execute as células para gerar as análises e gráficos.

## Principais análises realizadas
- Contagem total de palavras e palavras únicas por música
- Frequência das palavras mais comuns
- Análise de sentimento das letras
- Razão de repetição de palavras
- Visualizações em matplotlib, seaborn e plotly

## Autor
Mauro Santos

## Licença
MIT
