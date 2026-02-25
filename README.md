# WS Liss — Landing Page Institucional

Landing page profissional desenvolvida para a marca **WS Liss Professional Hair**, focada na captação de revendedores e cabeleireiras.

---

## 🖥️ Visão Geral

Página de vendas single-page com design mobile-first, carrossel de produtos por categoria, seção de depoimentos, formulário de qualificação e integração com WhatsApp.

**URL de produção:** `(adicionar após publicação)`

---

## 📁 Estrutura do Projeto

```
wsliss-landing-page/
└── wsliss-landing-page.html   # Arquivo único autossuficiente
```

> ⚠️ O projeto é um **único arquivo HTML** com todas as imagens embutidas em base64. Não depende de arquivos externos — exceto a fonte Montserrat carregada via Google Fonts.

---

## 🎨 Design System

| Token | Valor | Uso |
|---|---|---|
| `--green-deep` | `#1B4332` | Fundo hero, navbar, footer |
| `--green-dark` | `#2D6A4F` | Elementos secundários |
| `--green-mid` | `#52917C` | Acentos, links |
| `--green-light` | `#7CAF8E` | Destaques, accent text |
| `--cream` | `#F5ECD7` | Textos, backgrounds secundários |

**Tipografia:** Montserrat (Google Fonts) — pesos 300 a 900

---

## 📱 Responsividade

| Breakpoint | Layout |
|---|---|
| `< 640px` | Mobile — coluna única, imagem abaixo do texto |
| `640px – 900px` | Tablet — grid 2 colunas nos produtos |
| `> 900px` | Desktop — hero split 48/52, grid 3 colunas |

---

## 🗂️ Seções

1. **Navbar** — Logo + menu desktop + hambúrguer mobile + CTA revendedor
2. **Hero** — Headline, subheadline, proof pills, 2 CTAs, foto da modelo
3. **Stats Band** — 4 números de credibilidade
4. **Problema (P.A.S.)** — 3 dores + virada estratégica
5. **Sobre a Marca** — Métricas e diferenciais
6. **Produtos** — Carrossel filtrado por 5 categorias (17 produtos)
7. **Depoimentos** — Cards + placeholders para expansão
8. **Como Funciona** — 3 passos + bloco de garantia
9. **FAQ** — 5 perguntas em accordion
10. **Formulário** — Qualificação do revendedor (6 campos)
11. **Footer** — Contato, redes sociais, mapa do site

---

## 🛍️ Catálogo de Produtos

### Alisamento & Botox
- Organic Liss B.tox
- 4D Gloss Redutor de Volume
- Afro Liss
- Plástica dos Fios Rosê Gold
- Botox Orgânico
- Botox 4D

### Tratamento
- Zero Metais
- Cauter Hair Pro (kit)
- Reconstruliss (kit)
- Anabolizante Capilar

### Finalizadores
- UseDay Protetor Térmico
- Sérum Semi de Lino
- Sérum Argan Oil
- Parfun Perfume Capilar

### Home Care
- Kit Cauter Hair 300ml
- Kit Reconstruliss Home
- Máscara Ouro Puro

### Descoloração
- Pó Descolorante Luminance
- Emulsão Oxidante OX 30

---

## ⚙️ Funcionalidades JavaScript

- **Navbar** — Scroll detection com mudança de estilo
- **Menu mobile** — Toggle hambúrguer
- **Scroll reveal** — Animações via `IntersectionObserver`
- **FAQ Accordion** — Abertura/fechamento animado
- **Carrossel de produtos** — Filtro por categoria, prev/next, dots, counter, swipe touch, resize handler
- **Formulário** — Feedback visual no submit
- **WhatsApp flutuante** — Botão fixo no canto inferior direito

---

## 📞 Contatos Configurados

| Canal | Valor |
|---|---|
| WhatsApp | (88) 9807-5391 |
| Instagram | @wslissprofissional |
| Facebook | [Perfil WS Liss](https://www.facebook.com/profile.php?id=61588022105641) |

---

## 🚀 Como Publicar

### Opção 1 — Netlify (Recomendado, Gratuito)
1. Acesse [netlify.com/drop](https://netlify.com/drop)
2. Arraste o arquivo `wsliss-landing-page.html`
3. Copie a URL gerada ou configure um domínio próprio

### Opção 2 — GitHub Pages (Gratuito)
1. Crie um repositório no GitHub
2. Faça upload do arquivo `wsliss-landing-page.html`
3. Renomeie para `index.html`
4. Vá em **Settings → Pages → Branch: main → Save**
5. Acesse: `https://seuusuario.github.io/nome-do-repositorio`

### Opção 3 — Hospedagem Tradicional (Hostinger, KingHost, etc.)
1. Acesse o painel da hospedagem
2. Vá em **File Manager → public_html**
3. Faça upload do arquivo e renomeie para `index.html`
4. Aponte seu domínio para a hospedagem

---

## 🔧 Como Atualizar

### Trocar imagens
As imagens estão embutidas em **base64** diretamente no HTML. Para substituir, encode a nova imagem em base64 e substitua o valor no atributo `src` do elemento correspondente.

### Atualizar número de WhatsApp
Busque por `wa.me/` no arquivo e atualize o número em todos os links.

### Adicionar produtos
Localize a seção `<!-- ═══ PRODUTOS ═══ -->` no HTML e duplique um bloco `.p-card` existente, ajustando o conteúdo e a categoria (`data-cat`).

---

## 📄 Licença

Projeto desenvolvido exclusivamente para **WS Liss Professional Hair**. Todos os direitos reservados.
