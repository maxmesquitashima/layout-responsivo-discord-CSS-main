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


I. Recursos e Técnicas no HTML (Estrutura)Recurso / TécnicaDescriçãoBenefícios ChaveHTML Semântico (HTML5)Utilização de tags com significado, como <section>, <footer> e organização hierárquica dos títulos (h1, h2, h3).Acessibilidade aprimorada e melhor SEO.Tags <picture>Uso combinado das tags <picture> e <source media="..."> para servir a imagem mais otimizada conforme a largura da tela.Performance: Otimiza o tempo de carregamento em dispositivos móveis.Favicon AdicionadoInclusão das tags <link rel="icon"...> para exibir o ícone do site na aba do navegador.Identidade Visual e profissionalismo.Nomenclatura ReutilizávelAdoção de classes modulares como .container, .feature-block e classes de botões (e.g., .btn-primary).Manutenibilidade: Código mais limpo e estilos facilmente aplicáveis a outros elementos.II. Recursos e Técnicas no CSS (Estilo e Layout)Recurso / TécnicaDescriçãoBenefícios ChaveCSS Reset e Correção de LarguraAplicação de * { box-sizing: border-box; } e remoção do width: 100vw; do body.Correção de Layout: Elimina a barra de rolagem horizontal indesejada (overflow-x: hidden) e simplifica cálculos de layout.Variáveis CSS (:root)Definição de cores e fontes globais (--color-dark, --font-body) no seletor :root.Manutenção: Facilita a gestão e mudança de temas ou paletas de cores.Flexbox AvançadoUso de flex-direction: column (mobile) e flex-direction: row (desktop, via Media Queries). A classe .reverse-on-desktop inverte a ordem dos elementos em telas grandes.Layout Dinâmico e Responsivo: Cria seções alinhadas de forma eficiente e adaptável.Media QueriesUso de @media screen and (min-width: 1280px) para ajustar tamanhos de fonte (h1, h2) e layout.Responsividade: Garante uma experiência otimizada em todas as resoluções de tela.Efeitos de hoverAdicionado transition: all 0.3s ease; e sombras para fornecer feedback visual em botões.Interação: Melhora a experiência do usuário ao interagir com o site.