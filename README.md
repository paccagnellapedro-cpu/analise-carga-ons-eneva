# Análise Sazonal de Carga Verificada do SIN (2021-2023)

Este projeto realiza a extração automatizada e análise estatística dos dados de carga global do SIN via API do ONS.

## Funcionalidades
- Extração mensal (paginação) para evitar limites de API.
- Classificação sazonal (Hemisfério Sul).
- Cálculo de Médias, Extremos e Delta de Crescimento.
- Geração de Excel multi-abas e logs técnicos.

## Principais Insights
- Identificação de anomalia térmica na Primavera de 2023 (impacto do El Niño).
- Crescimento progressivo da carga base entre 2021 e 2023.

## Execução
1. Instale as dependências: `pip install -r requirements.txt`
2. Execute: `python analise_eneva.py`