ï»¿# ImersêÂ£o Vibe Coding ê¢â¬â Landing Promocional

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


Quatro versêÂµes de landing page de vendas para a **ImersêÂ£o Vibe Coding** (Do Zero ao SaaS com IA em 3 dias, presencial em ItaguaêÂ­ ê¢â¬â RJ).

ê°Å¸ââ **Online (GitHub Pages):** https://linnoff88-dev.github.io/arckhe-/

## VersêÂµes

| Arquivo | Estilo | Quando usar |
|---|---|---|
| [`versao-1.html`](versao-1.html) | **ConversêÂ£o direta** ê¢â¬â oferta, escassez, FAQ de objeêÂ§êÂµes | trêÂ¡fego quente / anêÂºncio |
| [`versao-2.html`](versao-2.html) | **Storytelling** ê¢â¬â jornada antesê¢â âdepois, editorial, depoimentos | desejo e confianêÂ§a |
| [`versao-3.html`](versao-3.html) | **Visual ousado** ê¢â¬â hero animado, glass, contadores, motion | impacto imediato |
| [`versao-4.html`](versao-4.html) | **ImersêÂ£o presencial (formato completo, recomendada)** ê¢â¬â hero com vêÂ­deo, datas/local, "Acesso êÂ  ImersêÂ£o Presencial", jornada dia a dia, barra de vagas | pêÂ¡gina de vendas pronta |

`index.html` êÂ© um seletor que mostra as 4. Quando decidir a versêÂ£o final, **renomeie o arquivo dela para `index.html`**.

## Oferta (jêÂ¡ configurada nas pêÂ¡ginas)

- De **R$ 4.800** por **R$ 3.000** (oferta de lanêÂ§amento)
- **Pagamento:** cartêÂ£o de crêÂ©dito em **atêÂ© 6x**
- **20 vagas** por imersêÂ£o

## Pagamento via Asaas

Mesmo padrêÂ£o usado no **ARCKHÉ.vip**: o botêÂ£o de CTA aponta direto para o **link de checkout do Asaas** (`https://www.asaas.com/c/XXXX`).

**JêÂ¡ configurado.** O botêÂ£o "Garantir vaga" das 4 versêÂµes aponta para o link real:

- R$ 3.000 (cartêÂ£o, atêÂ© 6x) ê¢â â `https://www.asaas.com/c/hkzrb361iks95c50`

Para trocar o link, basta substituir essa URL nos `versao-*.html`.

> ê°Å¸ââ **Como gerenciar os links pela API** (criar, mudar forma de pagamento, parcelas, valor, excluir): [`docs/asaas-links-pagamento.md`](docs/asaas-links-pagamento.md).

### CobranêÂ§a dinêÂ¢mica (opcional)

Para gerar cobranêÂ§as via API (customer + payment, webhook de confirmaêÂ§êÂ£o, controle automêÂ¡tico de vagas), o cliente de referêÂªncia jêÂ¡ existe em `ARCKHÉonline` (`worker/src/asaas.ts`): cria customer, cria payment, processa webhook `PAYMENT_CONFIRMED`/`PAYMENT_RECEIVED`.

## Editar datas/local

As pêÂ¡ginas usam o local **ItaguaêÂ­ ê¢â¬â RJ, Rua Prefeito JosêÂ© Maria de Brito, 251** e o texto _"PrêÂ³xima turma ê¢â¬â datas a confirmar"_. Procure pelos comentêÂ¡rios `EDITAR-DATAS` para colocar as datas reais.

## Stack

HTML estêÂ¡tico + Tailwind (CDN) + Google Fonts. Sem build. Abre direto no navegador.

---
ARCKHÉ AI êÂ· 2026

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>