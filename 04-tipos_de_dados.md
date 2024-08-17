# Tipos de dados

*  Lembrando que Javascript é dinamicamente tipadas ou seja, existem tipos de dados porém as variáveis não estão vinculadas a nenhum deles. 
    * Ex.:
        ```javascript 
                // no error
                let message = "hello";
                message = 123456;
        ```

* Em javascript temos 8 tipos de dados básicos:

   1. **Number:** Representa números, tanto inteiros quanto de ponto flutuante. 
   
        * Exemplo: 
        ```js
            let x = 42;
            let y = 3.14;
        ```
        * Existem também alguns valores especiais: **Infinity, -Infinity e NaN**.
        * **Infinity:** é um valor especial que é maior que qualquer número, podemos obter ele em uma divisão por 0, ex.:
        ```js
            alert( 1 / 0 ); // Infinity

        ```

        * **NaN:** Representa um erro computacional é o resultado de uma operação matemática incorreta ou indefinida, ex.:
        ```js
             
            alert( "not a number" / 2 );

            //qualque operação com um NaN o resultado é NaN  
            alert( NaN + 1 ); // NaN
            alert( 3 * NaN ); // NaN
            alert( "not a number" / 2 - 1 ); // NaN

            // Há apenas uma excessão:
            NaN ** 0
            // dá 1
        ```


    2. **String**: Representa uma sequência de caracteres, ou seja, texto.
    As strings podem ser delimitadas por aspas simples ('), aspas duplas ("), ou crases (``).
        * Exemplo: 
        ```js
           let nome = "Alice";
           let mensagem = 'Olá, mundo!';
           let outroNome = `Hello`;
           alert( `Hello, ${name}!` ); // Hello, John!
        ```
        

    3. **Boolean**: Representa um valor lógico que pode ser verdadeiro (true) ou falso (false).
        * Exemplo: 
        ```js
               let ativo = true;, let completado = false;
        ```
    4. **Undefined**: 
Representa um valor que ainda não foi definido. Se você declarar uma variável sem atribuir um valor a ela, o valor padrão será undefined.
        * Exemplo:
         ```js
            let valor; 
            \\(a variável valor é undefined)
         ```
    5. **Null**:
Representa a ausência intencional de qualquer valor de objeto. É usado para indicar que uma variável não tem valor.
        * Exemplo: 
        ```js
        let obj = null;
        ``` 
    6. **Symbol**:
Representa um valor único e imutável que pode ser usado como identificador para propriedades de objetos. Cada Symbol é único.
         * Exemplo:
         ```js
          let id = Symbol('id');
        ```
    7. **BigInt**:
Representa números inteiros de precisão arbitrária. É usado para trabalhar com números maiores do que o limite do tipo Number.
        * Exemplo: 
        ```js
        let grandeNumero = 123456789012345678901234567890n;
        ```
    8. **Object**
Embora não seja um tipo de dado primitivo, Object é um tipo fundamental que pode armazenar coleções de dados e mais complexos valores.
        * Exemplo:
            ```javascript
            let pessoa = {
                nome: "Alice",
                idade: 30
            };
            ```
* Se quisermos saber qual é o tipo de uma variável, utilizamos o **typeof**.

```js
typeof undefined // "undefined"

typeof 0 // "number"

typeof 10n // "bigint"

typeof true // "boolean"

typeof "foo" // "string"

typeof Symbol("id") // "symbol"

typeof Math // "object"  (1)

typeof null // "object"  (2)

typeof alert // "function"  (3) 
```
## Referências:
[Tipos de dados](https://javascript.info/types)