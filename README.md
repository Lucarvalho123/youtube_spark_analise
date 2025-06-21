# Análise de Vídeos do YouTube com PySpark

Projeto desenvolvido para aplicar leitura, escrita e manipulação de dados em ambiente de Big Data utilizando **Apache Spark no Google Colab**. A análise envolve arquivos públicos de estatísticas de vídeos e comentários da plataforma YouTube.

## Tecnologias Utilizadas

- Python 3
- Google Colab
- Apache Spark 3.3.1 (via PySpark)
- Parquet
- Spark SQL

## Arquivos Utilizados

- `videos-stats.csv`: informações sobre vídeos (visualizações, likes, etc.)
- `comments.csv`: base de comentários feitos em vídeos

## Etapas Realizadas

- ✅ Leitura dos arquivos `.csv` com e sem inferência de schema
- ✅ Visualização dos dados (`show`) e estrutura (`printSchema`)
- ✅ Conversão e salvamento no formato `.parquet`
- ✅ Criação de tabela `tb_videos` no catálogo do Spark
- ✅ Consulta da tabela usando SQL no Spark
- ✅ Upload e manipulação de múltiplos arquivos em ambiente distribuído

## 📊 Objetivo

O objetivo é simular tarefas comuns de um analista de dados em ambiente de Big Data, combinando dados de diferentes fontes e formatos. O projeto também serve como base para etapas futuras de tratamento e análise avançada.

## Como Executar

1. Faça upload dos arquivos `videos-stats.csv` e `comments.csv` no Colab
2. Abra o notebook `leitura-escrita.ipynb`
3. Execute as células passo a passo

> **Obs:** O ambiente Spark é instalado diretamente no Colab nas primeiras células.

## Autora

Projeto desenvolvido por [Lu Carvalho](https://github.com/Lucarvalho123) como parte do estudo prático sobre ferramentas de Big Data e análise de dados com Spark.

---

