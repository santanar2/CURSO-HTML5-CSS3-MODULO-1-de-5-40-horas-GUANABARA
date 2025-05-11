# CURSO-HTML5-CSS-MODULO-1-GUANABARA

`ex001.html`

`README.md` comentando o propósito e a estrutura do arquivo `ex001.html` que você forneceu:

---

# Exercício 001 - Meu Primeiro Documento HTML

Este é o **primeiro exercício** de HTML básico, com o objetivo de criar um documento HTML simples e funcional. Ele demonstra a estrutura mínima de uma página web e exibe uma saudação com texto descritivo.

## Arquivo: `ex001.html`

### Estrutura do código:

```html
<!DOCTYPE html>
```
- Define o tipo do documento como HTML5.

```html
<html lang="pt-BR">
```
- A tag `<html>` inicia o documento e define o idioma como português do Brasil.

```html
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Meu primeiro exercicio</title>
</head>
```
- A seção `<head>` inclui metadados:
  - `charset="UTF-8"` garante a correta exibição de caracteres especiais.
  - `viewport` permite a responsividade em dispositivos móveis.
  - `<title>` define o nome da aba do navegador.

```html
<body>
  <h1>Olá, Mundo! </h1>
  <hr>
  <p> Esse é o meu primeiro documento HTML! Estou muito feliz!</p>
  <p> Este é um momento único!Estou criando um site!</p>
</body>
</html>
```
- A seção `<body>` contém o conteúdo visível da página:
  - `<h1>` é um título principal.
  - `<hr>` insere uma linha horizontal.
  - `<p>` são parágrafos com mensagens pessoais de entusiasmo.

---

## Objetivo

Este exercício tem como objetivo praticar:

- A estrutura básica de um documento HTML.
- O uso de elementos semânticos como `<h1>`, `<p>` e `<hr>`.
- A escrita correta de uma página com codificação de caracteres e responsividade.

---

###############################################################################################################

`ex002.html`

 `README.md` explicando o exercício `ex002.html`, de forma clara e didática:

---

# Exercício 002 - Parágrafos, Quebras de Linha, Símbolos e Emojis em HTML

Este exercício tem como objetivo demonstrar o uso de **parágrafos**, **quebras de linha**, **símbolos especiais** e **emojis** em um documento HTML. É uma continuação prática do aprendizado dos elementos básicos da linguagem.

## Arquivo: `ex002.html`

### Estrutura do Código:

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Parágrafos</title>
</head>
```
- Define o documento como HTML5, define o idioma como português do Brasil, e inclui configurações de codificação (`UTF-8`) e responsividade.

```html
<body>
  <h1> Parágrafos e quebras de linha</h1>
  <hr>
```
- Um título principal e uma linha horizontal para separar visualmente os conteúdos.

### Conteúdo Demonstrado:

#### 1. **Uso da tag `<p>` para parágrafos**
```html
<p>Você pode escrever um parágrafo...</p>
```
- Explica como criar parágrafos com HTML.

#### 2. **Uso da tag `<br>` para quebras de linha**
```html
<p>Se precisar quebrar o texto... <br> ...use a tag br.</p>
```
- Demonstra como forçar uma quebra de linha sem iniciar um novo parágrafo.

#### 3. **Símbolos especiais com entidades HTML**
```html
<p>vamos adicionar alguns símbolos especiais: &reg; &copy; &euro; &infin; ...</p>
```
- Apresenta entidades HTML que representam símbolos como marcas registradas, moedas e símbolos matemáticos.

#### 4. **Uso de códigos Unicode para emojis**
```html
<p>vamos adicionar alguns emojis: &#128512; &#128513; ...</p>
```
- Mostra como inserir emojis utilizando seus códigos Unicode.

---

## Objetivos do Exercício

- Praticar a estruturação de textos em HTML.
- Compreender como inserir **símbolos especiais** e **caracteres reservados** usando entidades HTML.
- Inserir **emojis** diretamente no HTML usando códigos Unicode.
- Diferenciar entre parágrafos (`<p>`) e quebras de linha (`<br>`).

---

## Observações

- A linha `<p>...&lt;p&gt; e &alt;/p&pt; </p>` contém pequenos erros nas entidades: `&alt;`, `&pt;` e `&lt;/p&pt;` são inválidas.
 A forma correta seria usar `&lt;p&gt;` e `&lt;/p&gt;` para mostrar as tags `<p>` e `</p>` como texto.
- A palavra "texsto" e "alugns" estão com erros de digitação (correto: "texto" e "alguns").

---

########################################################################################################