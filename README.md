### Desafio de Código - Construindo um Layout Responsivo Para o Site do Discord Com CSS #

Projeto de HTML e CSS clonando a página do Discord usando conceitos de Responsividade e Mobile First.

Desafio de código do curso CSS Developer - DIO 

🚀 Projeto: Clone da Página Inicial do Discord
Este projeto é um clone da página inicial do Discord, desenvolvido para praticar e aplicar técnicas modernas de HTML e CSS, focando em responsividade, performance e manutenibilidade do código.

🛠️ Tecnologias Utilizadas
HTML5 (Estrutura Semântica)

CSS3 (Estilização e Layout Responsivo)

Flexbox (Sistema de Layout)

Media Queries (Responsividade)


# 🚀 Projeto: Clone da Página Inicial do Discord

Este projeto é um clone da página inicial do Discord, desenvolvido para praticar e aplicar técnicas modernas de HTML e CSS, focando em responsividade, performance e manutenibilidade do código.

---

### 🛠️ Análise Detalhada de Recursos e Técnicas

#### 🌟 I. Recursos e Técnicas no HTML (Estrutura)

| Recurso / Técnica | Descrição | Benefícios Chave |
| :--- | :--- | :--- |
| **HTML Semântico (HTML5)** | Utiliza tags com significado, como `<section>`, `<footer>` e organiza os títulos (`h1`, `h2`, `h3`). | Acessibilidade aprimorada e melhor **SEO**. |
| **Tags `<picture>`** | Uso de `<picture>` e `<source media="...">` para servir a imagem mais otimizada conforme a largura da tela. | **Performance:** Otimiza o tempo de carregamento em dispositivos móveis. |
| **Favicon Adicionado** | Inclusão das tags `<link rel="icon"...>` para exibir o ícone do site na aba do navegador. | **Identidade Visual** e profissionalismo. |
| **Nomenclatura Reutilizável** | Adoção de classes modulares como `.container`, `.feature-block` e classes de botões (`.btn-primary`). | **Manutenibilidade:** Código mais limpo e estilos facilmente aplicáveis. |

#### 🎨 II. Recursos e Técnicas no CSS (Estilo e Layout)

| Recurso / Técnica | Descrição | Benefícios Chave |
| :--- | :--- | :--- |
| **CSS Reset e Correção** | `* { box-sizing: border-box; }` e remoção do `width: 100vw;` do `body`. | **Correção de Layout:** Elimina a barra de rolagem horizontal indesejada e simplifica cálculos de layout. |
| **Variáveis CSS (`:root`)** | Definição de cores e fontes globais (`--color-dark`, `--font-body`) no seletor `:root`. | **Manutenção:** Facilita a gestão e mudança de temas ou paletas de cores. |
| **Flexbox Avançado** | Uso de `flex-direction: column` (mobile) e `flex-direction: row` (desktop). Classe `.reverse-on-desktop` para inversão de ordem. | **Layout Dinâmico e Responsivo:** Cria seções alinhadas de forma eficiente e adaptável. |
| **Media Queries** | Uso de `@media screen and (min-width: 1280px)` para ajustar tamanhos de fonte e layout. | **Responsividade:** Garante uma experiência otimizada em todas as resoluções de tela. |
| **Efeitos de hover** | Adicionado `transition: all 0.3s ease;` e sombras para feedback visual em botões. | **Interação:** Melhora a experiência do usuário. |

---
