# Análise de Letras das Músicas do TOP Brasil Spotify

## Sobre este projeto

Este diretório contém um projeto independente de análise de texto aplicado às letras das músicas da playlist TOP Brasil do Spotify.

O fluxo principal está no notebook `spotify_br_nlp.ipynb`.

## Estrutura da pasta

```text
lyrics-sentiment-analysis/
├── spotify_br_nlp.ipynb
├── requirements.txt
└── README.md
```

## Pré-requisitos

- Python 3.8+
- `pip`
- Jupyter Notebook (ou JupyterLab)

## Como executar (apenas este projeto)

### 1) Entre na pasta do projeto

```bash
cd lyrics-sentiment-analysis
```

### 2) Crie e ative um ambiente virtual (recomendado)

```bash
python -m venv .venv
source .venv/bin/activate
```

### 3) Instale as dependências

```bash
pip install -r requirements.txt
```

### 4) Execute o notebook

```bash
jupyter notebook spotify_br_nlp.ipynb
```

## Principais análises realizadas

- Contagem de palavras totais e palavras únicas por música
- Frequência de termos recorrentes
- Análise de sentimento das letras
- Medidas de repetição textual
- Visualizações com Matplotlib, Seaborn e Plotly

## Licença

MIT
