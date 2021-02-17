# desafio_nodeJS

## O seu objetivo neste desafio é criar um microserviço para um crud completo. 
## Além das funções básicas Create, Retrieve, Update, Delete, deverá ser criado mais 3 endpoints 
  - Update massivo
  - Delete massivo
  - Retrieve massivo

## Especificações
  - 1 - Realizar o desafio em Node
  - 2 - Os dados do endpoint deverão ser salvos em um banco de dados relacional (nosso preferido é o mysql)
  - 3 - Todas as ações devem gerar log. Por exemplo : editei um produto, deverá ser gravado data e hora da alteração, assim como o que foi modificado
  - 4 - Ao deletar um produto, o mesmo deverá ser inserido em uma tabela auxiliar, salvando seus atributos (nome, id, data e hora que ocorreu a deleção).
  - 5 - Deverá ser criado um cron para limpar esta tabela auxiliar, ou seja, produtos inseridos do dia anterior pra trás deverão ser limpos. Este cron deverá executar uma vez ao dia, na hora que desejar.
 ## Opcionais
  - Uso de ORM's como sequelize
  - Autenticação JWT e proteção de rotas
  - Arquitetura hexagonal
