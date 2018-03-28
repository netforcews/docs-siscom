# ENVIAR PEDIDOS POR E-MAIL DE FORMA AUTOMÁTICA
É possível enviar pedidos por e-mail através do sistema de forma automática. Abaixo segue os passos para configurar e enviá-los.

## Passo 1 - Configuração do módulo de vendas
Veja [aqui](/vendas/config-vendas.md) como configurar para que o pedido seja colocado na fila de saída de e-mail automaticamente. 

## Passo 2 - Condições do pedido
Para quer um pedido esteja em condições para ser enviado por e-mail automaticamente, as seguintes condições devem ser respeitadas:
## a) o pedido precisa estar com o campo **Estado** igual a Fechado. Veja [aqui](/vendas/pedidovenda#geral);
## b) o cliente do pedido precisa estar com o campo **Situação** igual a Ativo. Veja [aqui](/cadastros/pessoa#configuracoes);
## c) o cliente do pedido precisa possuir pelo menos um contato com o campo **Aatribuição** igual a Compras com e-mail. Veja [aqui](http://siscom.leiame.org/master/geral/pessoacontatos.md);
## d) o fornecedor do pedido precisa estar com o campo **Situação** igual a Ativo. Veja [aqui](/cadastros/pessoa#configuracoes);
## e) o fornecedor do pedido precisa possuir pelo menos um contato com o campo **Aatribuição** igual a Compras com e-mail. Veja [aqui](http://siscom.leiame.org/master/geral/pessoacontatos.md);
## f) a última alteração do pedido deve ter ocorrido após um tempo (em minutos) configurado no **Passo 1**;
## g) o campo **Pedido enviado por e-mail cliente/fornecedor** deve estar desmarcado. Veja [aqui](/vendas/pedidovenda#geral).

## Passo 3 - Envio do pedido por e-mail
Quando é feita uma tentativa de envio do e-mail e o sistema consegue enviá-lo, o e-mail sai da fila de saída com filtro **Não Enviados** e seleciona automaticamente o campo **Pedido enviado por e-mail cliente/fornecedor**. Veja [aqui](/vendas/pedidovenda#geral).
Se houver a necessidade de reenviar este pedido, por um problema no envio ou qualquer outra razão, basta desmarcar o campo **Pedido enviado por e-mail cliente/fornecedor**. Veja [aqui](/vendas/pedidovenda#geral).


