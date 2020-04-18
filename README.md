# Tutorial de Markdown

Este tutorial foi criado baseado na videoaula ["Como criar um README"](https://www.youtube.com/watch?v=Gcb60rPbnKA) da [Daniele Leão Evangelista](https://www.youtube.com/channel/UCBGMloQoUV3BA1-ht9Qbcvg). 

Na videoaula, ela ensina a criar o [README](https://github.com/danileao/rocketmusic) do projeto que desenvolveu durante seu [curso Bootcamp GoStack](https://github.com/danileao/rocketmusic).

A videoaula ficou excelente! Recomendo para quem não conhece markdown ou não tem muita experiência em criar README. 

Quis contribuir com um material escrito para ser utilizado como referência (famoso control-C, Control-V) e dar mais algumas dicas de forma a complementar ;)

## Editor
Existem diversos editores que você pode utilizar para criar um README, tais como:

- [Notepad++](https://notepad-plus-plus.org)
- [Notepadqq](https://notepadqq.com/s)
- [Visual Studio Code](https://code.visualstudio.com)

Uma dica, caso você esteja utilizando o Visual Studio Code, é habilitar o preview do seu README durante a edição. Assim você consegue ver como está ficando, enquanto altera o arquivo.

Basta clicar no canto superior direito, no ícone onde ao posicionar o mouse em cima, aparece "Open Preview to the Side".

## Como inserir uma imagem

Imagem localizada em algum site: utilizar a sintaxe de html

```html
<img src="https://ik.imagekit.io/wmdxyyoe83/logo2_wkzFleEF6_-uxaxxgq0.png">
```

O resultado será:

<img src="https://ik.imagekit.io/wmdxyyoe83/logo2_wkzFleEF6_-uxaxxgq0.png">

Podemos alinhar de forma centralizada:

```html
<h1 align="center">
    <img src="https://ik.imagekit.io/wmdxyyoe83/logo2_wkzFleEF6_-uxaxxgq0.png">
</h1>
```

O resultado será:

<h1 align="center">
    <img src="https://ik.imagekit.io/wmdxyyoe83/logo2_wkzFleEF6_-uxaxxgq0.png">
</h1>
 
Caso a imagem esteja localizada dentro de um diretório no projeto: 

```html
<h1 align="center">
    <img src="public/apresentacao.gif">
</h1>

```
O resultado será:

<h1 align="center">
    <img src="public/apresentacao.gif">
</h1>

Sim, é possível adicionar um gif com o preview/apresentação da sua aplicação!

## Como criar um gif

O gif nada mais é, que uma sequência de imagens que serão exibidas em uma ordem e duração que você define.

Selecione as imagens que irão aparecer no gif. 

Realize o upload para algum serviço online que faça geração de gif (nas "Referências" é possível consultar algumas indicações de sites e também um passo a passo). 

## Como criar títulos

```
# Título com hashtag
```
O resultado será:

# Título com hashtag

Atenção: é obrigatório o espaço após o sinal de hashtag (#)

É possível utilizar até 6 hashtags consecutivas para obter tamanhos menores de fonte. Quanto mais #, menor será a fonte:

## Título com 2 hashtags
### Título com 3 hashtags
#### Título com 4 hashtags
##### Título com 5 hashtags
###### Título com 6 hashtags

## Como incluir negrito
```
O que é importante pode ficar em **negrito**.
```
O resultado será:

O que é importante pode ficar em **negrito**.

## Como adicionar emoji

No Visual Studio Code, instale a extensão [Emoji Snippets](https://marketplace.visualstudio.com/items?itemName=devzstudio.emoji-snippets) a partir do menu "View \ Extensions". 

Pesquise pelo nome da extensão e clique em "Install".

Para inserir um emoji, digite : (dois pontos) e depois control + espaço. 

Para facilitar a busca, digite o nome do emoji na lista apresentada. 

Quando localizar o emoji desejado, clique em cima ou aperte enter.

Alguns exemplos:

```:lemon``` 🍋 

```:slice-of-pizza``` 🍕 

```:dog``` 🐕 

## Como criar lista

Utilize hífen seguido de espaço e o texto de cada item.

```
- Item 1
- Item 2
- Item 3
```

O resultado será:
- Item 1
- Item 2
- Item 3

## Como criar link

O texto que irá aparecer deve ficar entre colchetes e a url entre parênteses.

Não pode haver espaço entre o "fecha colchetes" e o "abre parênteses".

```
[Java](https://www.java.com/pt_BR/download/)
```
O resultado será:

[Java](https://www.java.com/pt_BR/download/)


## Como incluir trechos de código-fonte

O trecho de código deve ficar entre três crases.
```
    ```
    <tag></tag>
    ```
```

O resultado será:

```
<tag></tag>
```

Para que as palavras chaves da linguagem fiquem em destaque, defina a linguagem:
```
    ```js
    var nome = "Fulano";
    ```
```

 O resultado será:
```js
var nome = "Fulano";
```

 Exemplo com ```python``` (troque onde diz js pela palavra python):
```python
s = "Python"
print s
```

 Exemplo com ```bash``` (troque onde diz js pela palavra bash):

```bash
# Clonar o repositório
$ git clone https://github.com/danileao/rocketmusic

# Entrar no diretório
$ cd rocketmusic

# Instalar as dependências
$ yarn install

# Iniciar o projeto
$ yarn start
```

Consulte outras linguagens:
 - https://support.codebasehq.com/articles/tips-tricks/syntax-highlighting-in-markdown
 

## Como separar as seções

Adicione três traços antes da seção que conterá o traço.

```
### Seção 1
---
### Seção 2
```
O resultado será:

### Seção 1
---
### Seção 2

## Como criar um índice

```
- [Tutorial de Markdown](#tutorial-de-markdown)
- [Como inserir uma imagem](#como-inserir-uma-imagem)
```

O resultado será:

- [Tutorial de Markdown](#tutorial-de-markdown)
- [Como inserir uma imagem](#como-inserir-uma-imagem)

É semelhante a forma que criamos um link: onde colocamos o texto a ser exibido entre colchetes e a url entre parênteses.

A diferença é que, entre parênteses, deve conter uma hashtag, seguida do texto da seção onde quer criar a âncora (link para o próprio documento). Este texto não deve conter espaços, apenas hífen entre as palavras.

## Editor online para criar README
- https://www.makeareadme.com

## Alguns templates de README

- https://gist.github.com/PurpleBooth/109311bb0361f32d87a2

- https://gist.github.com/fvcproductions/1bfc2d4aecb01a834b46

## Referências

- Videoaula da Daniele Leão Evangelista de "Como criar um README": https://www.youtube.com/watch?v=Gcb60rPbnKA

- Github do projeto da Daniele Leão Evangelista:
https://github.com/danileao/rocketmusic


- Link da documentação do Markdown:
https://daringfireball.net/projects/markdown

- Mastering Markdown:
https://guides.github.com/features/mastering-markdown/

- Site para realizar upload de imagens:
https://imagekit.io/dashboard#media-library

- Sites para geração de gif:
    - Gifmaker: https://gifmaker.me
    - Giphy: https://giphy.com
    - Make a Gif: https://makeagif.com
    - Imgflip: https://imgflip.com
    - Ezgif: https://ezgif.com

- Como criar um gif animado: https://www.techtudo.com.br/dicas-e-tutoriais/noticia/2016/02/como-criar-um-gif-animado.html

- Extensão "Emoji Snippets" (Devzstudio) para o Visual Studio Code: https://marketplace.visualstudio.com/items?itemName=devzstudio.emoji-snippets

