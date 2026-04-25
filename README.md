# 🌟 Guia de Atividades Motoras — Landing Page

## Visão Geral
Landing page de alta conversão, 100% mobile-first, para venda do **Guia de Atividades para Foco e Coordenação Infantil** — um método digital com +250 atividades práticas para mães aplicarem em casa com crianças de 3 a 10 anos.

---

## ✅ Funcionalidades Implementadas

### Blocos de Conversão (14 no total)
1. **Barra de Prova Social (topo fixo)** — "+2.200 famílias já aplicaram este método"
2. **Contador de Pessoas Online (fixo)** — número aleatório entre 9–27, atualiza a cada 15s com fade suave
3. **Bloco 1 — Headline** — texto em caixa alta com destaques em azul e amarelo, máx. 3 linhas
4. **Bloco 2 — Subheadline** — texto simples sem efeitos
5. **Bloco 3 — Dor Latente** — imagem real com 5 pensamentos sobrepostos (fundo vermelho transparente, bordas arredondadas, distribuídos pela imagem sem bloquear o centro)
6. **Bloco 4 — Transição para Solução** — card de pergunta com destaques sublinhados e impactantes
7. **Bloco 5 — Passo a Passo** — 3 passos com números grandes, conectados visualmente
8. **Bloco 6 — Transformação** — lista de 6 benefícios em cards brancos com ícone ✅
9. **Bloco 7 — O Que Recebe** — imagem do produto + 4 cards de features com ícones
10. **Bloco 8 — CTA de Acesso Imediato** — 3 micro-passos simplificados
11. **Bloco 9 — Ancoragem de Valor** — card de preço com itens riscados, preço final destacado e garantia de 7 dias
12. **Bloco 10 — Botão de Compra 1** — verde, grande, mobile-friendly
13. **Bloco 11 — Conversa Séria** — comparativo visual "Sem o guia vs Com o guia"
14. **Bloco 12 — Botão de Compra 2** — verde com animação pulse, texto mais impactante
15. **Bloco 13 — FAQ** — acordeão com 8 perguntas frequentes
16. **Bloco 14 — Rodapé** — fundo escuro, links legais, disclaimer

### Recursos de UX & Conversão
- ✅ Design 100% mobile-first (max-width: 520px no container)
- ✅ Fonte Inter (Google Fonts) — limpa e moderna
- ✅ Paleta: branco (#FFF), azul (#3B82F6), azul suave (#EEF6FF), verde (#16A34A), preto (#1A1A1A)
- ✅ Scroll fade-in com IntersectionObserver (animações suaves ao rolar)
- ✅ Stagger animation nos itens de lista
- ✅ Smooth scroll em âncoras
- ✅ Pulsação sutil no preço (senso de urgência)
- ✅ Animação de entrada na barra de prova social
- ✅ FAQ em acordeão com acessibilidade (aria-expanded)
- ✅ Sem erros no console (validado via Playwright)

---

## 📁 Estrutura de Arquivos

```
index.html          → Página principal com os 14 blocos
css/
  style.css         → Estilos completos, mobile-first
js/
  main.js           → Contador online, FAQ, animações, scroll
README.md           → Esta documentação
```

---

## 🔗 URIs e Endpoints

| Caminho | Descrição |
|---------|-----------|
| `/` ou `index.html` | Página única da landing page |
| `#dor` | Âncora — Bloco Dor Latente |
| `#transicao` | Âncora — Bloco Transição |
| `#passos` | Âncora — Passo a Passo |
| `#produto` | Âncora — O Que Recebe |
| `#preco` | Âncora — Ancoragem de Valor |
| `#cta1` | Âncora — Botão de Compra 1 |
| `#cta2` | Âncora — Botão de Compra 2 |
| `#faq` | Âncora — FAQ |

> ⚠️ **Ação necessária**: Substituir `href="#"` nos botões de compra pelo link real do checkout (ex: Hotmart, Kiwify, Cakto, etc.)

---

## 🎨 Design Tokens

| Token | Valor |
|-------|-------|
| Fundo principal | `#FFFFFF` |
| Fundo secundário | `#EEF6FF` |
| Cor principal | `#3B82F6` |
| Cor de ação (botão) | `#16A34A` / `#22C55E` |
| Texto principal | `#1A1A1A` |
| Texto secundário | `#333` / `#555` |
| Fonte | Inter (Google Fonts) |

---

## 🚀 Próximos Passos Recomendados

1. **Substituir link dos botões** de compra pelo URL real do checkout
2. **Adicionar pixel de rastreamento** (Facebook Pixel, Google Tag Manager)
3. **Testar velocidade** no Google PageSpeed Insights (mobile)
4. **A/B Testing** no headline (versão A atual vs variação)
5. **Adicionar depoimentos reais** com foto e nome (bloco entre Transformação e Produto)
6. **Temporizador de escassez** (countdown timer) se houver oferta por tempo limitado
7. **Vídeo VSL** opcional logo abaixo do hero para aumentar tempo de sessão

---

## ⚠️ Regras do Produto (implementadas)

- ✅ NÃO menciona "PDF" ou "e-book"
- ✅ NÃO tem botão fixo de CTA
- ✅ NÃO tem botão no rodapé ou cabeçalho
- ✅ NÃO parece artigo ou curso
- ✅ Apresentado como "método", "guia" e "sistema"

---

*© 2026 Guia de Atividades Motoras*
