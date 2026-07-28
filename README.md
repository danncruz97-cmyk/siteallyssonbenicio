# Benício Advogados — site institucional

Página única (landing page) do escritório Benício Advogados.
Direito Criminal e Direito Imobiliário · Petrolina-PE.

## Estrutura

```
index.html        página completa (HTML + CSS + JS num só arquivo)
assets/           logos, símbolo, retratos e imagem de compartilhamento
robots.txt        libera indexação e aponta o sitemap
sitemap.xml       sitemap com a URL canônica
.nojekyll         desliga o processamento Jekyll no GitHub Pages
```

## Onde editar o que

| O que mudar | Onde |
| --- | --- |
| Números de WhatsApp | bloco `CONFIG` no `<script>`, no fim do `index.html` |
| Cores da marca | variáveis CSS em `:root` (conforme Manual de Marca, seção 13) |
| Textos, serviços, FAQ | direto no HTML das respectivas `<section>` |
| Dados para o Google | bloco `application/ld+json` no `<head>` |
| Imagem de compartilhamento | `assets/og-image.jpg` (1200x630) |

Trechos que ainda precisam de revisão estão marcados com `EDITE AQUI`.

## Publicação

Hospedado no GitHub Pages, a partir da branch `main`, pasta raiz.
