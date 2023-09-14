exemplo requisitos de sistema

//Cadastro 

RF-01 |A aplicação deve permitir que usuários não autenticados possam se registrar com informações pessoais. | -
RF-02 |Um usuário não autenticado pode alterar a própria senha através do fluxo de "Esqueceu a senha". | - RF-01.
RF-03 |Um usuário não autenticado pode realizar a autenticação na aplicação. | - RF-01.

//Pesquisa de Produtos

RF-04 |A aplicação deve ter um filtro avançado para refinar os resultados da pesquisa. | -

//Catálogo de Produtos

RF-05 |A aplicação deve exibir informações detalhadas de produtos, incluindo imagens, preços, descrições e disponibilidade. | - RF-04.
RF-06 |A aplicação poderá ter classificação por popularidade, preço, avaliações dos clientes, etc. | - RF-04.

//Carrinho de Compras

RF-07 |Um usuário não autenticado e/ou autenticado pode adicionar itens ao carrinho. | - RF-01.
RF-08 |Um usuário não autenticado e/ou autenticado pode remover itens do carrinho. | - RF-01.
RF-09 |A aplicação deve calcular automaticamente o total da compra. | - RF-07, RF-08.
RF-10 |Usuários poderão visualizar o resumo do carrinho antes da finalização da compra. | - RF-07, RF-08, RF-10.
