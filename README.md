# Sistema-de-Pedidos-com-Dominio-e-ORM
Projeto Java com ORM utilizando JPA/Hibernate, banco H2 e Maven. Inclui relações complexas entre entidades: N-N, N-1, 1-1. Modelagem de domínio rica para um sistema de pedidos dinâmico.

🚀 Bem-vindo ao repositório do nosso Sistema de Pedidos! Este projeto foi cuidadosamente construído para explorar o poder dos modelos de domínio ricos em Java, utilizando a abstração de ORM para uma interação fluente e robusta com o banco de dados.

O Que Temos Aqui?
Banco de Dados H2: Implementamos um banco de dados em memória H2 para facilitar o desenvolvimento e os testes. Ele é rápido, leve e perfeito para nosso ambiente de experimentação.

Maven como Gerenciador: Usamos o Maven para gerenciar nossas dependências, garantir que nossas builds sejam reprodutíveis e simplificar nosso processo de build.

ORM com JPA: Tiramos proveito do JPA para mapear nossos objetos do domínio para o banco de dados, abstraindo a complexidade das transações SQL.

Relacionamentos de Entidade: Modelamos diferentes tipos de relacionamentos entre as entidades:

Relações N-N (Muitos-para-Muitos): Como entre Produto e Categoria, para representar a diversidade de nosso catálogo.
Relações N-1 (Muitos-para-Um): Cada Pedido tem vários Itens e cada Item pertence a um único Pedido.
Relações 1-1 (Um-para-Um): Cada Pagamento é associado a um único Pedido, garantindo a unicidade da transação.
