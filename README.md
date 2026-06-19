# GitHub Blog

Aplicação de blog desenvolvida com React e TypeScript que consome a API do GitHub, exibindo issues de um repositório como publicações e permitindo busca por conteúdo.

## Tecnologias

- [React](https://react.dev/) — biblioteca para construção de interfaces
- [TypeScript](https://www.typescriptlang.org/) — tipagem estática
- [Vite](https://vitejs.dev/) — bundler e servidor de desenvolvimento
- [GitHub API](https://docs.github.com/en/rest) — fonte de dados das publicações
- [React Router DOM](https://reactrouter.com/) — navegação entre páginas
- [React Markdown](https://github.com/remarkjs/react-markdown) — renderização de Markdown

## Funcionalidades

- Exibição do perfil do usuário do GitHub (avatar, bio, seguidores e repositórios)
- Listagem de issues do repositório como posts do blog
- Busca de posts por palavra-chave
- Página de detalhes da publicação com conteúdo em Markdown
- Contador de resultados da busca

## Como Executar

```bash
npm install
npm run dev
```

## Deploy

[GitHub Blog](https://github-blog-eight-lime.vercel.app/)

## Sobre

Projeto desenvolvido durante o curso Ignite da [Rocketseat](https://www.rocketseat.com.br/), com foco em consumo de API, React Router e renderização de Markdown.
