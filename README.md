# Contech — landing page da consultoria

Landing page de serviço da **Contech**: vende a consultoria de software
sob medida (site institucional, landing page e SaaS) pra pequenos negócios e
comércio local. Usa o [Convito](https://convito-nine.vercel.app/) — produto
próprio da Contech, já usado em 50+ festas — como case de prova social.

Não confundir com a [LandPageConvito](../LandPageConvito): aquela vende o
Convito como produto; esta vende a Contech como consultoria.

## Stack

Página estática, sem build nem dependências:

- `index.html` — HTML + CSS + JavaScript puro (vanilla)
- `fonts.css` — mesmas fontes da LandPageConvito (Unbounded, Plus Jakarta
  Sans, JetBrains Mono) embutidas como `data:` URI, reaproveitadas para
  manter a identidade visual da marca; funciona offline
- Tema claro/escuro automático (`prefers-color-scheme`)
- Mesma paleta de cores e tokens de design da LandPageConvito

## Rodando localmente

```bash
# Windows
start index.html
```

## Deploy

HTML estático, publica em qualquer hospedagem sem configuração:

- **GitHub Pages**: Settings → Pages → Deploy from branch
- **Vercel / Netlify**: importe o repositório, sem build command

## Publicado em

https://maiconqatech.github.io/contech-consultoria/

Repositório separado do [contech](https://github.com/maiconqatech/contech)
(que hospeda a LandPageConvito) para não sobrescrever a página do Convito já
no ar.

## Decisões de negócio

- Suporte/manutenção pós-entrega é **pago à parte**, não incluído no valor
  do projeto — por isso não entra como diferencial em destaque na página,
  só como resposta honesta na FAQ.

## Contato

WhatsApp: [(15) 99734-1422](https://wa.me/5515997341422)
