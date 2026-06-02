<div align="center">
  <img src="./images/logos/logo_sem_texto.png" width="60" alt="Logo Médicos do Mundo">
  <h1>Landing Page - ONG Médicos do Mundo Brasil</h1>
</div>

<div align="center">
  <img src="https://img.shields.io/badge/status-protótipo-orange" alt="Status">
  <img src="https://img.shields.io/badge/HTML5-orange" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-blue" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-Vanilla-yellow" alt="JavaScript">
</div>

Landing page institucional da **ONG Médicos do Mundo Brasil**, apresentando projetos, missões, parcerias e canais de doação e voluntariado.

---

## 🔗 Link do Projeto

- **Produção:** [https://annajsussai.github.io/ong_mdm/](https://annajsussai.github.io/ong_mdm/)

---

## 📃 Resumo do Projeto

Site estático em HTML/CSS/JS puro para a ONG Médicos do Mundo Brasil. Apresenta as ações humanitárias da organização, facilita doações e captação de voluntários, e exibe parcerias institucionais.

**Seções:**
- Hero com imagem e chamada principal
- Quem Somos / Sobre Nós
- Nosso Trabalho (contadores animados)
- Projetos e Missões
- Segurança das equipes (parceria Insanos Moto Clube)
- Nossos Parceiros (carrossel)
- Seja Voluntário
- Doações Financeiras (dados bancários e PIX)
- Fale Conosco (formulário de contato)

---

## 🐱‍💻 Funcionalidades Principais

- **Menu mobile fullscreen** 
- **Header dinâmico** 
- **Scroll suavizado no desktop (lerp 0.1)**
- **Contadores animados** 
- **Carrossel de parceiros: Swiper.js com autoplay e responsivo**
- **Formulário de contato: Preenchimento automático do campo Assunto via cards**
- **Acessibilidade: VLibras integrado (Libras para deficientes auditivos)**
- **AOS Animations: Animações de entrada ao rolar a página**

---

## 🛠️ Tecnologias Utilizadas

### Frontend
- **HTML5** 
- **CSS3**
- **JavaScript Vanilla**

### Bibliotecas externas (CDN)
- **Swiper.js: Carrossel de parceiros**
- **AOS: Animações ao scroll**
- **Font Awesome: Ícones**
- **Google Fonts: Montserrat + Playfair Display**
- **VLibras Acessibilidade em Libras (Gov.br)**

---


## 🎨 Design & UX/UI
 
### Identidade Visual
- Paleta institucional azul (`#003d82`) + vermelho (`#e63946`) da ONG
- Tipografia: **Montserrat** (textos e UI) + **Playfair Display** (títulos editoriais)
- Design tokens centralizados em variáveis CSS (`:root`)
### Layout & Responsividade
- Totalmente responsivo: mobile, tablet e desktop
- Grid e Flexbox nativos, sem frameworks CSS
- Breakpoints principais: 768px (mobile) e 1024px (desktop)
- Imagens com `object-fit: cover` para nunca distorcer
### Interações & Animações
- Scroll com inércia no desktop (efeito lerp, desativado no mobile)
- Animações de entrada ao scroll via **AOS** (`fade-up`, `zoom-in`, `fade-right`)
- Contadores numéricos animados ao entrar na viewport
- Header transparente que ganha fundo sólido ao rolar (`.scrolled`)
- Hover com transições suaves em botões, cards e links (25+ estados `:hover`)
### Navegação
- Navegável por teclado: todos os links e botões são elementos nativos (`<a>`, `<button>`)
- Foco visível nos campos do formulário (outline azul com box-shadow)
- Scroll suave por âncora entre seções (`scroll-behavior: smooth`)
- Menu mobile fecha automaticamente ao selecionar uma seção
### Acessibilidade
- **VLibras** integrado: tradução em Libras para deficientes auditivos (padrão Gov.br)
- Todas as imagens com atributo `alt` descritivo
- Hierarquia semântica de headings (`h1` → `h2` → `h3`)
- Contraste de cores adequado entre texto e fundo

---

*Uso exclusivo da Associação Médicos do Mundo Brasil — São Paulo, SP (2026).*
