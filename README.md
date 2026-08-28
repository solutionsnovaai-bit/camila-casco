# Camila Casco — Embracon Anália Franco

Site estático (HTML + CSS + JS puro). Sem build, sem dependência.

## Estrutura

```
index.html
css/style.css
js/script.js
assets/
  ├── camila-hero.jpg        ← foto do hero
  ├── camila-retrato.jpg     ← retrato P&B (seção "Quem atende")
  ├── simbolo-vermelho.png   ← mão Embracon, fundo transparente
  ├── simbolo-branco.png     ← versão branca (CTA final)
  └── mao-*-p1..p4.png       ← peças da mão (loader e Modalidades)
```

## Deploy

1. `git init` → `git add .` → `git commit -m "first"`
2. Push pro GitHub
3. Vercel → Import repo → Framework: **Other** → Deploy

## ANTES DE PUBLICAR — obrigatório

| O quê | Onde |
|---|---|
| **WhatsApp da Camila** | `js/script.js`, linha `var WPP` — está com placeholder `5511900000000`. Trocar também o número visível no rodapé |
| **Instagram** | buscar `INSTAGRAM_DA_CAMILA` no `index.html` |
| Endereço | rodapé, bloco "Unidade" (está o da unidade Anália Franco) |
| Anos de casa | hero (`data-count="10"`) e badge da seção "Quem atende" |

## Cores da marca

Manual da Embracon: fundo sempre claro, vermelho + branco + carvão.

- Vermelho Embracon: `#E30613`
- Carvão (texto): `#1A1A1A`
- Papel (fundo): `#FAF8F5`
- Papel alternado / branco: `#F3EEE7` / `#FFFFFF`

## Tipografia

Versão refinada do padrão Embracon — serif como protagonista:

- **Bodoni Moda** — títulos, nomes de seção e números (peso 500, caixa normal)
- **Bodoni Moda itálico vermelho** — o fecho de cada título
- **Sora 300** — corpo de texto, entrelinha ampla
- **JetBrains Mono** — rótulos, marquee e microtextos

Sem a palavra "CEO" em nenhum ponto do site: o cargo aparece como
**Empresária à frente da unidade Anália Franco**.

---
Nova AI Solutions
