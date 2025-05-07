# Pipeline de Dados do Telegram com AWS  
**Projeto Final do Curso de Analista de Dados – EBAC**

Este projeto faz parte da etapa final do curso de Analista de Dados da EBAC, onde foi desenvolvido um pipeline automatizado para captura, armazenamento, transformação e análise de mensagens de um grupo do Telegram, utilizando serviços da AWS.

## Objetivo  
Criar um fluxo completo para capturar mensagens enviadas em um grupo do Telegram, armazená-las, transformá-las em um formato otimizado (Parquet) e disponibilizá-las para análise via consultas SQL no AWS Athena.

## Tecnologias Utilizadas  
- Python – Funções AWS Lambda para conversão e transformação de dados  
- AWS Lambda – Execução do processamento de dados  
- AWS API Gateway – Roteamento das mensagens capturadas  
- AWS S3 – Armazenamento das mensagens brutas e processadas  
- AWS EventBridge – Agendamento da transformação de dados  
- AWS Athena – Consultas SQL para análise das mensagens  

## Conteúdo do Repositório  
- `StoryTelling_Bot_Telegram.ipynb`: notebook com  
  - Código das funções Lambda (captura e ETL)  
  - Consultas SQL utilizadas no AWS Athena  
  - Análises exploratórias e insights gerados a partir dos dados  

## Como Explorar o Projeto  
1. Acesse o notebook `StoryTelling_Bot_Telegram.ipynb`  
2. Siga o passo a passo documentado no storytelling  
3. Explore os insights gerados a partir das mensagens capturadas  

## Considerações  
Este projeto é um estudo prático sobre automação de dados, armazenamento otimizado e análise de mensagens de grupos do Telegram utilizando serviços da AWS.
