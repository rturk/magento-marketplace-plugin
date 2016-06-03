Manual de Usuário 
Introdução

O módulo de integração com o Market Place tem como finalidade tornar possível a venda dos produtos da sua loja virtual na vitrine do Extra.com. Ele irá proporcionar o envio de produtos, o recebimento de pedidos e o acompanhamento de chamados por meio da interface de adminstração da Plataforma.

No entanto, antes de utilizar a integração proporcionada pelo módulo, você deve configurar todos os parâmetros corretamente, evitando que ocorram exceções e melhorando a qualidade dos dados enviados, o que irá proporcionar uma melhor experiência.

O módulo possui ações síncronas e assíncronas, ou seja, há algumas funcionalidades que serão executadas de tempos em tempos pelo cron da Plataforma (certifique-se de que ele esteja funcionando corretamente).



Configuração do Módulo

As configurações são realizadas na área de configuração da Plataforma, acessando o menu Sistema -> Configurações -> Extra.com. Neste menu, encontraremos três seções:

- Geral
- Configurações de Cliente
- Configurações de Produto

Geral

Nesta parte iremos configurar as informações genéricas do módulo, como por exemplo os dados de autenticação do lojista no Market Place, os tempos de latência e até ativar o módulo. Cada uma das configurações são discriminadas abaixo:

- Ativo: configuração utilizada para habilitar ou desabilitar o módulo;
- Token de Aplicação: identificador da aplicação fornecido pelo Extra.com para o lojista;
- Token de Autenticação: identificador de autenticação fornecedo pelo Extra.com para o lojista;
- Latência do serviço de Pedido: tempo entre cada sincronização automática dos pedidos entre Extra.com e Plataforma;
- Latência do serviço de Produtos: tempo entre cada sincronização automática dos produtos entre Extra.com e Plataforma;
- Método de envio padrão: métdo de envio associado ao pedido em caso de falha na obtenção do método através do Extra.com;
- Loja Padrão: loja em que entrará os pedidos.
ATENÇÃO! O módulo não deve ser ativado até que todas as configurações sejam corretamente realizadas.


Configurações de Cliente

Nesta seção o lojista faz o mapeamento dos campos que são essenciais para a idenficação do mesmo no Extra.com. Este mapeamento fará a conversão dos dados vindos do Market Place à sua configuração de campos na Plataforma, permitindo que os dados sejam alocados nos atributos corretos da sua loja virtual. As configurações são divididas em três áreas:

- Pessoa Física: são dados relativos ao cadastro de pessoa física (nome, sobrenome, CPF, RG e celular);
- Empresa: são dados relativos ao cadastro de pessoa jurídica (razão social, inscrição estadual e CNPJ);
- Endereço: são os campos de endereço do cliente.
O mapeamento acontece da seguinte forma: todos os campos exigidos pelo Extra.com têm uma caixa de seleção à sua direita, na qual são listados todos os campos de cadastro de cliente e endereço da Plataforma. O lojista então seleciona cada campo e pode fazer um teste que mostra como ficaria a associação utilizando um cliente qualquer selecionado dentre os disponíveis.


Configurações de Produto

Nesta seção o lojista poderá configurar quais atributos serão utilizados para enviar as informações do produto ao Extra.com. Existe uma caixa de seleção que permite que o lojista escolha qual campo deve ser utilizado para enviar as informações de dimensões (altura, largura e comprimento) e a marca dos produtos.

Caso a sua loja virtual não possua um campo para determinado atributo, poderão ser utilizados valores padrões definidos nesta configuração: na caixa de seleção escolha a opção "Usar padrão". Assim, será exibida um campo de texto abaixo da caixa de seleção para que seja preenchido o valor padrão a ser adotado. Mas atenção! É importante configurar sua integração da forma mais precisa possível, uma vez que estas configurações têm importante papel no cálculo de frete e na exibição de dados do produto no Extra.com, de forma que o valor padrão trata-se de uma saída para casos peculiares.

No caso do campo marca, além de poder escolher um valor padrão, você tem a opção de não enviar este campo. Para tanto, basta selecionar a opção "Não" na configuração "Possui Marca".
