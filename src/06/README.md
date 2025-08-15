# Exercício 06

## Compra com Desconto

A Loja do Juninho está com uma super promoção. Na compra de qualquer produto você ganha desconto conforme a forma de pagamento seguindo a tabela seguinte.

| Forma de Pagamento | Desconto |
| ------------------ | -------- |
| Débito            | 5%       |
| Crédito             | 3%       |
| Pix ou Dinheiro | 10%      |

Faça um programa que verifica o tipo de desconto, calcule o valor do produto com o desconto e imprima o resultado. O valor final do produto após o desconto pode ser encontrado com a fórmula:

$$ valorFinal = valorDoProduto - (valorDoProduto \* desconto)$$

Ao imprimir o valor, limite as casas decimais a apenas duas casas (ex: 12.50)

```javascript
//tipo de pagamento (dinheiro, credito, debito, pix)
const tipoDePagamento = "credito";

//valor da mercadoria (centavos)
const valorDoProduto = 13000;
```

Para o exemplo acima, o valor final é:

$$ valorFinal = 13000 - (13000\*0.05)$$

$$ valorFinal = 12350$$

O programa deve exibir na tela:

```
Valor a ser pago: R$123.50
```

Teste seu programa para outras entradas.

