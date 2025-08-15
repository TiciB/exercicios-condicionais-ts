# Exercício 05

## Montanha Russa Muito Assustadora

Você está desenvolvendo o sistema de acesso para a **Montanha Russa Muito Assustadora**. As regras para permitir ou negar a entrada de usuários são as seguintes:

**Requisitos de Acesso:**
- Idade: Pessoas entre 12 e 65 anos (inclusive).
- Saúde: Não podem ter patologias cardíacas.
- Altura: Devem ter no mínimo 150cm.

Se a pessoa não cumprir qualquer um desses requisitos, o sistema deve imprimir "ACESSO NEGADO".

Regras de Preço:

**Para quem tem acesso permitido, o valor do ingresso é:**
- R$ 10,00 (meia-entrada) para estudantes ou menores de 18 anos.
- R$ 20,00 para os demais casos.

Seu papel é imprimir na tela:

- **ACESSO NEGADO** caso a pessoa não possa brincar
- **10 reais** caso esse seja o valor que a pessoa deve pagar para brincar
- **20 reais** caso esse seja o valor que a pessoa deve pagar para brincar

```javascript
const idade = 18;
const possuiPatologia = false;
const altura = 180;
const ehEstudante = false;
```

Para este exemplo a resposta correta é `20 reais`

Lembre-se de testar seu código para outras variações de entrada.
