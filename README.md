# vscodeum-ext

### Resumo de Extensões para VSCodium

As extensões listadas focam em melhoria de produtividade, qualidade de código (linting/formatting), versionamento e infraestrutura (SSH/Shell).

#### Qualidade de Código e Formatação

| Extensão | Função Principal |
| --- | --- |
| `aaron-bond.better-comments` | Cria comentários coloridos/categorizados (ex: `!`, `?`, `//`, `TODO`). |
| `dbaeumer.vscode-eslint` | Integração do ESLint para análise estática de código JavaScript/TypeScript. |
| `esbenp.prettier-vscode` | Formatador de código opinativo para múltiplos padrões de linguagem. |
| `mkhl.shfmt` | Formatador para scripts Bash (utiliza o `shfmt`). |
| `stylelint.vscode-stylelint` | Linting para CSS, SCSS e Less. |
| `redhat.vscode-xml` | Suporte a XML com validação de esquema (XSD) e linting. |
| `rintoj.json-organizer` | Organiza chaves JSON de forma estruturada. |

#### Produtividade e Experiência do Desenvolvedor (DX)

| Extensão | Função Principal |
| --- | --- |
| `editorconfig.editorconfig` | Mantém consistência de indentação e espaçamento entre editores. |
| `gruntfuggly.todo-tree` | Exibe todos os itens marcados como `TODO` ou `FIXME` em uma árvore na barra lateral. |
| `usernamehw.errorlens` | Exibe mensagens de erro/aviso diretamente na linha do código (inline). |
| `naumovs.color-highlight` | Destaca códigos de cores (hex, rgb) no editor. |
| `oderwat.indent-rainbow` | Colore a indentação para facilitar a leitura de blocos aninhados. |
| `ms-ceintl.vscode-language-pack-pt-br` | Tradução da interface do VSCodium para Português Brasileiro. |
>Ao instalar o pacote de linguagem, deve copiar o arquivo `argv.json` para o diretório `"$HOME"/.vscode-oss`

#### Shell Scripting e Automação

| Extensão | Função Principal |
| --- | --- |
| `jannek-aalto.shell-function-outline` | Cria um outline de funções Bash para navegação rápida. |
| `jeff-hykin.better-shellscript-syntax` | Melhora o suporte de sintaxe e coloração para Shell. |
| `remisa.shellman` | Snippets para facilitar a escrita de scripts Shell. |
| `timonwong.shellcheck` | Análise estática para encontrar bugs em scripts Shell. |
| `zokugun.cron-tasks` | Gerenciamento e visualização de tarefas do Cron. |

#### Git e Versionamento

| Extensão | Função Principal |
| --- | --- |
| `eamodio.gitlens` | Expande as capacidades nativas do Git (blame, histórico, comparações). |
| `mhutchie.git-graph` | Visualização gráfica da árvore de commits e branches. |
| `github.vscode-pull-request-github` | Gerencia Pull Requests do GitHub diretamente no editor. |

#### Acesso Remoto e Infraestrutura

| Extensão | Função Principal |
| --- | --- |
| `jeanp413.open-remote-ssh` | Conexão SSH para edição remota de arquivos. |
| `cweijan.vscode-ssh` | Gerenciador de conexões SSH, SFTP e terminais remotos. |
| `jdevs.remote-development-ts` | Ferramentas auxiliares para desenvolvimento remoto. |

---

**Nota Técnica:** Certifique-se de que as dependências binárias (como `shfmt`, `shellcheck` e `eslint`) estejam instaladas no seu PATH (via `pacman` ou `nix`) para que as extensões funcionem corretamente, evitando depender de instaladores internos de extensões proprietárias quando possível.

