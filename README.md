## Corp Default Landing Page

Landing page responsiva para a **Corp IT Solutions**, desenvolvida com HTML, Tailwind CSS, Bootstrap, Font Awesome, animações AOS e JavaScript puro.

## ✨ Funcionalidades

*   **Layout moderno e responsivo** (mobile-first)
*   Seções: Home, Quem Somos, Serviços, Projetos, Parcerias, Contato
*   Menu responsivo com animação e diálogo para mobile
*   Efeitos de animação ao rolar (AOS)
*   Lazy loading de imagens para performance
*   Botão flutuante de WhatsApp e "voltar ao topo"
*   Formulário de contato estilizado
*   Ícones Font Awesome customizados
*   Cores e estilos personalizados via CSS

## 🚀 Tecnologias Utilizadas

*   **HTML5** e **CSS3**
*   [Tailwind CSS](https://tailwindcss.com/) (via CDN)
*   [Bootstrap 5](https://getbootstrap.com/) (via CDN)
*   [Font Awesome 6](https://fontawesome.com/) (via CDN)
*   [AOS - Animate On Scroll](https://michalsnik.github.io/aos/)
*   JavaScript puro (ES6+)
*   Imagens e SVG customizados

## 📁 Estrutura de Pastas

```plaintext
corp-default-landing-page/
│
├── index.html
├── README.md
├── LICENSE
└── src/
    ├── css/
    │   └── base.css         # Estilos customizados (cores, animações, responsividade)
    ├── img/
    │   ├── logo.png         # Logotipo principal
    │   ├── background.png   # Imagem de fundo da home
    │   ├── hero-section.svg # SVG decorativo da home
    │   └── teams/
    │       └── team-01.jpg  # Foto do fundador/equipe
    └── js/
        └── index.js         # Scripts JS (menu mobile, lazy loading, animações, botões flutuantes)
```

## 🖥️ Como rodar o projeto

**Clone o repositório:**

**Abra o arquivo** `**index.html**` **no seu navegador.**

*   Não é necessário servidor backend.
*   Todos os assets estão na pasta `src/`.

## 🎨 Customização

*   **Cores e estilos:** Edite `src/css/base.css` para alterar cores, bordas, efeitos e responsividade.
*   **Imagens:** Substitua os arquivos em `src/img/` para trocar logotipo, fundo, fotos de equipe, etc.
*   **Seções:** Edite o `index.html` para adicionar/remover serviços, projetos, parceiros ou alterar textos.
*   **Ícones:** Use qualquer ícone do Font Awesome alterando as classes `<i class="fa-solid fa-..."></i>`.

## 📱 Responsividade

*   O layout é mobile-first, com ajustes de espaçamento e tamanho para telas pequenas.
*   O menu se transforma em diálogo animado no mobile.
*   O botão "voltar ao topo" só aparece após rolar a página.

## ⚙️ Funcionalidades JS

*   **Menu mobile:** Abre/fecha com animação, bloqueia scroll do fundo.
*   **Lazy loading:** Imagens só carregam quando aparecem na tela.
*   **AOS:** Animações suaves ao rolar.
*   **Botão WhatsApp:** Abre modal para contato rápido.
*   **Formulário de contato:** Apenas visual, sem backend.

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

```plaintext
git clone https://github.com/seu-usuario/corp-default-landing-page.git
cd corp-default-landing-page
```