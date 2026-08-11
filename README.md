TESTE MANUAL - SouceDemo

Este arquivo contém as validações reais que executei no site SouceDemo

cenário 1: login com sucesso
pré-condição: não ter uma conta criada ainda

passos:

1.Usuário deve preencher todos os campos para criar um cadastro
2. cadastrar

resultado esperado: conta criada com sucesso
status: passou

cenário 2:escolher tamanho do produto e adicionar ao carrinho
pré-condição: não ter adicionado produto no carrinho e estar logado a uma conta

passos:

1.Escolha um produto do catálogo
2.click nesse produto
3.escolha o tamanho do seu produto 
4.aperte em "add to cart" desse produto

resultado esperado: O número do carrinho que estava em (0) deve ir para (1)
status: passou

cenário 3: validar o link que direciona o Usuário pra pagina inicial
pré-condição: estar na pagina do produtos

1.No menu no meio da tela, clicar no link "lar"

resultado esperado: O sistema deve direcionar o usuário pra pagina de inicio da loja.

status: passou

cenário 4: finalização do pedido
pré-condição: preencher todos os campos com seus dados

passos:

1.ir no carrinho 
2.apertar a opção de "pagamento"
3.preencher todos os campos com seus dados
4.apertar o botão de "confirmar"

resultado esperado: seu pedido foi confirmado com sucesso

status:passou

RELATÓRIO DE BUGS ENCONTRADOS

defeito 1: ausência de opção de remover o produto do carrinho ou gerenciar itens.

passos:

1.adicionar qualquer produto no carrinho 
2.ir para a página de visualização do carrinho de compras.

comportamento incorreto: Não existe nenhum botão ou opção de retirar um produto do carrinho se o usuário mudar de ideia.

defeito 2: contador de endereços incorretos na página da conta

passos:

1.Acessar a página de perfil "Conta" sem ter cadastrado nenhum endereço antes

comportamento incorreto: O sistema exibe o botão de "ENDEREÇOS (1)", mostrando uma falsa informação, já que a lista de endereços deveria estar zerada.

defeito 3: Barra de pesquisa não aceita termos em português no site traduzido

passos:

1.traduzir o site para o idioma Português através do navegador
2.Ir até a barra de pesquisa (pesquisar) no rodapé do site.
3.Digitar uma palavra em português (ex: "jaqueta") pressionar Enter.

comportamento incorreto: o sistema não encontra nenhum resultado e exibe a página vazia. o site só exibe os produtos se usar termos em inglês (ex: "jacket"), quebrando a experiência do usuário que navega em português.

defeito 4: link de "indique para amigos" não funciona
passos:

1.Ir para o menu do site
2.clicar em "indique para amigos"

comportamento incorreto: O link não direciona o usuário a outra pagina, não contendo funcionalidade.

defeito 5: Menagens de erro do checkout exibidas em inglês

passos:
TESTE MANUAL - SouceDemo

Este arquivo contém as validações reais que executei no site SouceDemo

cenário 1: login com sucesso
pré-condição: não ter uma conta criada ainda

passos:

1.Usuário deve preencher todos os campos para criar um cadastro
2. cadastrar

resultado esperado: conta criada com sucesso
status: passou

cenário 2:escolher tamanho do produto e adicionar ao carrinho
pré-condição: não ter adicionado produto no carrinho e estar logado a uma conta

passos:

1.Escolha um produto do catálogo
2.click nesse produto
3.escolha o tamanho do seu produto 
4.aperte em "add to cart" desse produto

resultado esperado: O número do carrinho que estava em (0) deve ir para (1)
status: passou

cenário 3: validar o link que direciona o Usuário pra pagina inicial
pré-condição: estar na pagina do produtos

1.No menu no meio da tela, clicar no link "lar"

resultado esperado: O sistema deve direcionar o usuário pra pagina de inicio da loja.

status: passou

cenário 4: finalização do pedido
pré-condição: preencher todos os campos com seus dados

passos:

1.ir no carrinho 
2.apertar a opção de "pagamento"
3.preencher todos os campos com seus dados
4.apertar o botão de "confirmar"

resultado esperado: seu pedido foi confirmado com sucesso

status:passou

RELATÓRIO DE BUGS ENCONTRADOS

defeito 1: ausência de opção de remover o produto do carrinho ou gerenciar itens.

passos:

1.adicionar qualquer produto no carrinho 
2.ir para a página de visualização do carrinho de compras.

comportamento incorreto: Não existe nenhum botão ou opção de retirar um produto do carrinho se o usuário mudar de ideia.

defeito 2: contador de endereços incorretos na página da conta

passos:

1.Acessar a página de perfil "Conta" sem ter cadastrado nenhum endereço antes

comportamento incorreto: O sistema exibe o botão de "ENDEREÇOS (1)", mostrando uma falsa informação, já que a lista de endereços deveria estar zerada.

defeito 3: Barra de pesquisa não aceita termos em português no site traduzido

passos:

1.traduzir o site para o idioma Português através do navegador
2.Ir até a barra de pesquisa (pesquisar) no rodapé do site.
3.Digitar uma palavra em português (ex: "jaqueta") pressionar Enter.

comportamento incorreto: o sistema não encontra nenhum resultado e exibe a página vazia. o site só exibe os produtos se usar termos em inglês (ex: "jacket"), quebrando a experiência do usuário que navega em português.

defeito 4: link de "indique para amigos" não funciona
passos:

1.Ir para o menu do site
2.clicar em "indique para amigos"

comportamento incorreto: O link não direciona o usuário a outra pagina, não contendo funcionalidade.

defeito 5: Menagens de erro do checkout exibidas em inglês

passos:

1.navegar pelo site com a tradução para português ativada
2.na tela de checkout, digitar dados incorretos nos campos
3.observar os alertas de erro quem surgem abaixo dos campos

comportamento incorreto: As mensagens de alertas são exibidas em inglês mesmo com a tradução automática, falhando na tradução da interface para o usuário.








1.navegar pelo site com a tradução para português ativada
2.na tela de checkout, digitar dados incorretos nos campos
3.observar os alertas de erro quem surgem abaixo dos campos

comportamento incorreto: As mensagens de alertas são exibidas em inglês mesmo com a tradução automática, falhando na tradução da interface para o usuário.







