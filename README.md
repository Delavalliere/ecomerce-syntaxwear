# SyntaxWear - E-commerce de Tênis e Sneakers

SyntaxWear é um e-commerce moderno e responsivo especializado em tênis e sneakers, desenvolvido com HTML5 e CSS3 puros, seguindo as melhores práticas de desenvolvimento web e design responsivo.

![SyntaxWear Preview](./assets/images/logo/logo.svg)

## 📋 Índice

- [Características](#características)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Como Executar](#como-executar)
- [Recursos e Funcionalidades](#recursos-e-funcionalidades)
- [Responsividade](#responsividade)
- [Acessibilidade](#acessibilidade)
- [Organização do CSS](#organização-do-css)

## ✨ Características

- Design moderno e minimalista
- Totalmente responsivo (mobile-first)
- Otimizado para acessibilidade
- Performance otimizada
- Código limpo e bem organizado
- CSS modular e reutilizável

## 📁 Estrutura do Projeto

```
syntaxwear/
├── assets/
│   └── images/
│       ├── banners/      # Banners e imagens hero
│       ├── icons/        # Ícones do sistema
│       ├── logo/         # Logotipos
│       └── products/     # Imagens de produtos
├── css/
│   ├── components/       # Componentes modulares
│   │   ├── categories.css
│   │   ├── footer.css
│   │   ├── header.css
│   │   ├── hero.css
│   │   └── product-grid.css
│   ├── base.css         # Estilos base e tipografia
│   ├── layout.css       # Layout e grid system
│   ├── reset.css        # Reset CSS moderno
│   └── variables.css    # Variáveis CSS
└── index.html           # Página principal
```

## 🚀 Tecnologias Utilizadas

- HTML5 Semântico
- CSS3 Moderno
  - Custom Properties (variáveis)
  - Flexbox
  - Grid
  - Media Queries
  - BEM Methodology (naming convention)

## 💻 Como Executar

1. Clone o repositório:
```bash
git clone https://github.com/Delavalliere/ecomerce-syntaxwear.git
```

2. Navegue até a pasta do projeto:
```bash
cd ecomerce-syntaxwear
```

3. Abra o arquivo `index.html` em seu navegador ou use um servidor local:
```bash
# Usando Python 3
python -m http.server 8000

# Usando Node.js com http-server
npx http-server
```

## 🎯 Recursos e Funcionalidades

- **Header Responsivo**
  - Menu de navegação adaptável
  - Ícones de usuário e carrinho
  - Logo centralizado

- **Hero Section**
  - Banner principal com call-to-action
  - Overlay com texto e botões
  - Imagem de fundo otimizada

- **Categorias**
  - Grid de categorias principais
  - Efeitos hover suaves
  - Imagens otimizadas

- **Grid de Produtos**
  - Layout responsivo com CSS Grid
  - Cards de produto com informações
  - Adaptação para diferentes tamanhos de tela

- **Footer**
  - Newsletter
  - Links de navegação organizados
  - Redes sociais
  - Informações de contato

## 📱 Responsividade

O site é totalmente responsivo e segue a abordagem mobile-first:

- **Mobile**: < 768px
  - Menu hamburguer
  - Layout em coluna
  - Imagens otimizadas

- **Tablet**: 768px - 1024px
  - Grid adaptativo
  - Navegação expandida
  - Layout híbrido

- **Desktop**: > 1024px
  - Grid completo
  - Hover effects
  - Experiência desktop completa

## ♿ Acessibilidade

- Uso de HTML semântico
- ARIA labels quando necessário
- Contraste adequado
- Navegação por teclado
- Alt text em imagens
- Roles definidos

## 📐 Organização do CSS

O CSS foi organizado seguindo uma arquitetura modular:

- **reset.css**: Reset moderno e normalização
- **variables.css**: Variáveis CSS globais (cores, fontes, etc)
- **base.css**: Estilos base e utilitários
- **layout.css**: Sistema de grid e layouts
- **components/**: Componentes individuais

### Convenções de Nomes

Seguimos uma versão simplificada da metodologia BEM:
- Bloco: `.block`
- Elemento: `.block__element`
- Modificador: `.block--modifier`

## 🤝 Contribuição

1. Faça um Fork do projeto
2. Crie uma Branch para sua Feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a Branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

Desenvolvido com 💜 por [Delavalliere](https://github.com/Delavalliere)