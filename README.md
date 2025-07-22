## ⚠ Repositório dedicado a práticas e estudos com HTML.

# HTML (HyperText Markup Language)

<p align="justify">
    HTML é uma linguagem de marcação padrão utilizada para criar e estruturar páginas web. Sua principal função é estabelecer a infraestrutura base do site, definindo a organização e o conteúdo. Isto inclui, textos, imagens, links, dentre outros aspectos.
</p>

A princípio, HTML é composto por **tags**, **elementos**, e **atributos**.

<br>

> **Tags**

<p align="justify">
    Em HTML, as tags referem-se a elementos de marcação que indicam ao <strong>navegador</strong> como o conteúdo deve ser exibido na página web. Elas atuam e funcionam como etiquetas que definem a estrutura e o tipo dos elementos. Isto é, parágrafos, títulos, subtítulos, imagens, links e etc.
</p>

<p align="justify">
    <strong>Exemplo(s):</strong> <strong>&lt;p&gt;</strong><br><br>Neste caso, a tag indica ao navegador que a partir dali <strong>começará</strong> um parágrafo de texto. Dessa forma, para delimitar o conteúdo que estará adentro do parágrafo torna-se necessário de utilizar uma <strong>tag de fechamento</strong>, cuja representação se dá pela seguinte forma: <strong>&lt;/p&gt;</strong>
</p>

<p>
    <strong>Exemplo(s):</strong> <strong>&lt;p&gt;</strong>Hello, World!<strong>&lt;/p&gt;</strong>
</p>

<br>

> **Elementos**

<p align="justify">
    Em HTML, os Elementos referem-se ao conjunto das tags de abertura, fechamento, e o seu respectivo conteúdo adentro da estrutura.
</p>

<p align="justify">
    <strong>Exemplo(s):</strong> <strong>&lt;p&gt;Olá, Mundo!&lt;/p&gt;</strong><br><br>Neste caso, esse é um <strong>elemento de parágrafo completo</strong>, cujo é interpretado pelo navegador e então exibe um texto na tela.
</p>

<br>

> **Atributos**

<p align="justify">
    Em HTML, os atributos referem-se a <strong>comandos adicionais</strong> que podem ser aderidas a <strong>tag de abertura</strong> com o intuito de <strong>adicionar informações extras aos elementos</strong>. 
</p>

<p align="justify">
    <strong>Exemplo(s):</strong> &lt;img <strong>src="foto.png alt ="Foto"</strong>&gt;<br><br>Neste caso, tanto "src", quanto "alt" são atributos da tag &lt;img&gt;. Nesse sentido, o atributo <strong>src="foto.png"</strong>, refere-se a um atributo aderido a tag de img cujo <strong>informa qual imagem o elemento deve demonstrar</strong>. Já o atributo <strong>alt="Foto"</strong> reponsabiliza-se por exibir um <strong>texto alternativo</strong> para caso a imagem não carregue.
</p>

---

<br>

> **Estrutura Básica do HTML**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```
<br>

> **&lt;!DOCTYPE html&gt;**

> **&lt;head&gt;**

> **&lt;meta&gt;**

> **&lt;title&gt;**

> **&lt;body&gt;**

