# 🚀 Desafio: Criando um Mini Blog Pessoal com HTML e CSS

Bem-vinda ao seu segundo desafio de desenvolvimento web! Nesta atividade, você vai construir a **Estrutura (HTML)** e a **Estilização (CSS)** de um Mini Blog Pessoal super charmoso e responsivo.

---

## 🎯 O Objetivo

O objetivo deste projeto é criar uma página de blog simples onde você possa exibir uma breve apresentação sobre você e uma lista com as suas postagens recentes. É uma excelente forma de treinar o alinhamento de textos, uso de imagens e cartões (*cards*) de conteúdo.

---

## 📁 Estrutura de Arquivos Recomendada

Antes de começar, certifique-se de organizar seus arquivos na mesma pasta (diretório):

```text
📂 seu-mini-blog/
┣ 📄 index.html      # Estrutura da página do blog
┣ 📄 style.css       # Estilos e visual do blog
┗ 📄 README.md       # Este guia de instruções
```

---

## 🛠️ Passo a Passo para o Desenvolvimento

### Passo 1: O Esqueleto (HTML)

No arquivo `index.html`, você deve criar a estrutura do seu blog utilizando as tags semânticas do HTML5:

*   **Cabeçalho (`<header>`)**: Deve conter o título principal do seu blog (`<h1>`) e um menu simples de navegação (`<nav>`) com dois ou três links falsos (*Ex: Home, Sobre, Contato*).
*   **Conteúdo Principal (`<main>`)**:
    *   Uma seção de apresentação (`<section>`) com uma foto sua (ou avatar) e um parágrafo curto se descrevendo.
    *   Uma seção para as postagens (`<section>`), onde cada post deve ser envolvido pela tag `<article>`.
*   **Artigos (`<article>`)**: Cada postagem precisa ter um título menor (`<h2>` ou `<h3>`), a data da publicação (`<small>` ou `<time>`) e um texto curto de resumo.
*   **Rodapé (`<footer>`)**: Um texto simples de direitos autorais (*Ex: "Desenvolvido com ❤️ por [Seu Nome]"*).

> ⚠️ **Muito Importante:** Não se esqueça de incluir a tag `<link rel="stylesheet" href="style.css">` dentro do seu `<head>` para conectar o HTML ao CSS!

### Passo 2: O Visual (CSS)

No arquivo `style.css`, dê vida ao seu blog seguindo estas etapas:

*   **Reset Inicial:** Zere as margens (`margin: 0; padding: 0; box-sizing: border-box;`) e defina uma fonte bonita no `body`.
*   **Layout Limpo:** Defina uma largura máxima para o conteúdo da página (*Ex: max-width: 800px;*) e use `margin: 0 auto;` para deixar tudo centralizado na tela.
*   **Navegação:** Deixe os links do menu lado a lado usando **Flexbox** e remova os sublinhados padrões (`text-decoration: none;`).
*   **Cartões de Postagem (Cards):** Estilize cada `<article>` adicionando uma cor de fundo suave, bordas levemente arredondadas (`border-radius`), uma sombra sutil (`box-shadow`) e um espaçamento interno (`padding`) para desgrudar o texto das bordas.
*   **Responsividade:** Garanta que as imagens não passem do tamanho da tela usando `max-width: 100%;`.

---

## 🚀 Como enviar para o GitHub

Depois que sua página estiver linda e funcionando, abra o terminal na pasta do projeto e envie os comandos abaixo:

1. **Inicialize o repositório Git:**
   ```bash
   git init
   ```

2. **Adicione os arquivos:**
   ```bash
   git add .
   ```

3. **Crie o seu commit:**
   ```bash
   git commit -m "feat: cria estrutura e estilo do mini blog"
   ```

4. **Conecte com o seu repositório remoto** *(substitua pelo seu link)*:
   ```bash
   git remote add origin https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git
   ```

5. **Envie os arquivos:**
   ```bash
   git branch -M main
   git push -u origin main
   ```

---

Boa sorte, Dev! Solte a criatividade nas cores e nos textos! 💻✨
