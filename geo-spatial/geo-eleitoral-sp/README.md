# Geographic Analysis of São Paulo Voters' Educational Profile (2022)

## About this project

This directory contains a standalone geospatial analysis project focused on the educational profile of São Paulo's electorate in 2022, using public data from Brazil's TSE.

The main workflow is in the notebook `perfil_eleitoral_sp_2022.ipynb`.

## Folder structure

```text
geo-eleitoral-sp/
├── perfil_eleitoral_sp_2022.ipynb
├── requirements.txt
├── README.md
└── data/
    └── SP_Municipios_2024.shp
```

## Prerequisites

- Python 3.8+
- `pip`
- Jupyter Notebook (or JupyterLab)

## How to run (this project only)

### 1) Enter the project folder

```bash
cd geo-eleitoral-sp
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

### 4) Download the TSE CSV

Download the 2022 São Paulo electorate file and save it as:

`data/perfil_eleitor_secao_2022_SP.csv`

Official source:
https://dadosabertos.tse.jus.br/dataset/eleitorado-2022/resource/a83ff021-02e3-45b9-8f9a-a17632af9bb8

### 5) Run the notebook

```bash
jupyter notebook perfil_eleitoral_sp_2022.ipynb
```

## Data used

- `data/perfil_eleitor_secao_2022_SP.csv` (manual download from TSE)
- `data/SP_Municipios_2024.shp` (São Paulo municipal boundaries)

## Expected output

Maps and analyses of the geographic distribution of educational levels across São Paulo municipalities.

## License

This project is licensed under MIT.
