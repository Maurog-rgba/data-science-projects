# Análise Geográfica do Perfil Educacional dos Eleitores de São Paulo (2022)

## Sobre este projeto

Este diretório contém um projeto independente de análise geoespacial com foco no perfil educacional do eleitorado de São Paulo em 2022, usando dados públicos do TSE.

O fluxo principal está no notebook `perfil_eleitoral_sp_2022.ipynb`.

## Estrutura da pasta

```text
geo-eleitoral-sp/
├── perfil_eleitoral_sp_2022.ipynb
├── requirements.txt
├── README.md
└── data/
    └── SP_Municipios_2024.shp
```

## Pré-requisitos

- Python 3.8+
- `pip`
- Jupyter Notebook (ou JupyterLab)

## Como executar (apenas este projeto)

### 1) Entre na pasta do projeto

```bash
cd geo-eleitoral-sp
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

### 4) Baixe o CSV do TSE

Baixe o arquivo de eleitorado 2022 de SP e salve em:

`data/perfil_eleitor_secao_2022_SP.csv`

Fonte oficial:
https://dadosabertos.tse.jus.br/dataset/eleitorado-2022/resource/a83ff021-02e3-45b9-8f9a-a17632af9bb8

### 5) Execute o notebook

```bash
jupyter notebook perfil_eleitoral_sp_2022.ipynb
```

## Dados utilizados

- `data/perfil_eleitor_secao_2022_SP.csv` (download manual do TSE)
- `data/SP_Municipios_2024.shp` (limites municipais de SP)

## Resultado esperado

Geração de mapas e análises da distribuição geográfica dos níveis de escolaridade do eleitorado paulista por município.

## Licença

Este projeto está sob a licença MIT.
