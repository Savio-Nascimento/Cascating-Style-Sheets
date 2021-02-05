# Seletores CSS <a id="css"></a>

## Como escrever um código em CSS

---

<div align="center">
    
### Sintaxe básica

``` css
    seletor{
        propriedade: valor;
    }

```

Para escrever o código CSS é necessário seguir a sintaxe, que define a forma com que o estilo será aplicado aos elementos html.

</div>

#### Seletor

O seletor é o **elemento** html ao qual se quer aplicar o css por exemplo: Div, Body, P.

#### Propriedade

A propriedade é o **atributo** do elemento que será aplicado o css por exemplo: Color, Font, Position.

#### Valor

O valor é a **característica** que o elemento irá assumir por exemplo: cor azul, tamanho 14 para a fonte.

### Exemplo:

``` css
    body{
        background-color:yellow;
    }

```

---

## Adicionando múltiplos elementos

Você também pode selecionar vários tipos de elementos e aplicar um único conjunto de regras a todos eles. Inclua múltiplos elementos separados por **vírgulas**. Por exemplo:

``` css
    p,h1,div{
        color:red;
    }

```

---

## Adicionando múltiplos atributos

É possivel adicionar mais de uma propriedade por seletor, basta separar suas declaracões com o **;** exemplo:

``` css
    h1{
        color:red;
        font-size: 16px;
        text-align: center;
    }
```

---

## Adicionando Ids

As ids são uma forma de identificar um elemento, e devem ser **únicas** para cada elemento. É como se fossem impressões digitais de nossos dedos ou nosso CPF. Através delas, pode-se atribuir formatação a um elemento em especial. Exemplo:

``` css
    #p1{
        color:blue;
    }

    #p2{
        color:green;
    }

```

Para indicar que o seletor será para um id basta colocar o o caractere hash **#** antes do **nome do id.**

---

## Adicionando Class

As classes são uma forma de identificar um grupo de elementos. Através delas, pode-se atribuir uma formatação a **vários** elementos de uma vez. Exemplo:

``` css
    .class01{
        color:blueviolet;
        font-size: 30px;
    }
    

```
Para identificar este seletor, basta usar um ponto **.** antes do **nome da classe.**

---

### Dicas/Comentários



* Cada linha de comando deve ser envolvida em chaves **{}**.
* Dentro de cada declaração, você deve usar dois pontos **:** para separar a propriedade de seus valores.
* Dentro de cada conjunto de regras, você deve usar um ponto e vírgula **;** para separar cada declaração da próxima.

---

<div align="center">

### Para conhecer mais seletores de Css <br>

#### Acesse uma tabela de referência com todos os seletores css [Tabela](https://tableless.com.br/referencia-seletores-css/) 

</div>

---

<div align="center">

### ⚠️Atenção⚠️

#### Acesse o html e o css dessa aula para ver de forma prática o que você estudou 😁 <br>

#### Baixe os códigos da aula e veja você mesmo👻

</div>

---

### 👤 Author

[![Github Badge](https://img.shields.io/badge/SavioNascimento-24292e?style=flat&logo=Github&logoColor=white&link=https://github.com/Savio-Nascimento)](https://github.com/Savio-Nascimento)

---

[⬆️ Topo](#css) <br>

[🏠 Home](https://github.com/Savio-Nascimento/Cascating-Style-Sheets)

