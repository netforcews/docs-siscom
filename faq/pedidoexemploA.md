# PEDIDO

- [Inclusão do pedido](#InclusaoDoPedido)
- [Inclusão de referências (itens) do pedido](#InclusaoDeReferenciasDoPedido)
- [Inclusão de parcelas do pedido](#InclusaoDeParcelasDoPedido)
- [Fechando o pedido](#FechandoOPedido)
- [Entrega total](#EntregaTotal)   
  - [Comissões a receber](#ComissoesAReceber)
     - [Recebendo totalmente o titulo 00018692/A](#RecebendoTotalmenteOTitulo)
     - [Recebendo parcialmente todo titulo 00018692/A](#RecebendoParcialmenteTodoOTitulo)
     - [Recebendo parcialmente o título 00018692/A](#RecebendoParcialmenteParteDoTitulo)
   - [Comissões a pagar](#ComissoesAPagar)
   - [Não selecionado: Baixar as comissões a pagar quando é baixado as comissões a receber](#NaoSelecionado)
     - [Pagando totalmente o titulo 00018692/A](#NSPagandoTotalmenteOTitulo)
     - [Pagando parcialmente todo o titulo 00018692/A](#NSPagandoParcialmenteTodoOTitulo)
     - [Pagando parcialmente o titulo 00018692/A](#NSPagandoParcialmenteOTitulo)
   - [Selecionado: Baixar as comissões a pagar quando é baixado as comissões a receber](#Selecionado)
     - [Pagando totalmente o titulo 00018692/A](#SPagandoTotalmenteOTitulo)
     - [Pagando parcialmente todo o titulo 00018692/A](#SPagandoParcialmenteTodoOTitulo)
     - [Pagando parcialmente o titulo 00018692/A](#SPagandoParcialmenteOTitulo)
- [Entrega parcial](#EntregaParcial)   

<br>

## Inclusão do pedido  <a id="InclusaoDoPedido"></a>
Para acessar esta opção, selecione o módulo **Vendas**, opção **Geral**, opção **Pedidos** e logo após clique na opção **Novo**.
![pedido.exemploA0](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA0.png)
   
Informaremos dois representantes: Representante C com 10% de comissão e Representante D com 2,5% de comissão, totalizando 12,5% de comissão.
![pedido.exemploA1](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA1.png)
   
## Inclusão de referências (itens) do pedido <a id="InclusaoDeReferenciasDoPedido"></a>
Na tela do pedido, clique em **Referências**.
Informaremos um valor e quantidade que nos resultem um montante final de R$ 90.000,00.   
![pedido.exemploA2](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA2.png)
![pedido.exemploA3](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA3.png)
   
## Inclusão de parcelas do pedido <a id="InclusaoDeParcelasDoPedido"></a>
Na tela do pedido clique em **Parcelas** e logo após em **Gerar parcelas**.
Como informamos a condição de pagamento **30/60/90 Dias**, o sistema irá gerar 3 parcelas.
![pedido.exemploA4](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA4.png)
![pedido.exemploA5](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA5.png)

> Perceba que a configuração da condição de pagamento está 33,34% para 30 dias, 33,33% para 60 dias e 33,33% para 90 dias.   
   
![pedido.exemploA6](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA6.png)
   
Em nosso exemplo, iremos alterar os valores de cada uma das parcelas arredondando-as e a data do vencimento para o primeiro dia do mês. 

> Perceba que alteramos o número de dias para mudar o vencimento.

![pedido.exemploA7](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA7.png)
   
Ao final, teremos as seguintes informações:
![pedido.exemploA8](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA8.png)
   
## Fechando o pedido <a id="FechandoOPedido"></a>
Na tela do pedido clique em **Comandos** e selecione a opção **Fechar pedido**.
![pedido.exemploA9](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA9.png)
   
Informe o número da nota fiscal e a data de faturamento.
   
## Entrega total <a id="EntregaTotal"></a>
Se a entrega for total (100%), mantenha as quantidades e clique em **Executar**.
![pedido.exemploA9](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA9.png)
   
No momento do fechamento, o sistema irá gerar dados para o financeiro e apresentar a mensagem abaixo.
![pedido.exemploA10](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA10.png)
    
### Comissões a receber <a id="ComissoesAReceber"></a>
Para acessar esta opção, selecione o módulo **Financeiro**, opção **Comissões a receber**.    
Vamos filtrar nosso pedido. Clique sobre a palavra **Número** para que a pesquisa por número seja selecionada. Em nosso exemplo, informaremos no campo **Filtro** o número do nosso pedido: **00018692** e selecionaremos **Nenhum filtro**.
![pedido.exemploA11](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA11.png)
    
> Perceba que aqui temos o montante de R$ 11.250,00 de comissões a receber do pedido.   
> Mas como chegamos a este valor?   
> O sistema fez a seguinte conta: (Percentual de comissão do Representante C + Percentual de comissão do Representante D) do total do pedido. Ou seja, ((10,00% + 2,5%) * R$ 90.000,00) / 100 = R$ 11.250,00; Como foram 3 parcelas, temos: R$ 11.250,00 / 3 = R$ 3.750,00. 
    
#### Recebendo totalmente o titulo 00018692/A <a id="RecebendoTotalmenteOTitulo"></a>
Na tela do título **00018692/A**, clique na aba **Lançamentos** e logo após na opção em **Novo**.
![pedido.exemploA12](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA12.png)
![pedido.exemploA13](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA13.png)
![pedido.exemploA14](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA14.png)

#### Recebendo parcialmente todo titulo 00018692/A <a id="RecebendoParcialmenteTodoTitulo"></a>
Na tela do título **00018692/A**, clique na aba **Lançamentos** e logo após na opção em **Novo**.
![pedido.exemploA12](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA12.png)
![pedido.exemploA15](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA15.png)   
Foi recebido R$ 2.000,00. Restando um saldo de R$ 1.750,00.
![pedido.exemploA16](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA16.png)   
Foi recebido mais R$ 1.000,00, totalizando R$ 3.000,00 recebidos. Restando um saldo de R$ 750,00.
![pedido.exemploA17](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA17.png)   
Foi recebido mais R$ 750,00, totalizando R$ 3.750,00 recebidos. 
![pedido.exemploA18](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA18.png)

#### Recebendo parcialmente o título 00018692/A <a id="RecebendoParcialmenteParteDoTitulo"></a>
Na tela do título **00018692/A**, clique na aba **Lançamentos** e logo após na opção em **Novo**.
![pedido.exemploA12](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA12.png)
![pedido.exemploA15](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA15.png)   
Foi recebido R$ 2.000,00. Restando um saldo de R$ 1.750,00.
![pedido.exemploA16](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA16.png)   
Foi recebido mais R$ 1.000,00, totalizando R$ 3.000,00 recebidos. Restando um saldo de R$ 750,00.
![pedido.exemploA19](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA19.png)   
Foi recebido mais R$ 500,00, totalizando R$ 3.500,00 recebidos. Restando um saldo de R$ 250,00.
<br>

![pedido.exemploA20](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA20.png)   
> Podemos considerar o saldo de R$ 250,00 como perdido, podendo manter desta forma caso algum dia queiramos gerar um acerto de contas.

![pedido.exemploA21](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA21.png)
![pedido.exemploA22](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA22.png)   
> Podemos fazer um novo lançamento de R$ 250,00 com observação de desconto, por exemplo.

### Comissões a Pagar <a id="ComissoesAPagar"></a>
Para acessar esta opção, selecione o módulo **Financeiro**, opção **Comissões a pagar**.    
Vamos filtrar nosso pedido. Clique sobre a palavra **Número** para que a pesquisa por número seja selecionada. Em nosso exemplo, informaremos no campo **Filtro** o número do nosso pedido: **00018692** e selecionaremos **Nenhum filtro**.
![pedido.exemploA23](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA23.png)
    
> Perceba que aqui temos o montante de R$ 11.250,00 de comissões a pagar do pedido.   
> Mas como chegamos a este valor?   
> O sistema fez a seguinte conta: Percentual de comissão do Representante C do total do pedido. Ou seja, (10,00% * R$ 90.000,00) / 100 = R$ 9.000,00; Percentual de comissão do Representante D do total do pedido. Ou seja, (2,50% * R$ 90.000,00) / 100 = R$ 2.250,00; Como foram 3 parcelas, temos: R$ 9.000,00 / 3 = 3 parcelas de R$ 3.000,00 para o Representante C e R$ 2.250,00 / 3 = 3 parcelas de R$ 750,00 para o Representante D.   

> Perceba que aqui o sistema poderá se comportar de duas formas, de acordo com as configurações do módulo Financeiro.   
> Se o campo **Baixar as comissões a pagar quando é baixado as comissões a receber** estiver selecionado o sistema irá fazer os lançamentos automáticos no **Comissões a pagar** a cada lançamento no **Comissões a receber**. No caso do lançamento em **Comissões a receber** for excluido, os lançamentos do **Contas a pagar** também serão.
![Configuração](https://raw.githubusercontent.com/netforcews/docs-siscom/master//financeiro/imagens/config-financeiro.geral.png)

### Não selecionado: Baixar as comissões a pagar quando é baixado as comissões a receber <a id="NaoSelecionado"></a>
Quando o sistema estiver configurado desta forma, os títulos de comissões a pagar são gerados no fechamento do pedido e os lançamentos devem ser feitos manualmnente.

#### Pagando totalmente o titulo 00018692/A <a id="NSPagandoTotalmenteOTitulo"></a>
Na tela do título **00018692/A**, **Representante C**, clique na aba **Lançamentos** e logo após na opção em **Novo**.   
![pedido.exemploA24](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA24.png)   
![pedido.exemploA25](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA25.png)   
![pedido.exemploA26](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA26.png)   

Na tela do título **00018692/A**, **Representante D**, clique na aba **Lançamentos** e logo após na opção em **Novo**.   
![pedido.exemploA27](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA27.png)   
![pedido.exemploA28](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA28.png)   
![pedido.exemploA29](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA29.png)   

> Perceba que aqui temos o Representante C e o Representante D para o titulo 00018692/A.

#### Pagando parcialmente todo o titulo 00018692/A <a id="NSPagandoParcialmenteTodoOTitulo"></a>
Na tela do título **00018692/A**, **Representante C**, clique na aba **Lançamentos** e logo após na opção em **Novo**.   
![pedido.exemploA24](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA24.png)   
![pedido.exemploA30](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA30.png)   
![pedido.exemploA34](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA34.png)   
![pedido.exemploA35](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA35.png)   

Na tela do título **00018692/A**, **Representante D**, clique na aba **Lançamentos** e logo após na opção em **Novo**.   
![pedido.exemploA27](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA27.png)   
![pedido.exemploA32](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA32.png)   
![pedido.exemploA36](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA36.png)   
![pedido.exemploA37](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA37.png)   

> Perceba que aqui temos o Representante C e o Representante D para o titulo 00018692/A. 

#### Pagando parcialmente o titulo 00018692/A <a id="NSPagandoParcialmenteOTitulo"></a>
Na tela do título **00018692/A**, **Representante C**, clique na aba **Lançamentos** e logo após na opção em **Novo**.   
![pedido.exemploA24](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA24.png)   
![pedido.exemploA30](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA30.png)   
![pedido.exemploA31](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA31.png)   

Na tela do título **00018692/A**, **Representante D**, clique na aba **Lançamentos** e logo após na opção em **Novo**.   
![pedido.exemploA27](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA27.png)   
![pedido.exemploA32](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA32.png)   
![pedido.exemploA33](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA33.png)   

> Perceba que aqui temos o Representante C e o Representante D para o titulo 00018692/A. 

### Selecionado: Baixar as comissões a pagar quando é baixado as comissões a receber <a id="Selecionado"></a>
Quando o sistema estiver configurado desta forma, os títulos de comissões a pagar são gerados no fechamento do pedido e os lançamentos são feitos de acordo com os lançamentos dos títulos de comissões a receber de forma proporcional as comissões do pedido.

#### Pagando totalmente o titulo 00018692/A <a id="SPagandoTotalmenteOTitulo"></a>
Em **Comissões a receber**, na tela do título **00018692/A**, clique na aba **Lançamentos**.   
![pedido.exemploA14](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA14.png)   
Em **Comissões a pagar**, na tela do título **00018692/A**, **Representante C**, clique na aba **Lançamentos**.   
![pedido.exemploA26](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA26.png)   
Em **Comissões a pagar**, na tela do título **00018692/A**, **Representante D**, clique na aba **Lançamentos**.   
![pedido.exemploA29](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA29.png)   

#### Pagando parcialmente todo o titulo 00018692/A <a id="SPagandoParcialmenteTodoOTitulo"></a>
Em **Comissões a receber**, na tela do título **00018692/A**, clique na aba **Lançamentos**.   
![pedido.exemploA18](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA18.png)   
Em **Comissões a pagar**, na tela do título **00018692/A**, **Representante C**, clique na aba **Lançamentos**.   
![pedido.exemploA38](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA38.png)   
Em **Comissões a pagar**, na tela do título **00018692/A**, **Representante D**, clique na aba **Lançamentos**.   
![pedido.exemploA39](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA39.png)   

#### Pagando parcialmente o titulo 00018692/A <a id="SPagandoParcialmenteOTitulo"></a>
Em **Comissões a receber**, na tela do título **00018692/A**, clique na aba **Lançamentos**.   
![pedido.exemploA20](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA20.png)   
> Podemos considerar o saldo de R$ 250,00 como perdido, podendo manter desta forma caso algum dia queiramos gerar um acerto de contas.   
<br>

Em **Comissões a pagar**, na tela do título **00018692/A**, **Representante C**, clique na aba **Lançamentos**.   
![pedido.exemploA40](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA40.png)   
Em **Comissões a pagar**, na tela do título **00018692/A**, **Representante D**, clique na aba **Lançamentos**.   
![pedido.exemploA41](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA41.png)   

Em **Comissões a receber**, na tela do título **00018692/A**, clique na aba **Lançamentos**.   
![pedido.exemploA22](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA22.png)   
> Podemos fazer um novo lançamento de R$ 250,00 com observação de desconto, por exemplo.
<br>

Em **Comissões a pagar**, na tela do título **00018692/A**, **Representante C**, clique na aba **Lançamentos**.     
![pedido.exemploA42](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA42.png)   
Em **Comissões a pagar**, na tela do título **00018692/A**, **Representante D**, clique na aba **Lançamentos**.     
![pedido.exemploA43](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA43.png)   


## Entrega parcial <a id="EntregaParcial"></a>
Se a entrega foi parcial, informe a quantidade recebida e clique em **Executar**.
![pedido.exemploA44](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA44.png)   

No momento do fechamento, o sistema irá gerar dados para o financeiro e apresentar a mensagem abaixo. 
![pedido.exemploA10](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA10.png)   

Caso ocorra a mensagem abaixo, verifique as parcelas, pois neste caso os valores não estão fechando.
![pedido.exemploA46](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA46.png)   
![pedido.exemploA47](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemploA47.png)   
Veja [aqui](#InclusaoDeParcelasDoPedido)



   
   
