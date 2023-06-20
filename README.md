# Case_Data_Analyst
Concepção de projeto voltado para área de análise de dados no qual é disponibilizado um arquivo chamado "Arquivo_limpar.csv" para Carregamento, Tratamento e Carregamento(ETL). 

# Metodologia: 
Tarefa 1 - limpar/normalizar:
Separar o endereço criando novos campos: TIPO_LOGRADOURO, NOME_LOGRADOURO, NUMERO e COMPLEMENTO
*No campo NUMERO deverá conter apenas dados de tipo numéricos, outras informações deverão ser colocadas no campo COMPLEMENTO.

Tarefa 2 - juntar endereços utilizando o DocId
Identificar os Clientes com mesmo Codigo e DocId colocar na mesma linha os endereços encontrados
*Podem ser criados novos campos: (TIPO_LOGRADOURO_1, NOME_LOGRADOURO_1, NUMERO_1, COMPLEMENTO_1; TIPO_LOGRADOURO_2, NOME_LOGRADOURO_2, NUMERO_2, COMPLEMENTO_2; ... ;TIPO_LOGRADOURO_N, NOME_LOGRADOURO_N, NUMERO_N, COMPLEMENTO_N;)

Tarefa 3 - achar/tratar DocId vazios/zerados  
Identificar nome e código de clientes com DocId vazios/zerados utilizando as chaves que julgar ser suficiente para tal (Identificar DocId em novo campo DOCId_SUGERIDO)
Não esquecer de voltar na tarefa 2 e adicionar os endereços referentes ao docs sugeridos.

4 - Salvar arquivo em formato .xlsx com os tratamentos executados e prints do código/ferramenta utilizado para fazer os tratamentos.
