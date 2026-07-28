# Benício Advogados — site institucional

Site institucional (landing page única) do escritório **Benício Advogados**,
especializado em **Direito Criminal** e **Direito Imobiliário**, em
**Petrolina-PE**.

## Estrutura

```
index.html        página completa (HTML + CSS + JS num só arquivo)
assets/           logos, símbolo, retratos e imagem de compartilhamento
robots.txt        libera indexação e aponta o sitemap
sitemap.xml       sitemap com a URL canônica
.nojekyll         desliga o processamento Jekyll (compatibilidade)
```

## Manual de Marca

As cores institucionais são definidas em `:root` no `index.html` e devem ser
respeitadas em qualquer alteração visual:

| Nome           | Hex       | Uso                                  |
| -------------- | --------- | ------------------------------------ |
| Verde Toga     | `#1B3A2D` | Cor institucional e dominante        |
| Ouro Benício   | `#C9A84C` | Prestígio, uso pontual (detalhes)    |
| Areia Cartório | `#F2EDE3` | Fundo claro oficial                  |

Variações auxiliares (verde-sessão, ouro-velho, tons com opacidade) já
existem no CSS e servem para profundidade/hierarquia — não introduzir cores
fora dessa paleta.

## Publicidade advocatícia (Provimento 205/2021 da OAB)

Todo texto do site — página, FAQ, chamadas de WhatsApp, metadados de SEO —
precisa respeitar as regras de publicidade da advocacia. Ao escrever ou
revisar conteúdo, evitar:

- Promessa de resultado ou captação de causídica (garantir vitória, "resolve
  seu problema", etc.);
- Comparação com outros advogados/escritórios ou uso de superlativos não
  comprováveis ("o melhor", "número 1");
- Mercantilização (preço, desconto, promoção, parcelamento em destaque);
- Uso de termos que sugiram urgência/pressão comercial;
- Menção a clientes ou casos concretos sem autorização/anonimização.

É permitido: informação objetiva sobre áreas de atuação, linguagem
institucional e sóbria, dados de contato, currículo e trajetória dos
advogados.

## Publicação

Hospedado na **Vercel**, com deploy automático a cada push na branch
`main`.
