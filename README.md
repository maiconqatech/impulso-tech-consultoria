# Impulso Tech — landing page da consultoria

Landing page de serviço da **Impulso Tech**: vende a consultoria de software
sob medida (site institucional, landing page e SaaS) pra pequenos negócios e
comércio local. Usa o [Convito](https://convito-nine.vercel.app/) — produto
próprio da Impulso Tech, já usado em 50+ festas — como case de prova social.

Não confundir com a [LandPageConvito](../LandPageConvito): aquela vende o
Convito como produto; esta vende a Impulso Tech como consultoria.

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

https://maiconqatech.github.io/impulso-tech-consultoria/

Repositório separado do [impulsoTech](https://github.com/maiconqatech/impulsoTech)
(que hospeda a LandPageConvito) para não sobrescrever a página do Convito já
no ar.

## Pendências

- [ ] Gerar `og-image.png` para preview em redes sociais e WhatsApp
- [ ] Validar prazo de entrega real para incluir (ou não) na FAQ
- [ ] Revisar se "suporte pós-entrega" deve virar diferencial explícito

## Contato

WhatsApp: [(15) 99734-1422](https://wa.me/5515997341422)
