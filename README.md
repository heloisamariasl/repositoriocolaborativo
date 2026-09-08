# 🎬 CineMatch

> Encontre filmes que combinam com você!

## 1. 🎬 Apresentação do projeto

O **CineMatch** é um projeto desenvolvido em equipe para criar uma plataforma simples de filmes, permitindo que os usuários encontrem e conheçam diferentes opções para assistir.

### Problema

Com a grande quantidade de filmes disponíveis atualmente, pode ser difícil escolher o que assistir de acordo com os próprios interesses.

### Objetivo

O objetivo do CineMatch é tornar a busca por filmes mais fácil e prática, reunindo informações e recursos que auxiliem o usuário na escolha.

### Público-alvo

O projeto é voltado para pessoas que gostam de assistir filmes e procuram novas opções para descobrir.

### Tecnologias

O projeto poderá utilizar tecnologias como:

- HTML
- CSS
- JavaScript
- Git
- GitHub

## 🎯 Funcionalidades

O CineMatch é uma plataforma voltada para a descoberta de filmes e para a interação entre usuários com gostos cinematográficos semelhantes. O sistema conta com as seguintes funcionalidades:

### 👤 Cadastro e login de usuários

Permite que os usuários criem uma conta na plataforma e realizem login para acessar suas informações e utilizar as funcionalidades personalizadas do CineMatch.

### 🔎 Busca de filmes

Possibilita pesquisar filmes por diferentes informações, como título, gênero, diretor ou outros critérios disponíveis no sistema.

### ⭐ Avaliação de filmes

Os usuários podem avaliar os filmes assistidos, permitindo registrar suas opiniões e contribuir para o sistema de recomendações.

### 🎬 Sistema de recomendações

Com base nas avaliações, preferências e histórico do usuário, o CineMatch sugere filmes que possam ser do seu interesse.

### 🤝 Match entre usuários

O sistema identifica usuários que possuem gostos cinematográficos semelhantes, possibilitando encontrar pessoas com preferências em comum.

### ❤️ Lista de favoritos e Watchlist

Permite que os usuários salvem filmes em uma lista pessoal. Os filmes podem ser adicionados aos **favoritos** ou à **Watchlist**, para serem assistidos posteriormente.

# repositoriocolaborativo

Repositório fictício para aula de monitoria em GitHub da disciplina de Desenvolvimento de Software

**Estrutura e contribuição**

**Estrutura de Pastas**

```text
cinematch/
├── src/
│   ├── assets/          # Imagens, ícones e estilos globais
│   ├── components/      # Componentes reutilizáveis da interface
│   ├── pages/           # Telas principais (Home, Match, Perfil, Watchlist)
│   ├── services/        # Configuração de rotas e chamadas de API (ex: TMDB)
│   └── utils/           # Funções auxiliares e algoritmos de recomendação
├── public/              # Arquivos estáticos acessíveis publicamente
├── .gitignore           # Arquivos e pastas ignorados pelo Git
├── README.md            # Documentação do projeto
└── package.json         # Dependências e scripts do Node.js

```

**Como Contribuir**

Contribuições são o que fazem a comunidade open source ser um lugar incrível para aprender e criar. Toda ajuda é bem-vinda!

1. Faça um **Fork** do projeto.
2. Crie uma **Branch** para a sua funcionalidade:
`git checkout -b feature/nome-da-funcionalidade`
3. Faça o **Commit** das suas alterações (siga o padrão abaixo):
`git commit -m 'feat: adiciona filtro por gênero no match'`
4. Envie as alterações para o seu repositório remoto:
`git push origin feature/nome-da-funcionalidade`
5. Abra um **Pull Request** para a branch principal (`main`) descrevendo o que foi feito.

**Fluxo de Git e Padrões de Commit**

Para manter o histórico do projeto limpo e legível, adotamos a convenção do *Conventional Commits*:

* `feat:` Adição de uma nova funcionalidade no sistema.
* `fix:` Correção de um bug ou comportamento inesperado.
* `docs:` Alterações na documentação (como no arquivo README).
* `style:` Formatação de código ou ajustes de UI sem alterar a lógica.
* `refactor:` Mudanças no código que melhoram a performance sem alterar o comportamento externo.

**Créditos dos Integrantes**

Projeto desenvolvido para fins didáticos pela equipe CineMatch:

* **Pessoa 1** — Apresentação, Visão Geral e Escopo
* **Pessoa 2** — Mapeamento de Funcionalidades e Regras de Negócio
* **Pessoa 3** — Guia de Instalação, Pré-requisitos e Execução
* **Pessoa 4** — Arquitetura de Pastas, Fluxo Git e Padrões de Contribuição

**Licença**

Este projeto está distribuído sob a licença **MIT**. Consulte o arquivo `LICENSE` para mais detalhes.
# 🎬 Cinematch

> Encontre o filme perfeito para assistir em dupla sem perder tempo!

---

## 📋 Sumário
1. [Sobre o Projeto](#1-sobre-o-projeto)
2. [Funcionalidades e Tecnologias](#2-funcionalidades-e-tecnologias)
3. [Como utilizar](#3-como-utilizar)
   - [Pré-requisitos](#pré-requisitos)
   - [Como instalar/clonar o projeto](#como-instalarclonar-o-projeto)
   - [Como executar localmente](#como-executar-localmente)
   - [Como utilizar as principais funcionalidades](#como-utilizar-as-principais-funcionalidades)
   - [Exemplos de uso](#exemplos-de-uso)
4. [Estrutura do Projeto](#4-estrutura-do-projeto)
5. [Como Contribuir](#5-como-contribuir)
6. [Licença](#6-licença)
7. [Autores e Agradecimentos](#7-autores-e-agradecimentos)

---

## 1. Sobre o Projeto

O **Cinematch** é uma aplicação web desenvolvida para resolver o clássico dilema de "o que vamos assistir hoje?". Inspirado na dinâmica de aplicativos de relacionamento, o Cinematch permite que duas pessoas entrem em uma mesma sala virtual, filtrem filmes por gênero ou plataforma de streaming e deem *swipe* (curtir/pular) nos títulos apresentados. Quando ambos dão *like* no mesmo filme, a aplicação exibe um **Match!** 🍿🎉

---

## 2. Funcionalidades e Tecnologias

### ✨ Funcionalidades
- **Salas em Tempo Real:** Criação e entrada em salas através de códigos únicos.
- **Filtros Personalizados:** Seleção por gênero, serviços de streaming e ano de lançamento.
- **Interface de Swipe:** Cartões interativos com informações detalhadas, sinopse e nota do filme.
- **Notificação de Match:** Alerta em tempo real assim que a dupla combina na escolha.
- **Lista de Combinados:** Aba dedicada para visualizar todos os filmes que deram *match* na sala.

### 🛠️ Tecnologias Utilizadas
- **Frontend:** React, TypeScript, Tailwind CSS
- **API de Filmes:** TMDB (The Movie Database) API
- **Build Tool:** Vite

---

## 3. Como utilizar

### Pré-requisitos
Antes de começar, certifique-se de ter instalado em sua máquina:
* **Git** (para clonagem do repositório)
* **Node.js** (versão 18.x ou superior)
* **NPM** ou **Yarn** (gerenciador de pacotes)
* Uma chave de API gratuita do **TMDB (The Movie Database)**

### Como instalar/clonar o projeto

1. Clone o repositório para a sua máquina local:
   ```bash
   git clone [https://github.com/seu-usuario/cinematch.git](https://github.com/seu-usuario/cinematch.git)
