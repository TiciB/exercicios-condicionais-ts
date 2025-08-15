# Exercício 7

## Nome para exibição

Considerando que uma pessoa pode ter nome, sobrenome e/ou apelido, crie um código que imprima o nome da pessoa no console, seguindo esta ordem de prioridade:

- Apelido: Se a variável apelido estiver preenchida, imprima apenas o seu valor.
- Nome e Sobrenome: Se a variável apelido não estiver preenchida, verifique se o nome e sobrenome existem.
- Se o nome e sobrenome estiverem preenchidos, imprima o primeiroNome seguido de um espaço e o sobrenome.
- Se apenas o nome estiver preenchido, imprima apenas o primeiroNome.
- Se o apelido, nome e sobrenome estiverem preenchidos, apenas o apelido deve ser impresso.

Observação: É obrigatório o preenchimento do nome (primeiroNome).


#### Exemplo 1: primeiro nome:

```javascript
const primeiroNome = "Mario";
const sobrenome = "";
const apelido = "";

//seu código aqui
```

Para o exemplo acima, deverá ser impresso no console apenas:

```
Mario
```


#### Exemplo 2: apelido:

```javascript
const primeiroNome = "Mario";
const sobrenome = "";
const apelido = "Bros";

//seu código aqui
```

Para o exemplo acima, deverá ser impresso no console apenas:

```
Bros
```

#### Exemplo 3: com sobrenome:

```javascript
const primeiroNome = "Mario";
const sobrenome = "Bros";
const apelido = "";

//seu código aqui
```

Para o exemplo acima, deverá ser impresso no console apenas:

```
Mario Bros
```
