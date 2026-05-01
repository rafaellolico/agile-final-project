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

Cenário: Criar produto com dados válidos

* Dado que o administrador do sistema está autenticado
* E que ele acessa a página de cadastro de produtos
* Quando o administrador preenche todos os campos obrigatórios com dados válidos
* E clica no botão de salvar
* Então o sistema deve registrar o produto no catálogo
* E o produto deve aparecer na lista de produtos disponíveis
