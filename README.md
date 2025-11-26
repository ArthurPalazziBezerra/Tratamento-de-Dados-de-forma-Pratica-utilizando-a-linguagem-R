
# Tratamento de Dados de forma Pratica utilizando a linguagem R

Este projeto realiza a leitura, inspeção, análise exploratória e tratamento da base Tempo.csv, que contém variáveis relacionadas às condições climáticas e decisão de jogar ou não. Observação: O arquivo está em RMD, de preferencia execute-o com VScode com extensão para markdowns ou no Rstudio, obrigado!

Objetivo

Organizar e preparar os dados para análises posteriores, identificando inconsistências, valores ausentes e outliers nas variáveis categóricas e numéricas.

Etapas do Projeto
1. Importação e visualização inicial

Leitura da planilha com read.csv().

Verificação estrutural com head() e summary().

2. Análise de variáveis categóricas

Frequências calculadas com table().

Criação de gráficos de barras (barplot()) para:

Aparência

Vento

Jogar

3. Análise de variáveis numéricas

Para Temperatura e Umidade:

Estatísticas descritivas

Boxplots para detecção de outliers

Histogramas para avaliar distribuição

4. Tratamento de missing values

Identificação de linhas incompletas com complete.cases().

Correção de valores ausentes em Vento, substituindo por "FALSO".

5. Correção de inconsistências

Valor incorreto "menos" em Aparência substituído pela categoria correta.

Conversão da coluna para factor.

6. Tratamento de outliers

Temperaturas fora do intervalo plausível substituídas pela mediana.

Umidades fora do intervalo 0–100 ou NAs corrigidas também com a mediana.



Resultado

A base final é entregue sem valores faltantes ou inconsistentes e com variáveis numéricas ajustadas, permitindo análises mais robustas e evitando distorções em modelos futuros.


