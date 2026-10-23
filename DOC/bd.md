
    //Banco.db
    O banco de dados foi feito pelo vs code.
    – A seed é aonde esta todos os códigos da criação das 5 tabelas (Clientes, Equipamentos, Técnicos, Status e Ordem e serviço) Também tem os códigos das informações que vai em cada tabela. 

    –  No banco.db contém as 5 tabelas, já com as informações.

    – Tabela Clientes:
    ID: é um identificador único de cada registro
    Nome: nome de cada cliente registrado
    Telefone: telefone dos clientes registrados
    Email: email pessoal de cada cliente

    – Tabela Equipamentos:
    ID: identificador único de cada registro
    Nome: nome do produto registrado

    – Tabela Ordem e serviço:
    ID:  identificador único de cada registro do equipamento
    Descrição do problema: descreve o problema do equipamento registrado
    Data: Data que foi relatado o problema 

    – Tabela Status:
    ID:  identificador único de cada registro
    Descrição: mostra se o produto esta pendente, concluída ou em andamento

    – Tabela Técnicos
    ID: mostra o identificador único de cada técnico
    Nome: Mostra o nome de cada técnico registrado
    Especialidade: Indica a área em que cada técnico possui conhecimento ou atua
    Contato:  armazena o telefone ou e-mail do técnico, facilitando a comunicação

    – Relacionamento das tabelas:  As tabelas se relacionam por meio da ordem de serviço, que conecta o cliente, o técnico, o equipamento e o status, mantendo todas as informações organizadas.
    Explicando cada relacionamento:
    Cliente: pode ter várias ordens de serviço.
    Técnico: pode ser responsável por várias ordens.
    Equipamento: pode estar associado a várias ordens.
    Status: indica a situação de cada ordem, como pendente, em andamento ou concluída.


