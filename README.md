# Enrico Dellatorre - RM:566824
# Gustavo Atusyuki Hiruo - RM:567625

# Link do deploy - https://niercoelectron.github.io/CP-04-FRONT-END/

# 🌿 VerdeEssência — Moda Sustentável

**VerdeEssência** é um site de e-commerce voltado para moda sustentável, oferecendo roupas, acessórios, produtos de beleza e itens para casa — todos com produção ética e materiais ecológicos. O projeto foi desenvolvido como Checkpoint da disciplina de **Front-End** da **FIAP**.

## 📸 Sobre o Projeto

O site simula uma loja virtual completa de moda sustentável, com foco em design limpo, navegação intuitiva e responsividade. A identidade visual utiliza tons de verde e areia, reforçando a proposta ecológica da marca.

### Páginas

| Página | Descrição |
|---|---|
| **Home** (`index.html`) | Banner carrossel, diferenciais da marca, categorias, produtos em destaque, depoimentos de clientes e rodapé completo. |
| **Categorias** (`categorias.html`) | Listagem de produtos com filtros laterais (tipo, faixa de preço), ordenação e grid de cards. |
| **Produto** (`produto.html`) | Página de detalhes de um produto com galeria de imagens, seleção de tamanho/cor, avaliações e produtos relacionados. |
| **Contato** (`contato.html`) | Formulário de contato com campos de nome, e-mail, assunto e mensagem, além de informações de atendimento. |

## 🛠️ Tecnologias Utilizadas

- **HTML5** — Estrutura semântica das páginas
- **CSS3** — Estilização customizada com variáveis CSS (`--verde-principal`, `--areia`, etc.)
- **Bootstrap 5.3.3** — Framework CSS para layout responsivo, grid system, componentes (navbar, carousel, cards, formulários, breadcrumbs)
- **Bootstrap Icons 1.11.3** — Ícones utilizados em seções e navegação
- **Font Awesome 6.5.0** — Ícones complementares (carrinho, redes sociais)
- **Google Fonts (Quicksand)** — Fonte customizada carregada via `@font-face`

## 📁 Estrutura do Projeto

```
├── index.html            # Página inicial
├── categorias.html       # Página de categorias/produtos
├── produto.html          # Página de detalhes do produto
├── contato.html          # Página de contato
├── README.md
└── src/
    ├── assets/
    │   └── fonts/        # Fonte Quicksand (variável)
    └── css/
        └── style.css     # Estilos customizados
```

## 🎨 Paleta de Cores

| Cor | Variável | Hex |
|---|---|---|
| Verde Principal | `--verde-principal` | `#2f6b4f` |
| Verde Claro | `--verde-claro` | `#eaf5ee` |
| Areia | `--areia` | `#f7f3eb` |
| Marrom | `--marrom` | `#6f5c4b` |
| Texto | `--texto` | `#243126` |

## ✨ Funcionalidades e Destaques

- **Design Responsivo** — Layout adaptável para desktop, tablet e mobile
- **Carrossel Interativo** — Banner rotativo na home com imagens e CTAs
- **Cards de Produto** — Exibição de produtos com badges ecológicos, preços e botões de ação
- **Filtros de Categoria** — Checkboxes por tipo de produto e faixa de preço
- **Galeria de Produto** — Imagem principal com thumbnails clicáveis
- **Formulário de Contato** — Campos validados com seleção de assunto
- **Depoimentos** — Seção de avaliações de clientes
- **Navbar Sticky** — Navegação fixa com efeito de blur (glassmorphism)
- **Hover Effects** — Animações suaves em cards e ícones

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/NiercoElectron/CP-04-FRONT-END.git
   ```
2. Abra o arquivo `index.html` no navegador.

> Não é necessário instalar dependências — os frameworks são carregados via CDN.

## 👥 Autores

- **Gustavo Hiruo** — [LinkedIn](https://www.linkedin.com/in/gustavo-hiruo-098847380/)
- **Enrico Dellatorre** — [LinkedIn](https://www.linkedin.com/in/enrico-dellatorre-57a0a4381/)

---

📌 **FIAP** — Checkpoint 04 · Front-End · 2026
