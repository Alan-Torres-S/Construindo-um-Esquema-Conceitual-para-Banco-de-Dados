# Projeto - Construindo um Esquema Conceitual para Banco de Dados

Neste repositório encontra-se o projeto do Bootcamp Unimed BH da Digital Innovation One (DIO) sobre a construção de um esquema conceitual para Banco de Dados.

# Sobre o Projeto

Trata-se da criação de um esquema conceitual do zero. O esquema conceitual de ER foi elaborado com base nos conceitos estudados no curso de Banco de Dados SQL e NoSQL pela DIO, ministrado pela Data Scientist Juliana Mascarenhas.

Para a elaboração deste esquema conceitual de ER foi utilizada a ferramenta MySQL Workbench.

## Narrativa do projeto

* Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica.
* Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões  periódicas.
* Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.
* A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra.
* O valor de cada peça também irá compor a OS, o cliente autoriza a execução dos serviços.
* A mesma equipe avalia e executa os serviços.
* Os mecânicos possuem código, nome, endereço e especialidade.
* Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.