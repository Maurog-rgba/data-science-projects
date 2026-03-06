# Analysis of Spotify Top Brasil Song Lyrics

## About this project

This directory contains a standalone text analysis project focused on song lyrics from Spotify's Top Brasil playlist.

The main workflow is in the notebook `spotify_br_nlp.ipynb`.

## Folder structure

```text
lyrics-sentiment-analysis/
├── spotify_br_nlp.ipynb
├── requirements.txt
└── README.md
```

## Prerequisites

- Python 3.8+
- `pip`
- Jupyter Notebook (or JupyterLab)

## How to run (this project only)

### 1) Enter the project folder

```bash
cd lyrics-sentiment-analysis
```

### 2) Create and activate a virtual environment (recommended)

```bash
python -m venv .venv
source .venv/bin/activate
```

### 3) Install dependencies

```bash
pip install -r requirements.txt
```

### 4) Run the notebook

```bash
jupyter notebook spotify_br_nlp.ipynb
```

## Main analyses included

- Total and unique word counts per song
- Frequency of recurring terms
- Lyrics sentiment analysis
- Text repetition metrics
- Visualizations with Matplotlib, Seaborn, and Plotly

## License

MIT
