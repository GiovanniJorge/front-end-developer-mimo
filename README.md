# Front-End Developer - Mimo
Exercícios e projetos relacionados ao curso "Front-End Developer" da Mimo — coleção organizada de aplicações práticas com foco em JavaScript, CSS e HTML. Ideal para desenvolvedores que desejam consolidar conhecimentos em desenvolvimento front-end moderno.

## Conteúdo principal
- Exercícios prototipados com foco em funcionalidades reais e interativas.
- Projetos estruturados com HTML, CSS e JavaScript vanilla ou frameworks modernos (React).
- Exemplos de integração com APIs externas (ex.: PokéAPI).
- Aplicações responsivas e com boas práticas de desenvolvimento web.

## Badges
- Licença: MIT (ver arquivo LICENSE)

## Sumário
- [Visão geral](#visão-geral)
- [Estrutura do repositório](#estrutura-do-repositório)
- [Como executar os projetos](#como-executar-os-projetos)
- [Boas práticas / recomendações](#boas-práticas--recomendações)
- [Contribuindo](#contribuindo)
- [Licença](#licença)
- [Autor / Contato](#autor--contato)

## Visão geral
Este repositório organiza exercícios e projetos práticos em desenvolvimento front-end que exemplificam conceitos de web design responsivo, manipulação do DOM, consumo de APIs, e desenvolvimento com frameworks modernos. Cada projeto normalmente é uma aplicação independente e funcional, pronta para ser explorada e estendida.

## Estrutura do repositório
Top-level:
- `.gitignore`
- `README.md`
- `package.json` — dependências e scripts compartilhados (se houver)
- `exercicios/` — exercícios e pequenas aplicações didáticas
  - `exercicio-1/` — projeto/exercício exemplo 1
  - `exercicio-2/` — projeto/exercício exemplo 2
  - (mais exercícios...)
- `projetos-finais/` — projetos completos e integrados
  - `pokedex/` — Pokedex interativa com React
    - `public/` — assets estáticos
    - `src/` — código-fonte (componentes, serviços, estilos)
    - `package.json` — dependências específicas do projeto
    - `README.md` — documentação detalhada
  - (mais projetos...)

Como se encaixa:
- Cada pasta de exercício ou projeto é uma aplicação independente.
- Alguns projetos podem ter suas próprias dependências (`package.json` locais) e devem ser executados separadamente.
- A forma usual de usar o repositório é navegar para a pasta desejada e seguir as instruções de execução específicas do projeto.

## Como executar os projetos

### Pré-requisitos
- Node.js (v14+ recomendado) — necessário para projetos com npm
- npm ou yarn — gerenciador de pacotes
- Um navegador moderno (Chrome, Firefox, Safari, Edge)

### Projeto Pokedex (React)
```bash
# Navegar até o projeto
cd projetos-finais/pokedex

# Instalar dependências
npm install

# Iniciar servidor de desenvolvimento
npm start

# Acessar no navegador
# http://localhost:3000
```

### Exercícios simples (HTML/CSS/JavaScript)
Para exercícios que usam apenas HTML, CSS e JavaScript vanilla:
```bash
# Navegar até o exercício
cd exercicios/seu-exercicio

# Abrir no navegador (direto ou com um servidor local)
# Opção 1: Abrir arquivo diretamente
open index.html

# Opção 2: Usar um servidor local (Python)
python3 -m http.server 8000
# Acesse http://localhost:8000

# Opção 3: Usar Live Server (VS Code extension)
# Instale a extensão "Live Server" e abra com ela
```

### Compilação/Build para produção
Para projetos React:
```bash
cd projetos-finais/pokedex
npm run build
# Gera a versão otimizada em ./build
```

## Boas práticas / recomendações

### Estrutura de código
- Organize componentes em pastas separadas com seus estilos.
- Use nomes descritivos para variáveis, funções e classes CSS.
- Mantenha a separação entre lógica (JavaScript) e apresentação (CSS/HTML).
- Prefira módulos CSS ou CSS-in-JS para evitar conflitos de estilos.

### Performance
- Minimize o uso de dependências; considere JavaScript vanilla para exercícios simples.
- Use lazy loading para imagens grandes.
- Comprima e otimize imagens antes de commitar.
- Para projetos React, use React.memo e useMemo quando apropriado.

### Acessibilidade
- Use semântica HTML correta (ex.: `<button>`, `<nav>`, `<article>`).
- Adicione labels a inputs de formulário.
- Garanta contraste adequado de cores (WCAG AA mínimo).
- Teste com leitores de tela (ex.: NVDA, JAWS).

### Documentação
- Cada projeto deve ter um README com descrição, instalação e como usar.
- Adicione comentários no código para lógica complexa.
- Use nomes de variáveis e funções autodescritivos.

### Versionamento e commits
- Faça commits atômicos com mensagens claras.
- Exemplo: "feat: adiciona busca de Pokémon por nome" ao invés de "alterações".
- Use convenção de commits (feat:, fix:, docs:, style:, refactor:, test:).

## Contribuindo
Contribuições são bem-vindas! Fluxo sugerido:

1. **Fork** do repositório.
2. **Criar branch** com nome descritivo: `feature/novo-exercicio`, `fix/bug-correcao`, `docs/melhorias-readme`.
3. **Fazer commits** atômicos com mensagens claras e convencionais.
4. **Abrir Pull Request** descrevendo as mudanças, o que foi adicionado/corrigido e, se aplicável, a motivação pedagógica.
5. **Incluir testes ou instruções** para validar o exercício/projeto (se possível).

### Sugestões para contribuições
- Adicionar novos exercícios temáticos (animações CSS, manipulação de DOM, etc.).
- Melhorar a documentação de projetos existentes.
- Corrigir bugs ou problemas de acessibilidade.
- Adicionar testes automatizados.
- Implementar workflows de CI/CD com GitHub Actions.

## Testes e automação (opcional)
- Poderia ser adicionado um GitHub Actions workflow que valida a compilação de projetos React.
- Para exercícios simples, adicionar testes E2E com Playwright ou Cypress.
- Linter (ESLint) e formatador (Prettier) para manter consistência de código.

## Licença
Este repositório utiliza a licença MIT — consulte o arquivo `LICENSE` na raiz.

## Autor / Contato
Autor: Giovanni Jorge  
Repositório: https://github.com/GiovanniJorge/front-end-developer-mimo
