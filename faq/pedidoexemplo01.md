# PEDIDO: EXEMPLO
Abaixo segue um processo completo de pedido.
   
## 1. Inclusão do pedido
Para acessar esta opção, selecione o módulo **Vendas**, opção **Geral**, opção **Pedidos** e logo após clique na opção **Novo**.
![pedido.exemplo01.1](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemplo01.0.png)
   
Informaremos dois representantes: Representante C com 10% de comissão e Representante D com 2,5% de comissão, totalizando 12,5% de comissão.
![pedido.exemplo01.1](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemplo01.1.png)
   
## 2. Inclusão de referências (itens) do pedido
Na tela do pedido, clique em **Referências**.
Informaremos um valor e quantidade que nos resultem um montante final de R$ 90.000,00.   
![pedido.exemplo01.2](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemplo01.2.png)
![pedido.exemplo01.3](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemplo01.3.png)
   
## 3. Inclusão de parcelas do pedido
Na tela do pedido clique em **Parcelas** e logo após em **Gerar parcelas**.
Como informamos a condição de pagamento **30/60/90 Dias**, o sistema irá gerar 3 parcelas.
![pedido.exemplo01.4](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemplo01.4.png)
![pedido.exemplo01.5](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemplo01.5.png)

> Perceba que a configuração da condição de pagamento está 33,34% para 30 dias, 33,33% para 60 dias e 33,33% para 90 dias.   
   
![pedido.exemplo01.6](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemplo01.6.png)
   
Em nosso exemplo, iremos alterar os valores de cada uma das parcelas arredondando-as e a data do vencimento para o primeiro dia do mês. 

> Perceba que alteramos o número de dias para mudar o vencimento.

![pedido.exemplo01.7](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemplo01.7.png)
   
Ao final, teremos as seguintes informações:
![pedido.exemplo01.8](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemplo01.8.png)
   
## 4. Fechando o pedido
Na tela do pedido clique em **Comandos** e selecione a opção **Fechar pedido**.
![pedido.exemplo01.9](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemplo01.9.png)
   
Informe o número da nota fiscal e a data de faturamento.
   
## 5. Entrega total
Se a entrega for total (100%), mantenha as quantidades e clique em **Executar**.
![pedido.exemplo01.9](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemplo01.9.png)
   
No momento do fechamento, o sistema irá gerar dados para o financeiro e apresentar a mensagem abaixo.
![pedido.exemplo01.10](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemplo01.10.png)
    
### 5.1. Comissões a Receber
Para acessar esta opção, selecione o módulo **Financeiro**, opção **Comissões a receber**.    
Vamos filtrar nosso pedido. Clique sobre a palavra **Número** para que a pesquisa por número seja selecionada. Em nosso exemplo, informaremos no campo **Filtro** o número do nosso pedido: **00018692** e selecionaremos **Nenhum filtro**.
![pedido.exemplo01.11](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemplo01.11.png)
    
> Perceba que aqui temos o montante de R$ 11.250,00 de comissões a receber do pedido.   
> Mas como chegamos a este valor?   
> O sistema fez a seguinte conta: (Percentual de comissão do Representante C + Percentual de comissão do Representante D) do total do pedido. Ou seja, ((10,00 + 2,5) * 90000) / 100 = 11250; Como foram 3 parcelas, temos: 11250 / 3 = 3750. 
    
#### 5.1.1. Recebendo totalmente o titulo 00018692/A
Na tela do título **00018692/A**, clique na aba **Lançamentos** e logo após na opção em **Novo**.
![pedido.exemplo01.12](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemplo01.12.png)
![pedido.exemplo01.13](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemplo01.13.png)
![pedido.exemplo01.14](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemplo01.13.png)

#### 5.1.2. Recebendo parcialmente todo titulo 00018692/A
Na tela do título **00018692/A**, clique na aba **Lançamentos** e logo após na opção em **Novo**.
![pedido.exemplo01.12](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemplo01.12.png)
![pedido.exemplo01.15](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemplo01.15.png)
Foi recebido R$ 2.000,00. Restando um saldo de R$ 1.750,00.
![pedido.exemplo01.16](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemplo01.16.png)
Foi recebido mais R$ 1.000,00, totalizando R$ 3.000,00 recebidos. Restando um saldo de R$ 750,00.
![pedido.exemplo01.17](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemplo01.17.png)
Foi recebido mais R$ 750,00, totalizando R$ 3.750,00 recebidos. 
![pedido.exemplo01.18](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemplo01.18.png)

### 5.1.3. Recebendo parcialmente parte do título 00018692/A
Na tela do título **00018692/A**, clique na aba **Lançamentos** e logo após na opção em **Novo**.
![pedido.exemplo01.12](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemplo01.12.png)
![pedido.exemplo01.15](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemplo01.15.png)
Foi recebido R$ 2.000,00. Restando um saldo de R$ 1.750,00.
![pedido.exemplo01.16](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemplo01.16.png)
Foi recebido mais R$ 1.000,00, totalizando R$ 3.000,00 recebidos. Restando um saldo de R$ 750,00.
![pedido.exemplo01.19](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemplo01.19.png)
Foi recebido mais R$ 500,00, totalizando R$ 3.500,00 recebidos. Restando um saldo de R$ 250,00.
<br>

![pedido.exemplo01.20](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemplo01.20.png)
> Podemos considerar o saldo de R$ 250,00 como perdido, podendo manter desta forma caso algum dia queiramos gerar um acerto de contas.

![pedido.exemplo01.21](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemplo01.21.png)
![pedido.exemplo01.22](https://raw.githubusercontent.com/netforcews/docs-siscom/master/faq/imagens/pedido.exemplo01.22.png)
> Podemos fazer um novo lançamento de R$ 250,00 com observação de desconto, por exemplo.








O título é de R$ 3.750,00 e podemos recebê-lo totalmente ou parcialmente, bastando para isso alterar o valor e fazendo vários lançamentos. O sistema tornará o título quitado quando a soma dos valores a receber totalizar R$ 3.750,00.
    
### 5.2. Comissões a Pagar
Para acessar esta opção, selecione o módulo **Financeiro**, opção **Comissões a pagar** e clique na opção **novo**.
   
   
## 6. Entrega parcial
Se a entrega foi parcial, informe a quantidade recebida e clique em **Executar**.
   
   
