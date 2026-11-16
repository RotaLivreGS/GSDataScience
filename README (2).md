# Rota Livre – Data Science & Statistical Computing

Global Solution 2026.2 · CitizenTech · Engenharia de Software · FIAP

## Ficha da CitizenTech

| | |
|---|---|
| **Nome da CitizenTech** | Rota Livre |
| **Cidade e bairro** | São Paulo – Bela Vista (entorno da Av. Paulista, 1106) |
| **Cidadão beneficiado** | Cadeirantes, idosos, pessoas com mobilidade reduzida e quem anda com carrinho de bebê |
| **Problema, em uma frase** | Os apps de mapa mostram o caminho mais rápido, mas não avisam se tem degrau, buraco ou falta de rampa no caminho. |
| **Como funciona** | A pessoa coloca o destino e o seu perfil de mobilidade, e o app mostra uma rota que desvia das barreiras e prioriza rampas. As barreiras são relatadas pelos usuários e validadas por uma equipe. |
| **Link do repositório** | https://github.com/RotaLivreGS/GSDataScience |
| **Indicador de impacto** | Barreiras relatadas e validadas; quanto da rota sugerida fica livre de barreiras; atendimentos na Central |
| **ODS conectados** | ODS 11 (metas 11.2 e 11.7), ODS 10 (meta 10.2) e ODS 9 (meta 9.c) |

## Sobre esta entrega

Análise descritiva das reclamações de **calçada e acessibilidade** feitas à Prefeitura de São Paulo pelo SP156, entre abril e setembro de 2026. O objetivo é entender a realidade de quem tem mobilidade reduzida e apoiar o Rota Livre.

**Fonte:** Prefeitura de São Paulo, Portal de Dados Abertos, *Dados do SP156 – 2º e 3º trimestres de 2026*. Mantivemos só os serviços:

- Calçada pública - solicitar manutenção
- Acessibilidade - solicitar avaliação de obstáculo na calçada
- Calçada particular - denunciar calçada danificada ou inexistente
- Guias para travessia de pedestres - Solicitar rebaixamento
- Sugerir construção de calçadas em áreas públicas e praças

## Arquivos

| Arquivo | Conteúdo |
|---|---|
| `GS_DataScience_RotaLivre.ipynb` | Notebook executado: preparação, análise descritiva, gráficos e conclusões |
| `sp156_calcadas_acessibilidade_2026.csv` | Base de dados usada (8.361 solicitações) |

## Como executar

1. Abra o `GS_DataScience_RotaLivre.ipynb` no **Google Colab**.
2. No menu lateral **Arquivos**, faça o upload do `sp156_calcadas_acessibilidade_2026.csv` (ele fica na pasta `/content`).
3. Clique em **Ambiente de execução → Executar tudo**.

Bibliotecas: `pandas`, `numpy` e `matplotlib` (já vêm instaladas no Colab).

## Integrantes

- Igor Davi Avelar Rosa Cesário – RM568163
- Patrick Castro Quintana – RM575906
- Rafael Menezes Viana – RM576753
