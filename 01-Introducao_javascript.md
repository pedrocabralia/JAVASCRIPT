# O que é e para que serve o JavaScript

* Uma linguagem de programação que permite implementar interatividade nas páginas Web. 

* Exemplo exemplo1.html.

* No exemplo acima, o código javascript reagiu  a um "evento" que foi o clique no botão.


* Com javascript podemos utilizar Apis(nos aprofundaremos em breve)
* Apis são conjuntos prontos de construção de códigos.(como se fosse um kit de móveis prontos)

Algumas Apis:

 * A API DOM (Document Object Model) permite que você manipule HTML e CSS, criando, removendo e alterando HTML, aplicando dinamicamente novos estilos à sua página, etc. Toda vez que você vê uma janela pop-up aparecer em uma página, ou algum novo conteúdo exibido (como vimos acima em nossa demonstração simples), por exemplo, esse é o DOM em ação.


 *  A API de Geolocalização recupera informações geográficas. É assim que o Google Maps consegue encontrar sua localização e plotá-la em um mapa.

 * As APIs Canvas e WebGL permitem que você crie gráficos animados 2D e 3D. Ex.:  [Exemplo](https://webglsamples.org/)


 * APIs de áudio e vídeo como WebRTCHTMLMediaElement permitem que você faça coisas realmente interessantes com multimídia, como reproduzir áudio e vídeo diretamente em uma página da web ou capturar vídeos da sua webcam e exibi-los no computador de outra pessoa .
 ex.: https://chrisdavidmills.github.io/snapshot/ 
 


* A API do Twitter permite que você faça coisas como exibir seus tweets mais recentes em seu site.

* A API do Google Maps e a API do OpenStreetMap permitem que você incorpore mapas personalizados em seu site, além de outras funcionalidades semelhantes.


## Como adicionar Javascript no html?

* Javascript interno:

```html
        <script>
        // JavaScript vai aqui
        </script>
```
* Javascript externo(que pode ser adicionado no head ou no final do body):

```html
<script  src="script.js"></script>
```


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


