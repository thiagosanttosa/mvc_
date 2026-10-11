MVC CROCHÊS — LANDING PAGE ARTESANAL

NOVA IDENTIDADE VISUAL
- Azul pastel: #A9C8F7
- Azul acinzentado: #426779
- Branco gelo: #F8FCFD
- Azul névoa: #E8F2F9
- Azul claro para bordas: #B4D0F7
- Branco puro: #FFFFFF

ARQUIVOS DO PROJETO
- index.html: estrutura semântica, cards modernos com botões de orçamento direto para o WhatsApp, links do Instagram e responsividade
- style.css: identidade visual reestilizada com a paleta azul/branco, contornos arredondados, tipografia elegante e sombras suaves
- server.js: servidor local estático nativo em Node.js (sem dependências externas)
- package.json: script de inicialização ("npm start")
- assets/: fotos reais das peças de crochê da marca

ANTES DE PUBLICAR
1. Abra index.html e procure por 55SEUNUMERO.
2. Substitua o texto 55SEUNUMERO em todos os links pelo telefone de WhatsApp oficial com código do país e DDD (somente dígitos).
   Exemplo: 5531999999999
3. Verifique o link do perfil do Instagram no rodapé (atualmente configurado para https://www.instagram.com/mvc_croches/).

COMO EXECUTAR LOCALMENTE
1. Certifique-se de ter o Node.js instalado (versão LTS recomendada: https://nodejs.org/).
2. Abra um terminal na pasta do projeto:
   cd c:\Users\thiago\Desktop\projetos\landingpagemvc\mvc_croches_landing
3. Execute o comando:
   npm start
   (ou: node server.js)
4. Abra o navegador no endereço:
   http://localhost:3000

Observações:
- Não é necessário executar 'npm install', pois o servidor utiliza unicamente a biblioteca padrão do Node.js.
- As fontes (Playfair Display e Plus Jakarta Sans) são carregadas via Google Fonts, com fallback limpo para fontes locais do sistema caso esteja offline.
