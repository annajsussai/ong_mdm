<div align="center">
  <img src="./images/logos/logo_sem_texto.png" width="80" height="80" alt="Logo Médicos do Mundo">
  <h1>Landing Page - Médicos do Mundo Brasil</h1>
</div>

<div align="center">
  <img src="https://img.shields.io/badge/status-produtivo-green" alt="Status">
  <img src="https://img.shields.io/badge/HTML5-orange" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-blue" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-Vanilla-yellow" alt="JavaScript">
</div>

Landing page institucional da **Associação Médicos do Mundo Brasil**, apresentando projetos, missões, parcerias e canais de doação e voluntariado.

---

## 🔗 Link do Projeto

- **Produção:** [https://annajsussai.github.io](https://annajsussai.github.io)

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

- **Menu mobile fullscreen** — overlay em tela cheia com animação suave
- **Header dinâmico** — muda visual ao rolar a página (`.scrolled`)
- **Scroll com inércia** — efeito de scroll suavizado no desktop (lerp 0.1)
- **Contadores animados** — números sobem ao entrar na viewport
- **Carrossel de parceiros** — Swiper.js com autoplay e responsivo
- **Formulário de contato** — preenchimento automático do campo Assunto via cards
- **Acessibilidade** — VLibras integrado (Libras para deficientes auditivos)
- **AOS Animations** — animações de entrada ao rolar a página

---

## 🛠️ Tecnologias Utilizadas

### Frontend
- **HTML5** — Estrutura semântica
- **CSS3** — Estilização responsiva com variáveis CSS (design tokens)
- **JavaScript Vanilla** — Toda lógica sem frameworks

### Bibliotecas externas (CDN)
- **Swiper.js** — Carrossel de parceiros
- **AOS** — Animações ao scroll
- **Font Awesome** — Ícones
- **Google Fonts** — Montserrat + Playfair Display
- **VLibras** — Acessibilidade em Libras (Gov.br)

---

## 📁 Estrutura de Arquivos

```
/
├── index.html          # Arquivo principal (todo HTML, CSS e JS inline)
├── images/
│   ├── logos/          # Logotipos da ONG
│   ├── parceiros/      # Logos dos parceiros
│   └── *.jpg / *.png   # Imagens das seções
```

---

## 🎨 Design Tokens (Cores)

Edite as variáveis no `:root` dentro do `<style>` do `index.html`:

| Variável | Valor | Uso |
|---|---|---|
| `--primary-blue` | `#003d82` | Cor principal |
| `--accent-red` | `#e63946` | Destaque vermelho |
| `--accent-coral` | `#ff6b6b` | Botões e hovers |
| `--dark` | `#1a1a2e` | Fundo escuro / menu |

---

## ⚙️ Manutenção

- **Adicionar parceiro:** incluir novo `<div class="swiper-slide">` dentro de `.partnersSwiper`
- **Alterar velocidade do scroll suavizado:** ajustar `ease` no script de inércia (0.05 = lento, 0.2 = rápido)
- **Alterar contadores:** editar atributo `data-target` nos elementos `.counter`
- **Cores globais:** editar variáveis CSS no `:root`

---

*Uso exclusivo da Associação Médicos do Mundo Brasil — São Paulo, SP (2026).*
