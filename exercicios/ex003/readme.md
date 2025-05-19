Aqui está um exemplo de `README.md` para o Exercício 3, com base no código HTML fornecido:

---

# Exercício 3 – Testando Carga de Imagens em HTML

Este exercício tem como objetivo demonstrar diferentes formas de carregar imagens em uma página HTML. O arquivo `index.html` inclui exemplos de imagens locais, imagens em subpastas e imagens hospedadas externamente.

## Estrutura do Projeto

```
exercicio-3/
│
├── index.html
├── logo html 200.png
└── imagens/
    └── logo css 200.png
```

## Conteúdo

O arquivo `index.html` inclui os seguintes elementos:

- **Imagem na mesma pasta:**  
  Usa a tag `<img>` para exibir uma imagem que está no mesmo diretório do arquivo HTML.  
  ```html
  <img src="logo html 200.png" alt="logo HTML5">
  ```

- **Imagem em subpasta:**  
  Exibe uma imagem localizada dentro de uma subpasta chamada `imagens`.  
  ```html
  <img src="imagens/logo css 200.png" alt="logo CSS3">
  ```

- **Imagem externa (URL):**  
  Exibe uma imagem hospedada em um servidor externo.  
  ```html
  <img src="https://blog.magmalabs.io/wp-content/uploads/2012/06/JAVASCRIPT-EVOLUTION-BACKBONECONF.png" alt="logo JavaScript">
  ```

## Objetivo

- Compreender o uso da tag `<img>` no HTML.
- Aprender a carregar imagens locais e externas.
- Organizar arquivos em pastas para melhor estruturação de projetos.

## Requisitos

Para visualizar corretamente as imagens locais:

- Certifique-se de que os arquivos `logo html 200.png` e `logo css 200.png` estejam nos locais indicados.
- Use um servidor local (como o Live Server no VS Code) se as imagens locais não forem exibidas diretamente ao abrir o HTML no navegador.

---

Se quiser, posso adaptar esse `README.md` para um formato mais técnico ou mais didático, dependendo da finalidade (estudo, entrega de trabalho, portfólio, etc.).