# DatathonONS
Resolução do 4º Datathon da ONS

Esse repositório é de um desafio proposto pela ONS (Operador Nacional do Sistema Elétrico). É um projeto feito em conjunto com Flávio e Marcelo. O desafio: O ONS trabalha com ponte entre os membros da Rede Básica de energia. Seu papel, nesse desafio, é garantir a conformidade das informações nos contratos entre usuários (geradores de energia) e o agente de transmissão. Até julho de 2022, foram recebidos cerca de 500 contratos do tipo CCT (contrato firmado entre usuário e transmissor). Estes contratos precisam ser analisados manualmente, o que demanda muito tempo. Assim sendo, nosso objetivo é fazer com que essa validação seja feita de forma automizada.

## Bibliotecas: 
1 - Biblioteca “tika” para leitura dos pdfs. 2 - Biblioteca “datetime” para trabalhar com datas 3 - Biblioteca “re” para expressões regulares, utilizada principalmente para detectar CNPJs e identificações de documentos. 4 - Biblioteca “pandas” para trabalhar com Dataframes.

## Como rodar: 
Para rodar o projeto é necessário substituir os caminhos nas variáveis indicadas no arquivo. Deixo abaixo os caminhos a serem alterados: 1 - path_contratos 2 - path_base_agentes 3 - path_excel_parecer_de_acesso

## Metodologia adotada: 
1- Leitura dos pdfs dos contratos, transformando-os para strings; 2- Tratamento das strings a depender da tarefa realizada; 3- Extração das informações no texto; 4- Validação de cada item através de similaridade com um texto esperado ou com informação presente num banco de dados.
