# EFETUAR BAIXA COLETIVA
<br>

## Geral
![financeiro-baixa-coletiva.geral](https://raw.githubusercontent.com/netforcews/docs-siscom/master/geral/imagens/financeiro-baixa-coletiva.geral.png)

Campo | Descrição
--:|---
**Data Pagto** | Informe a data do pagamento. Por padrão, este campo é obrigatório.
**Valor Pago** | Informe o valor pago. Por padrão, este campo é obrigatório.
**Conta** | Selecione a conta. Por padrão, este campo é obrigatório.
**Conta Contábil** | Selecione a conta contábil. Por padrão, este campo é obrigatório.
**Observação** | Informe uma observação.
**Baixar proporcional** | Selecione se deve baixar proporcional.
<br>

## Detalhes
### Baixar Não Proporcional
Se selecionarmos 5 títulos para baixar, totalizando R$ 5.000,00 (R$ 1.000,00 cada título), e ao informarmos R$ 5.000,00 no valor total da baixa (100% sugerido pelo sistema), o sistema fará baixa de todos os títulos.
Se selecionarmos 5 títulos para baixar, totalizando R$ 5.000,00 (R$ 1.000,00 cada título), e ao informarmos R$ 2.500,00 no valor total da baixa, o sistema fará baixa total do primeiro e segundo título de R$ 1.000,00, o terceiro título fará uma baixa parcial de R$ 500,00 e não fará baixa do quarto e quinto título.
### Baixar Proporcional
Se selecionarmos 5 títulos para baixar, totalizando R$ 5.000,00 (R$ 1.000,00 cada título), e ao informarmos R$ 5.000,00 no valor total da baixa, o sistema entenderá que deverá baixar 100% proporcional de cada título, fazendo a baixa total de 100% do valor de cada título selecionado, neste exemplo R$ 1.000,00.
Se selecionarmos 5 títulos para baixar, totalizando R$ 5.000,00 (R$ 1.000,00 cada título), e ao informarmos R$ 2.500,00 no valor total da baixa, o sistema entenderá que deverá baixar 50% proporcional de cada título, fazendo a baixa parcial de 50% do valor de cada título selecionado, neste exemplo R$ 500,00.
<br>
<br>
<br>
<br>

```FORM:FINANCEIRO_BAIXA_COLETIVA```
