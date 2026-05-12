# ALPHA-TECH
Apresenta o desenvolvimento de um aplicativo mobile para gerenciamento de uma loja de peças de computador.
A aplicação permite organizar produtos por categorias, controlar o estoque em tempo real e simular uma experiência de compra por meio de um carrinho.
O sistema foi desenvolvido utilizando Flutter e Dart no frontend, com integração a uma API em Django e banco de dados, garantindo organização e eficiência no gerenciamento das informações.

MODELAGEM E BANCO DE DADOS

O desenvolvimento iniciou pela criação do banco de dados, estruturando as principais entidades da aplicação: produtos, categorias, carrinho e itens do carrinho.
As tabelas foram relacionadas por meio de chaves estrangeiras, garantindo a integridade dos dados e permitindo a associação entre produtos, categorias e operações de compra.

Desenvolvimento da API

Com o banco de dados definido, foi desenvolvida uma API utilizando Django. A partir das tabelas, foram criados os models, seguidos pelos serializers, views e rotas.
A API implementa operações completas de CRUD (criação, leitura, atualização e exclusão), permitindo o gerenciamento total dos dados da aplicação. Após a implementação, foram realizados testes para validar o funcionamento correto dos endpoints.
Desenvolvimento Mobile
Na etapa mobile, utilizando Flutter, iniciou-se pela criação de telas simples para listagem de dados. Em seguida, foi implementado o CRUD de produtos.
A funcionalidade de carrinho foi desenvolvida por último, por envolver maior complexidade devido ao relacionamento entre tabelas e regras de negócio, como controle de quantidade e cálculo de valores.

CONSIDERAÇÕES FINAIS

O desenvolvimento do aplicativo permitiu aplicar, de forma prática, conceitos de banco de dados, construção de APIs e desenvolvimento mobile. Foi possível criar uma solução funcional para o gerenciamento de uma loja de peças de computador, atendendo aos objetivos propostos.
Durante o processo, foram enfrentados desafios técnicos, principalmente na integração entre o banco de dados e o Django, além de problemas relacionados à lógica do carrinho e controle de estoque. A resolução desses problemas contribuiu para o aprimoramento do sistema e para o aprendizado sobre boas práticas de desenvolvimento.
A aplicação final demonstrou ser eficiente, oferecendo funcionalidades como organização de produtos, controle de estoque e simulação de compras de forma simples e intuitiva.
Por fim, o projeto reforça a importância da integração entre diferentes tecnologias e
evidencia como soluções mobile podem trazer mais praticidade e eficiência para o gerenciamento de negócios.
