### Explique com suas palavras o papel de cada camada da arquitetura MVC usada neste projeto.
#### Como o Model, o Controller e a View interagem entre si?

O Model cria e faz as requisições em CRUD que o controller usará.
O Controller roda essas requisições e retorna o resultado para o banco de dados.
O View exibe os resultados que o usuário deseja.

### Como ocorre o envio e o recebimento de dados no formato JSON neste projeto?
#### Cite uma rota que responde em JSON e explique seu funcionamento.

Os elementos como Forms e inputs guardam informações em JSON no formato das tabelas do banco de dados e realiza o POST e GET em JSON.

EX: router.post('/edit/:id', controller.update); é o ENDPoint usado ao clicar no botão de editar uma informação no View. Ele pega as informações enviadas e armazenam em JSON.

### Qual a importância de usar HTML básico com formulários e tabelas para organizar e manipular dados no navegador?
#### Por que esse tipo de estrutura ainda é útil em projetos back-end com Node.js?

Ele é importante para realizar e visualizar as requisições em um formato visualmente agradável para experiência do usuário. Se utilizassemos a outra forma de visualizar (console) essas requisições seriam em código, o que é ruim e menos prático do que em HTML.
