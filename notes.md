# Estudo de HTML:


##### Sumário
- [Definição](#definição)
- [Tags](#tags)

--------------------------------------------

##### Definição
_HTML_ é uma linguagem de marcação, e não de programação.

--------------------------------------------

##### TAGS

- `<!--` e `-->`: o conteúdo que for colocado entre essas tags será considerados um _comentário_; 
- `<!DOCTYPE html>`: visa garantir a compatibilidade com os navegadores modernos. Com isso está dizendo para o navegador que o código foi escrito em HTML5. É _case insensitive_ funcionando tanto `<!doctype html>` ou `<!DOCTYPE HTML>`, deve vir antes da tag `<html>`;
- `<html>`: deve ser sempre a primeira tag do seu código. Ela deve ser fechada com `</html>`. Ela envolve todo o código;
- `<head>`: define o cabeçalho. O conteúdo dentro das tags `<head>` e `</head>` não é visível no browser, mas contém instruções sobre seu conteúdo e comportamento, como folhas de estilo e scripts;
- `<title>`: define o título título da página, ou seja o texto que aparece na aba/janela do navegador. O conteúdo precisa estar entre `<title>` e `</title>`;
- `<meta>`: define metadados, ou seja, informações sobre o documento HTML. Essas tags são inseridas dentro do elemento `<head>` e servem para especificar o conjunto de caracteres, autoria, configurações de visualização, entre outras informações; 
- `<body>`: representa o conteúdo de um documento HTML, a tag fecha com `</body>`. É permitido apenas um `<body>` por documento.
- `<h1>` até `<h6>`: define do cabeçalho 1 até o cabeçalho 6. Quanto maior o número menor o tamnho da fomnte do cabeçalho. É necessário fechar as tags, por exemplo `<h3>` `</h3>`.
- `<p>`: define um parágrafo. O conteúdo precisa ser fechado pela tag `</p>`.
- `<br>`: cria uma quebra de linha. O _br_ vem de break.
- `<hr>`: é usada para representar uma quebra temática entre parágrafos ou seções de uma página. O _\<hr>_ significa Horizontal Rule (Linha Horizontal). É indicado pensar nela como aquela linha ou espaçamento que encontra-se em livros quando o autor muda de assunto, muda o ponto de vista da história ou passa para um novo tópico dentro do mesmo capítulo. 
Além disso é importante saber que ela é uma tag vazia (ou de fechamento automático), o que significa que ela não tem conteúdo de texto dentro dela e não precisa de uma tag de fechamento.
- `<b>`: transforma o conteúdo em negrito. É preciso fechar com a tag `</b>`.
- `<i>`: transforma o conteúdo em itálico. É preciso fechar com a tag `</i>`.
- `<ol>`: usado para criar uma lista ordenada. É preciso fechar com a tag `</ol>`.
- `<ul>`: usado para criar uma lista não ordenada. É preciso fechar com a tag `</ul>`.
- `<li>`: para inserir elementos tanto listas ordenadas e não ordenadas. É preciso fechar com a tag `</li>`.
- `<footer>`: significa Rodapé. Ela é uma tag semântica, introduzida no HTML5, usada para definir a seção de encerramento de uma página web ou de uma seção específica dentro do site. .É preciso fechar com a tag `</footer>`. Ela fica dentro do _body_.
