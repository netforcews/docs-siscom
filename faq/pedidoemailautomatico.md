# ENVIAR PEDIDOS POR E-MAIL DE FORMA AUTOMÁTICA
É possível enviar pedidos por e-mail através do sistema de forma automática. Abaixo segue os passos para configurar e enviá-los.

## Passo 1 - Configuração do módulo de vendas
Veja [aqui](/vendas/config-vendas.md) como configurar para que o pedido seja colocado na fila de saída de e-mail automaticamente. 

## Passo 2 - Condições do pedido
Para quer um pedido esteja em condições para ser enviado por e-mail automaticamente, as seguintes condições devem ser respeitadas:
## a) o pedido precisa estar fechado;
## b) o cliente do pedido precisa estar ativo;
## c) o cliente precisa possuir pelo menos um contato comercial com e-mail;
## d) o fornecedor do pedido precisa estar ativo;
## e) o fornecedor precisa possuir pelo menos um contato comercial com e-mail;
## f) a última alteração do pedido deve ter ocorrido após o tempo (em minutos) configurado na aba avisso por e-mail (Passo1);
## g) o campo Pedido enviado por e-mail cliente/fornecedor da aba Geral de pedidos deve estar desmarcado.

## Passo 3 - Envio do pedido por e-mail
Quando é feita uma tentativa de envio do e-mail e o sistema consegue enviá-lo, o e-mail sai da fila de saída com filtro "Não Enviados" e seleciona automaticamente o campo Pedido enviado por e-mail cliente/fornecedor d aba Geral de pedidos.
Se houver a necessidade de reenviar este pedido, por um problema no envio ou qualquer outra razão, basta desmarcar o campo Pedido enviado por e-mail cliente/fornecedor d aba Geral de pedidos.


