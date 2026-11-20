# ImersÃ£o Vibe Coding â€” Landing Promocional

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


Quatro versÃµes de landing page de vendas para a **ImersÃ£o Vibe Coding** (Do Zero ao SaaS com IA em 3 dias, presencial em ItaguaÃ­ â€” RJ).

ðŸ”— **Online (GitHub Pages):** https://inematds.github.io/imersaovc/

## VersÃµes

| Arquivo | Estilo | Quando usar |
|---|---|---|
| [`versao-1.html`](versao-1.html) | **ConversÃ£o direta** â€” oferta, escassez, FAQ de objeÃ§Ãµes | trÃ¡fego quente / anÃºncio |
| [`versao-2.html`](versao-2.html) | **Storytelling** â€” jornada antesâ†’depois, editorial, depoimentos | desejo e confianÃ§a |
| [`versao-3.html`](versao-3.html) | **Visual ousado** â€” hero animado, glass, contadores, motion | impacto imediato |
| [`versao-4.html`](versao-4.html) | **ImersÃ£o presencial (formato completo, recomendada)** â€” hero com vÃ­deo, datas/local, "Acesso Ã  ImersÃ£o Presencial", jornada dia a dia, barra de vagas | pÃ¡gina de vendas pronta |

`index.html` Ã© um seletor que mostra as 4. Quando decidir a versÃ£o final, **renomeie o arquivo dela para `index.html`**.

## Oferta (jÃ¡ configurada nas pÃ¡ginas)

- De **R$ 4.800** por **R$ 3.000** (oferta de lanÃ§amento)
- **Pagamento:** cartÃ£o de crÃ©dito em **atÃ© 6x**
- **20 vagas** por imersÃ£o

## Pagamento via Asaas

Mesmo padrÃ£o usado no **inema.vip**: o botÃ£o de CTA aponta direto para o **link de checkout do Asaas** (`https://www.asaas.com/c/XXXX`).

**JÃ¡ configurado.** O botÃ£o "Garantir vaga" das 4 versÃµes aponta para o link real:

- R$ 3.000 (cartÃ£o, atÃ© 6x) â†’ `https://www.asaas.com/c/hkzrb361iks95c50`

Para trocar o link, basta substituir essa URL nos `versao-*.html`.

> ðŸ“„ **Como gerenciar os links pela API** (criar, mudar forma de pagamento, parcelas, valor, excluir): [`docs/asaas-links-pagamento.md`](docs/asaas-links-pagamento.md).

### CobranÃ§a dinÃ¢mica (opcional)

Para gerar cobranÃ§as via API (customer + payment, webhook de confirmaÃ§Ã£o, controle automÃ¡tico de vagas), o cliente de referÃªncia jÃ¡ existe em `inemaonline` (`worker/src/asaas.ts`): cria customer, cria payment, processa webhook `PAYMENT_CONFIRMED`/`PAYMENT_RECEIVED`.

## Editar datas/local

As pÃ¡ginas usam o local **ItaguaÃ­ â€” RJ, Rua Prefeito JosÃ© Maria de Brito, 251** e o texto _"PrÃ³xima turma â€” datas a confirmar"_. Procure pelos comentÃ¡rios `EDITAR-DATAS` para colocar as datas reais.

## Stack

HTML estÃ¡tico + Tailwind (CDN) + Google Fonts. Sem build. Abre direto no navegador.

---
INEMA.CLUB Â· 2026

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>