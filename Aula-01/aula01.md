# Inserindo CSS no HTML <a id="css"></a>

## Há três formas de adicionar o CSS

### 1 - CSS Externo

No modo externo um arquivo separado denominado aula01.css é criado com a extensão .css, neste arquivo será inserido todos os comandos relacionados a formatação da página linkando os dois, é a forma mais recomendada.

 **Inserido no head:**

``` Html
    <head>
    <!--Tag utilizada para linkar o css-->
   
    <link rel="stylesheet" href="aula01.css">
    
    </head>
```

### 2 - CSS Incorporado

No modo incorporado o código CSS é criado dentro do próprio HTML, a tag `<style>` é a responsável.

**Inserido no head:**

``` Html
    <head>
    <!--Utilizando os seletores, propriedades e valores-->
    
    <style>
        body{
            background-color: #7affa8;
        }
        h1{
            color: #005e16;
        }
    </style>
    </head>

```

### 3 - CSS Inline

No modo inline o código css é atribuido na mesma linha de uma tag html, e só é funcional para ela mesmo.

**Inserido em Tags <>:**

``` Html
    <!--Usando a tag style na mesma tag onde se deseja aplicar o CSS-->
    
    <body style="background-color: gray;">
    
    <h1 style="color: #fff1cb;">
    
    <p style="color: #0d7cff; font-size: 16px;">
        Nunca esqueça de sempre colocar o ; em css.
    </p>
    </body>

```

---

### Dicas/Comentários

> No modo externo a formatação css afeta todas os seletores que você utiliza. <br>
> O css incorporado tem prioridade sobre o externo. <br>
> O css inline tem prioridade sobre o incorporado. <br>
> **Inline > Incorporado > Externo.** 

---

### Explicação dos atributos do link

**rel** – Esse atributo define o relacionamento entre o arquivo em que o comando está escrito e o arquivo que é definido no caminho do href. Geralmente será apenas um stylesheet se conectamos um arquivo CSS (stylesheet).

**type** – Esse atributo define o conteúdo do arquivo para qual está linkado. O valor do atributo deve ser um MIME como text/html, text/css e similares.

**href** – O atributo Href especifica a localização do arquivo que você precisa criar um link. Como você está tentando linkar um arquivo CSS, o caminho deve ser um subdiretório do CSS. Se o arquivo estiver no mesmo diretório, então você precisa inserir somente o nome do arquivo, caso não esteja você deve digitar o caminho para o diretório onde está o arquivo.
**Exemplo: C:\Usário\Sites\estilo.css.**

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
