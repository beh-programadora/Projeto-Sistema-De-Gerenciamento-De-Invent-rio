Inventário de Armazém
Descrição
Este projeto gerencia o inventário de um armazém, incluindo produtos, categorias e fornecedores. O banco de dados inclui tabelas para armazenar informações sobre categorias de produtos, fornecedores e os próprios produtos. As relações entre essas tabelas são definidas por chaves estrangeiras para garantir a integridade referencial.

Estrutura do Banco de Dados
Categorias: Armazena informações sobre as categorias dos produtos.

id_categoria: Identificador único da categoria (PRIMARY KEY)
nome: Nome da categoria
Fornecedores: Armazena informações sobre os fornecedores.

id_fornecedor: Identificador único do fornecedor (PRIMARY KEY)
nome: Nome do fornecedor
contato: Informação de contato do fornecedor
endereco: Endereço do fornecedor
Produtos: Armazena informações sobre os produtos no inventário.

id_produto: Identificador único do produto (PRIMARY KEY)
nome: Nome do produto
descricao: Descrição do produto
preco: Preço do produto
quantidade_estoque: Quantidade em estoque
id_categoria: Identificador da categoria do produto (FOREIGN KEY)
id_fornecedor: Identificador do fornecedor do produto (FOREIGN KEY)
Instruções de Uso
Criação do Banco de Dados

Execute o script SQL para criar o banco de dados e as tabelas.
Inserção de Dados

Utilize os comandos de inserção fornecidos para popular as tabelas com dados de exemplo.
Consultas e Atualizações

Utilize as consultas SQL para visualizar dados e realizar atualizações conforme necessário.
Exclusão de Dados

Use o comando DELETE para remover registros específicos.
Consultas Exemplos
Listar todos os produtos com suas respectivas categorias e fornecedores.
Mostrar todos os produtos que pertencem a uma categoria específica.
Exibir fornecedores que fornecem produtos acima de um determinado preço.
Contribuição
Sinta-se à vontade para contribuir para este projeto. Se você encontrar algum problema ou tiver sugestões de melhorias, por favor, abra uma issue ou envie um pull request.

Licença
Este projeto é fornecido sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
