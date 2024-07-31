# Como executar código JavaScript?
* Uma das formas é por meio do navegador.
* E também pelo Nodejs.

* A maneira mais simples:

```html
    <!DOCTYPE html>
    <html>
        <head>
            <meta charset="UTF-8">
            <title>Page Title</title>
        </head>
        <body>
            <script>
                // Your JavaScript goes here!
                console.log("Hello, World!")
            </script>
        </body>
    </html>
```
* Para ver esse código temos que abrir o console do navegador por meio do inspect ou inspect Element.

* Outra forma é vincular um arquivo externo:

```html
  <script src="javascript.js"></script>
```

# Variáveis 

* Lembrando que variáveis podem ser consideradas como "containers" ou "caixas"  de armazenamento de dados para seu códigos.

![](img/variaveis.png)
[Fonte: Odin Project](https://www.theodinproject.com/lessons/foundations-variables-and-operators#variables)

* Existem três formas de declarar variáveis em js:
    * **var**: é uma forma mais antiga de declarar variáveis no javascript.  O var ele é de escopo geral, o que significa que ele é visto em todo o código mesmo que tenha sido declarado em um escopo local. alguns exemplos:

    ```javascript
                    
            if (true) {
                var test = true; 
             }
            console.log(test);
    ```
    * Se usássemos o mesmo exemplo acima, só que colocando o let, retornaria uma erro.

    * Agora se o var estiver dentro de uma função o escopo dela será apenas a função:
    ```js
        function sayHi() {
        if (true) {
            var phrase = "Hello";
        }

        alert(phrase); // works
        }

        sayHi();
        alert(phrase); // ReferenceError: phrase is not defined
    ```

    * Se declararmos duas variáveis com o mesmo nome com o var, ele aceita:

    ```js
        var user = "Pete";

        var user = "John"; 

        alert(user); // John


    ```
 * Já com o let dá erro:

    ```js
        let user = "Pete";

        let user = "John"; 

        alert(user); // SyntaxError: 'user' has already been declared


    ```

    * const: Use const para variáveis com escopo de bloco cujo valor não deve ser reatribuído.

    ***let é  a maneira mais utilizada.***
## Números

# Exercícios:

* Experimente os seguintes exercícios (e não se esqueça de usar console.log()!):

* Adicione 2 números juntos! (basta digitar console.log(23 + 97) no seu arquivo HTML).

*  Adicione uma sequência de 6 números diferentes.

* Imprima o valor da seguinte expressão:(4 + 6 + 9) / 77
A resposta deve ser aproximadamente 0.24675

## Vamos usar variáveis!
*  Digite esta declaração no topo da tag de script:let a = 10
* No console console.log(a) deve imprimir 10
*  Tente o seguinte no console:9 * a
e isto: let b = 7 * a (retorna undefined*) e então console.log(b)

* Declare uma variável constante MAX com o valor 57.
* Defina outra variável actualpara MAX - 13.
*  Defina outra variável percentage para actual / MAX
* Se você digitar percentage no console e pressionar Enter, deverá ver um valor como 0.7719
# Ler
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript

https://www.w3schools.com/js/js_arithmetic.asp 

https://www.w3schools.com/js/js_numbers.asp

https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Math

https://javascript.info/operators 


https://javascript.info/variables
 
 TESTE
