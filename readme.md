1.Introdução 
            Esse projeto de Banco de Dados é direcionado a uma ferramenta, na qual tem como objetivo auxiliar na administração e no controle de produtos de uma concessionária, evitando prejuízos para a empresa. Neste projeto existem dois tipos de usuários principais:  o gerente responsável por cadastro de produtos, vendedores e clientes e o Vendedor cadastrar cliente, saída e entrada de mercadoria. 

2. Descrição Geral
	O sistema a ser desenvolvido, é um sistema de venda e gerenciamento de produtos de uma concessionária. Uma má administração de funcionários, produtos e clientes em uma concessionária, pode causar uma alta diminuição dos lucros, até mesmo, desvio de caixa ( caixa 2). O software em questão, tem como principal característica, tornar mais fácil, tanto a vida do vendedor, quanto a vida do dono da loja. Com recursos otimizados e de fácil entendimento, será possível a realização de uma venda de forma simples e prática, e uma melhor manipulação de estoque e de produtos oferecidos pela empresa, além de um fácil gerenciamento de clientes, seja suas faturas pendentes à créditos na casa.

3. Usuários

	3.1 Gerente

	É o responsável por administrar o sistema, os vendedores e os clientes. Fica responsável pelo cadastro no estoque e alterações mais específicas do sistema. Monitora o pagamento dos clientes e as vendas e preços manipulados pelos vendedores.

	3.2 Vendedor

	É o responsável pela venda dos produtos; cadastro de clientes; manipular entrada e saída de produtos no estoque; negociar valores;

4. Funcionalidades do sistema

Regras: O sistema terá dois tipos de acesso, o acesso de vendedor poderá fazer buscas de produtos registrados no sistema e cadastrar novos clientes com suas informações pessoais para futuras compras, consultas de crédito e pagamento. O acesso de administrador terá acesso a todo o sistema, poderá criar novos logins de vendedor e criar novos produtos para o sistema, poderá editar produtos e logins existentes.

Um vendedor não poderá criar produtos.
O cadastro de cliente deverá conter informações pessoais necessárias para uma compra no sistema(CPF, Nome completo, Idade).
A idade do cliente deve ser maior que 18.

O sistema permite que o usuário tenha acesso ao estoque, que lista todos os produtos registrados pelo administrador do sistema. O vendedor deve alinhar junto ao cliente o que ele deve buscar, caso o retorno dessa busca seja existente, uma lista de produtos referente a busca deve ser exibida, caso não, o vendedor deverá informar ao cliente que o produto não existe no sistema e deverá informar a um administrador a demanda de tal produto. Quando clicado no produto uma página exibindo as informações do produto como imagem, nome, modelo, mini descrição(se houver), preço e variantes(cor, modelo, caso houver)  deve ser exibida. Na parte de vendas o cliente deverá escolher as propriedades de seu produto e forma de pagamento, caso a venda seja realizada, o produto deverá ser atribuído ao cliente, e essa transação deve ser registrada no sistema. O Vendedor posteriormente poderá checar o andamento dessa transação, como quantas parcelas faltam, o total do produto e qual cliente o tem.


