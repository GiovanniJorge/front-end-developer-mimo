# Front-End Developer - Mimo

Exercícios e projetos relacionados ao curso "Front-End Developer" da Mimo — coleção organizada de aplicações práticas com foco em JavaScript, CSS e HTML. Ideal para desenvolvedores que desejam consolidar conhecimentos em desenvolvimento front-end moderno.

## Conteúdo principal
- Exercícios prototipados com foco em funcionalidades reais e interativas.
- Projetos estruturados com HTML, CSS e JavaScript vanilla ou frameworks modernos (React).
- Exemplos de integração com APIs externas (ex.: PokéAPI).
- Aplicações responsivas e com boas práticas de desenvolvimento web.

## Badges
![Licença](https://img.shields.io/github/license/GiovanniJorge/front-end-developer-mimo?style=flat-square)
![Projetos](https://img.shields.io/badge/quantidade-1%20projeto-blue?style=flat-square)

## Sumário
- [Visão geral](#visão-geral)
- [Estrutura do repositório](#estrutura-do-repositório)
- [Destaques do repositório](#destaques-do-repositório)
- [Como executar os projetos](#como-executar-os-projetos)
- [Contribuindo](#contribuindo)
- [Licença](#licença)
- [Autor / Contato](#autor--contato)

## Visão geral
Este repositório organiza exercícios e projetos práticos em desenvolvimento front-end que exemplificam conceitos de web design responsivo, manipulação do DOM, consumo de APIs e desenvolvimento com frameworks modernos. Cada projeto é uma aplicação independente e funcional, pronta para ser explorada e estendida.

## Estrutura do repositório
Top-level:
```text
├── .gitignore
├── README.md
├── package.json               # Dependências e scripts compartilhados
├── exercicios/                # Exercícios e pequenas aplicações didáticas
│   ├── exercicio-1/
│   ├── exercicio-2/
│   └── ...
└── projetos-finais/           # Projetos completos e integrados
    └── pokedex/               # Pokedex interativa com React (Consumo de PokéAPI)
        ├── public/            # Assets estáticos
        ├── src/               # Código-fonte (componentes, serviços, estilos)
        ├── package.json       # Dependências específicas do projeto
        └── README.md          # Documentação detalhada
```

### Como se encaixa:
- O repositório abriga uma variedade de projetos e exercícios independentes criados ao longo do curso.
- Cada pasta possui sua própria estrutura dedicada, onde projetos baseados em ecossistemas modernos (como a Pokedex em React) contêm seus próprios arquivos `package.json` locais para execução isolada.

## Destaques do repositório

### Pokédex
* **Descrição:** Interface dinâmica e integrada para listagem e busca de criaturas consumindo os dados da PokéAPI externa em tempo real.
* **Tecnologias:** React, JavaScript (ES6+), CSS3 Modules.

## Como executar os projetos

### Pré-requisitos
- **Node.js** (v14 ou superior recomendado)
- **npm** ou **yarn** como gerenciador de pacotes
- Um navegador moderno (Chrome, Firefox, Edge ou Safari)

### Passos para execução

1. **Clone o repositório:**
```bash
git clone [https://github.com/GiovanniJorge/front-end-developer-mimo.git](https://github.com/GiovanniJorge/front-end-developer-mimo.git)
cd front-end-developer-mimo
```

2. **Para projetos React (Exemplo: Pokédex):**
```bash
cd projetos-finais/pokedex
npm install
npm start
```
A aplicação iniciará o servidor local em `http://localhost:3000`. Para gerar o build otimizado de produção, execute `npm run build`.

3. **Para exercícios simples (HTML / CSS / Vanilla JS):**
```bash
cd exercicios/seu-exercicio

# No Linux/macOS:
open index.html
# No Windows:
start index.html

# Ou inicie um servidor HTTP local simples com Python:
python3 -m http.server 8000
```

## Contribuindo
Contribuições são bem-vistas! Se deseja adicionar um novo exercício ou corrigir bugs estruturais de acessibilidade, siga os passos abaixo:

1. Faça um **Fork** do repositório.
2. Crie uma branch com nome descritivo: `feature/novo-exercicio` ou `fix/bug-correcao`.
3. Faça commits atômicos com mensagens claras utilizando a convenção do projeto (ex: `feat:`, `fix:`, `docs:`).
4. Abra um **Pull Request** detalhando as alterações implementadas.

## Licença
Este repositório utiliza a licença MIT — consulte o arquivo [LICENSE](LICENSE) na raiz.

## Autor / Contato
- **Autor:** Giovanni Jorge  
- **Repositório:** [https://github.com/GiovanniJorge/front-end-developer-mimo](https://github.com/GiovanniJorge/front-end-developer-mimo)
