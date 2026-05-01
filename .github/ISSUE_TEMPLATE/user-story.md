## História de Usuário

Como um administrador do sistema,
Eu preciso da capacidade de criar novos produtos no catálogo,
Para que eu possa disponibilizar itens para venda no site de comércio eletrônico.

---

## Detalhes e Suposições

* O catálogo de produtos será armazenado em um banco de dados
* Cada produto deve conter nome, descrição, preço e quantidade em estoque
* O sistema deve validar os dados antes de salvar

---

## Critérios de Aceitação

Dado que o administrador está autenticado no sistema,
Quando ele envia os dados válidos de um novo produto,
Então o produto deve ser salvo com sucesso no catálogo e estar disponível para consulta.
