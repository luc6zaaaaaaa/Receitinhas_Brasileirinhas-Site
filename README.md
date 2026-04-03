# 🥘 Receitinhas Brasileirinhas

> **Projeto Acadêmico - FATEC Itaquera** > Curso: Desenvolvimento de Software Multiplataforma (DSM)  
> Disciplina: Desenvolvimento Web I - 1º Semestre

---

## 📖 Índice

- [📌 Sobre o Projeto](#-sobre-o-projeto)
- [🎓 Contexto Acadêmico](#-contexto-acadêmico)
- [🛠️ Tecnologias e Metodologia](#️-tecnologias-e-metodologia)
- [📁 Estrutura de Arquivos](#-estrutura-do-projeto)
- [🚀 Como Executar](#-como-rodar-localmente)
- [👥 Autores](#-autores)

---

## 📌 Sobre o Projeto

O **Receitinhas Brasileirinhas** é uma plataforma web desenvolvida para facilitar o acesso à cultura gastronômica nacional. O foco do projeto é aplicar conceitos de **Web Standard**, semântica HTML5 e design responsivo para criar uma experiência de usuário fluida e educativa.

### 🎯 Objetivos do Sistema
- **Democratização:** Tornar receitas tradicionais acessíveis através de uma interface simples.
- **Responsividade:** Garantir que o aluno ou cozinheiro acesse a receita do celular na cozinha ou do desktop.
- **Performance:** Uso de práticas de desenvolvimento que garantem carregamento rápido (Clean Code).

---

## 🎓 Contexto Acadêmico

Este projeto faz parte da grade curricular da **FATEC Itaquera**. Ele serve como avaliação prática para consolidar os fundamentos de:
- Estruturação de documentos com **HTML5**.
- Estilização avançada e Layouts com **CSS3 (Flexbox/Grid)**.
- Organização de diretórios e versionamento com **Git/GitHub**.
- Arquitetura de informação para sistemas multi-páginas.

---

## 🛠️ Tecnologias e Metodologia

| Tecnologia | Finalidade |
|-----------|-----------|
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) | Estruturação semântica das receitas e menus. |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) | Estilização, layout responsivo e identidade visual. |
| ![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white) | Controle de versão e colaboração. |
| ![Fonts](https://img.shields.io/badge/Google%20Fonts-4285F4?style=for-the-badge&logo=google&logoColor=white) | Tipografia otimizada para leitura (Poppins). |

---

## 📁 Estrutura do Projeto

A organização segue o padrão de separação de responsabilidades (assets, páginas e estilos):

```text
site/
├── menu.html                          # Landing Page (Ponto de entrada)
│
├── css/
│   └── css_menu.css                   # Estilização Global (Flexbox, Responsivo)
│
├── img/                               # Assets Visuais e Logos
│   └── logo.png                       # Logo do projeto
│
├── sites/                             # Módulos de Categorias
│   ├── bebidas.html
│   ├── sobremesa.html
│   ├── pratos.html
│   ├── pascoa.html
│   ├── quem-somos.html                # Informações institucionais
│   │
│   └── Receitas/                      # Banco de dados de receitas (HTML estático)
│       ├── Bebidas/
│       │   ├── chocolate_quente.html
│       │   ├── limonada_suica.html
│       │   ├── suco_laranja.html
│       │   ├── vinho_quente.html
│       │   └── img/
│       │
│       ├── Pascoa/
│       │   ├── bacalhau.html
│       │   ├── colomba_pascal.html
│       │   ├── ovo_pascoa.html
│       │   ├── torta_chocolate.html
│       │   └── img/
│       │
│       ├── Pratos/
│       │   ├── feijoada.html
│       │   ├── lasanha.html
│       │   ├── moqueca.html
│       │   ├── strogonoff.html
│       │   └── img/
│       │
│       └── Sobremesa/
│           ├── bolo_cenoura.html
│           ├── brigadeiro.html
│           ├── mousse_maracuja.html
│           ├── pudim.html
│           └── img/
│
├── README.md                          # Documentação do projeto
└── LICENSE                            # Licença MIT
```

---

## 🍽️ Categorias de Receitas

| Categoria | Descrição | Exemplos |
|-----------|-----------|----------|
| 🍲 **Pratos** | Pratos principais da culinária brasileira | Feijoada, Moqueca, Strogonoff, Lasanha |
| 🥛 **Bebidas** | Bebidas tradicionais refrescantes e quentes | Suco de Laranja, Limonada Suíça, Vinho Quente, Chocolate Quente |
| 🍰 **Sobremesas** | Doces e sobremesas irresistíveis | Bolo de Cenoura, Brigadeiro, Mousse de Maracujá, Pudim |
| 🐰 **Páscoa** | Receitas especiais para festividades | Bacalhau à Brás, Colomba Pascal, Ovo de Páscoa, Torta de Chocolate |

---

## ✨ Funcionalidades Principais

- ✅ **Design Responsivo:** Layout adaptável para mobile, tablet e desktop
- ✅ **Navegação Intuitiva:** Menu de fácil acesso com categorias bem definidas
- ✅ **Receitas Detalhadas:** Instruções passo a passo com ingredientes organizados
- ✅ **Performance Otimizada:** Carregamento rápido sem dependências externas
- ✅ **Semântica HTML5:** Código estruturado e acessível
- ✅ **CSS Moderno:** Flexbox para layouts fluidos e adaptáveis

---

## 📋 Pré-requisitos

Nenhuma dependência complexa! O projeto utiliza tecnologias **Vanilla Web** (HTML5 puro + CSS3):

- ✅ **Navegador moderno** (Chrome, Firefox, Safari, Edge)
- ✅ **Editor de código** (VS Code, Sublime, etc.) - *opcional, apenas para edições*
- ⭕ **Nenhum**: Node.js, Python, Apache, etc. não são necessários

---

## 🚀 Como Rodar Localmente

### Opção 1: Abrir Diretamente no Navegador (Mais Simples)

```bash
# 1. Clone o repositório
git clone https://github.com/luc6zaaaaaaa/Receitinhas_Brasileirinhas-Site.git

# 2. Navegue até a pasta
cd site

# 3. Abra menu.html no navegador
# Windows: Duplo clique em menu.html
# macOS: Clique direito > Abrir com > Navegador padrão
# Linux: xdg-open menu.html
```

### Opção 2: Usar o Live Server do VS Code (Recomendado para Desenvolvimento)

```bash
# 1. Instale a extensão "Live Server" no VS Code (ID: ritwickdey.LiveServer)

# 2. Clique com botão direito em menu.html

# 3. Selecione "Open with Live Server"

# O navegador abrirá automaticamente em http://localhost:5500
```

### Opção 3: Servidor Local com Python

```bash
# Python 3.x
cd site
python -m http.server 8000

# Python 2.x
python -m SimpleHTTPServer 8000

# Acesse em http://localhost:8000
```

### Opção 4: Servidor Local com Node.js

```bash
# Instale http-server globalmente (primeira vez)
npm install -g http-server

# Inicie o servidor
cd site
http-server

# Acesse em http://localhost:8080
```

### ✅ Verificação de Sucesso

Você saberá que está funcionando quando:
- 🏠 A página inicial carrega com logo e menu
- 🎨 Os estilos CSS aparecem (cores, fontes, layouts)
- 🔗 Os links de navegação funcionam entre páginas
- 📱 O layout se adapta ao redimensionar a janela
- 🖼️ As imagens das receitas carregam corretamente

---

## 🎨 Vista Geral da Interface

**Landing Page (menu.html):**
- Header com logo e título
- Menu de navegação com categorias
- Seção de destaques com cards de receitas
- Decoração com emojis temáticos

**Páginas de Categoria:**
- Lista de receitas da categoria
- Links para receitas completas
- Imagens de preview

**Páginas de Receita:**
- Ingredientes organizados
- Modo de preparo detalhado
- Imagens do processo
- Links de navegação

---

## 🎓 Conceitos Aplicados

Este projeto é um excelente exercício prático dos seguintes conceitos:

| Conceito | Aplicação no Projeto |
|----------|----------------------|
| **HTML5 Semântico** | Uso de tags como `<header>`, `<nav>`, `<main>`, `<section>`, `<article>` |
| **CSS3 Responsivo** | Media queries e Flexbox para adaptação de layouts |
| **Web Standards** | Compatibilidade entre navegadores e boas práticas web |
| **Arquitetura de Informação** | Hierarquia clara de páginas e categorias |
| **Mobile First** | Design pensado primeiramente para dispositivos móveis |
| **Clean Code** | Código bem organizado e fácil de manter |

---

## 👥 Autores

| 👤 Nome | 🎯 Função | 🔗 Contato |
|---------|----------|-----------|
| **Lucas Araujo de Souza** | Desenvolvedor Principal | [![GitHub](https://img.shields.io/badge/GitHub-@luc6zaaaaaaa-000?style=flat-square&logo=github)](https://github.com/luc6zaaaaaaa) |

### 👨‍🏫 Orientação Acadêmica

- **Disciplina:** Desenvolvimento Web I
- **Instituição:** FATEC Itaquera
- **Curso:** Desenvolvimento de Software Multiplataforma (DSM)
- **Semestre:** 1º

---

## 📚 Como Contribuir

Se você conhece receitas incríveis ou quer melhorar o projeto:

1. 🍴 Faça um Fork do repositório
2. 🌿 Crie uma branch para sua contribuição (`git checkout -b feature/nova-receita`)
3. 💾 Faça commit das mudanças (`git commit -m 'Adiciona receita: Brigadeiro Gourmet'`)
4. 📤 Push para a branch (`git push origin feature/nova-receita`)
5. 🔄 Abra um Pull Request descrevendo suas mudanças

### Padrão para Novas Receitas

Ao adicionar uma nova receita, siga este padrão:

```html
<div class="receita">
    <h2>Nome da Receita</h2>
    <p class="tempo">⏱️ Tempo: XX minutos</p>
    
    <h3>Ingredientes</h3>
    <ul>
        
    </ul>
    
    <h3>Modo de Preparo</h3>
    <ol>
       
    </ol>
</div>
```

---

## 📄 Licença

Este projeto é licenciado sob a **MIT License** - veja o arquivo [LICENSE](LICENSE) para detalhes completos.

```
MIT License - Você pode usar, modificar e distribuir este projeto livremente,
desde que inclua a licença original.
```

---

## 💡 Aprendizados Principais

Durante o desenvolvimento deste projeto, foram consolidados:

- ✅ Estrutura semântica de documentos HTML5
- ✅ Criação de layouts responsivos com CSS3 e Flexbox
- ✅ Organização de arquivos e pastas em projetos web
- ✅ Versionamento com Git e GitHub
- ✅ Boas práticas de desenvolvimento web
- ✅ Mobile-first design thinking
- ✅ Performance web (redução de requisições, otimização de imagens)

---

## 📞 Dúvidas ou Sugestões?

- 📧 Entre em contato através do perfil GitHub
- 🐛 Abra uma issue para reportar bugs ou sugerir melhorias
- ⭐ Se o projeto foi útil, considere dar uma estrela no GitHub!

---

<div align="center">

**Desenvolvido com ❤️ para celebrar a gastronomia brasileira**

[![Made with HTML5](https://img.shields.io/badge/Made%20with-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://html.spec.whatwg.org/)
[![Made with CSS3](https://img.shields.io/badge/Made%20with-CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://www.w3.org/Style/CSS/)
[![License MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

**Bom apetite!** 🍽️✨

</div>