# Convenções básicas
1. Usar snake_case
2. Sempre Utilizar verbos para nomear funções, e utilizar nomes descritivos para nomear variáveis
3. Sempre verificar o diretório de trabalho atual (getwd() e setwd())
4. Sempre que possível crie um projeto R no lugar de criar apenas um script R, visando evitar problemas de caminho e de isolamento
5. Sempre caminhos relativos dentro de um projeto R para acessar arquivos e pastas
6. Nunca modifique o dado bruto (planilha, banco de dados, etc...)
7. Use pacotes adequados para tipos de dados e tipos de bases de dados adequados (readxl para planilhas excel, tidyverse para csv, DBI e ODBC para bancos SQL)
8. Sempre crie funções para evitar a duplicação de código.<br> Sintaxe: nome_funcao <- function(parametros){expressoes return()}
9. Sempre modularize seu código:<br>
9.1. Crie um script r para definir suas funções e chame o arquivo para onde o código será executado através da função source("path_arquivo.r")<br>
9.2. Crie scripts r para cada fase do projeto (extracao, transformacao, analise_descritiva, analise_diagnostica, analise_preditiva,...)<br>
9.3. Separe o seu dataframe após a extração e salve ele no formato rds com saveRDS() e readRDS() para carga e leitura eficiente, separando o dataframe bruto do dataframe limpo

# Estrutura base de um projeto R
```
project/
- README.md   # Project description written in Markdown (we will talk about this later)
- R/          # Where the R scripts live
- input/      # Data files
- output/     # Results: plots, tables..
```

