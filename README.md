# repositoriocolaborativo

Repositório fictício para aula de monitoria em GitHub da disciplina de Desenvolvimento de Software

**4. Estrutura e contribuição**

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

Este projeto está distribuído sob a licença **MIT**. Consulte o arquivo `LICENSE` para mais detalhes. ..