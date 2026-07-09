# Site — Kit Aprova Educação

Site estático puro (HTML + Tailwind via CDN + CSS). Sem build, sem dependências, sem Node necessário para rodar — só abrir os arquivos ou publicar direto.

## Páginas

- `index.html` — Landing page principal
- `produto.html` — Detalhamento do que está incluso no kit
- `sobre.html` — Página institucional
- `faq.html` — Perguntas frequentes (com schema FAQPage para SEO)
- `checkout.html` — Ponte para o checkout externo (Hotmart/Kiwify) — **substitua o link antes de publicar**
- `obrigado.html` — Página de agradecimento pós-compra
- `blog/index.html` + 3 artigos completos — conteúdo SEO (ver `../07-SEO` para a lista completa de pautas)

## Publicar gratuitamente (2 opções)

### Opção 1 — Cloudflare Pages (recomendado)
1. Crie conta gratuita em pages.cloudflare.com.
2. "Create a project" → "Upload assets" → arraste a pasta `04-SITE` inteira.
3. Pronto: recebe uma URL `*.pages.dev`. Depois é possível ligar um domínio próprio de graça.

### Opção 2 — GitHub Pages
1. Crie um repositório no GitHub e envie o conteúdo da pasta `04-SITE` para a raiz (ou para uma pasta `/docs`).
2. Settings → Pages → escolha a branch/pasta → salvar.
3. O site fica disponível em `usuario.github.io/repositorio`.

## Antes de publicar (checklist)

- [ ] Substituir o link de checkout em `checkout.html` pelo link real da Hotmart/Kiwify.
- [ ] Substituir `SEU-DOMINIO.com.br` em `robots.txt` e `sitemap.xml` pelo domínio real.
- [ ] Trocar os placeholders "Mockup do Kit" por imagens reais (capa do ebook, prints da planilha) em `assets/img/`.
- [ ] Configurar Google Search Console e enviar o `sitemap.xml`.
- [ ] Conectar um formulário de e-mail (Brevo/Mailchimp free) para a isca digital — ver `../08-AUTOMACOES`.
