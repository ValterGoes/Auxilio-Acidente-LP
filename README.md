Auxílio-Acidente — Maragonesa Silveira Advocacia

Landing page institucional focada em auxílio-acidente (benefício do INSS), desenvolvida para captação de leads via Google Ads e WhatsApp para o escritório Maragonesa Silveira Advocacia & Consultoria.

Sobre a página

Página única (one-page), dividida em seções pensadas para conversão:

Hero — proposta de valor direta, com vídeo explicativo e CTA para WhatsApp.
Sobre / Como funciona — quem tem direito, tipos de acidente cobertos e a conexão com o Direito do Trabalho (CAT, estabilidade, indenização).
Perguntas Frequentes — dúvidas comuns sobre o benefício, em formato de acordeão.
CTA final — reforço de confiança e botão de contato direto pelo WhatsApp.

Inclui também um botão flutuante de WhatsApp (aparece a partir da segunda seção) e rastreamento de conversão para campanhas de Google Ads.

Tecnologias
HTML5 semântico
CSS3 puro (sem framework), com variáveis CSS para cores, espaçamentos e tipografia
JavaScript vanilla (sem dependências) para:
incorporação do vídeo do YouTube sob demanda (clique para carregar)
acordeão da seção de FAQ
exibição do botão flutuante de WhatsApp via IntersectionObserver
Google Fonts — Montserrat (títulos) e Roboto (texto)
Schema.org (JSON-LD) — dados estruturados de LegalService e FAQPage para SEO e rich snippets
Google Ads / GA4 (gtag.js) — rastreamento de conversão nos cliques de WhatsApp
Estrutura do projeto
.
├── index.html
├── style.css
└── images/
    ├── favicon.ico
    ├── logo_azul.png
    ├── logo_branco.png
    └── logo-valtergoes.svg
Como rodar localmente

Não há build nem dependências — é só abrir o index.html no navegador, ou servir a pasta com qualquer servidor estático:

bash
npx serve .
Configuração antes de publicar

Alguns pontos ainda estão como placeholder no código e precisam ser preenchidos antes do deploy:

ID de conversão do Google Ads (GT-XXXXXXX, no <head>)
URL final do domínio (usada no canonical, Open Graph e dados estruturados)
Endereço completo do escritório (nos dados estruturados)
Imagem de compartilhamento (og:image, 1200×630px)
Créditos

Desenvolvido por Valter Goes.
