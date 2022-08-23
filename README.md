# Construindo-um-Esquema-Conceitual-de-Oficina
Criado um esquema conceitual de um database de uma oficina do zero. A partir da narrativa fornecida criei todas as entidades, relacionamentos e atributos.

📦 Objetivos

Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica
Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões  periódicas (tabela Serviço_referências)
Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega (tabela equipe e Ordem_de_Servico)
A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra (tabela Ordem_de_Servico)
O valor de cada peça também irá compor a OSO cliente autoriza a execução dos serviços (tabela Pecas e tabela Ordem_de_Servico)
A mesma equipe avalia e executa os serviços (tabela Equipe))
Os mecânicos possuem código, nome, endereço e especialidade (tabela Funcionários)

🛠️ Construído com MySQL Workbench
