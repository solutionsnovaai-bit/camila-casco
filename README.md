# Camila Casco — Embracon Anália Franco

Site estático (HTML + CSS + JS puro). Sem build, sem dependência.

## Estrutura

```
index.html
css/style.css
js/script.js
assets/
  ├── camila-hero.jpg        ← foto do hero
  ├── casal-1.jpg / casal-2.jpg  ← fotos do casal (seção "Sobre nós")
  ├── simbolo-vermelho.png   ← mão Embracon, fundo transparente
  ├── simbolo-branco.png     ← versão branca (CTA final)
  └── mao-*-p1..p4.png       ← peças da mão (loader e Modalidades)
```

## Deploy

1. `git init` → `git add .` → `git commit -m "first"`
2. Push pro GitHub
3. Vercel → Import repo → Framework: **Other** → Deploy

## Antes de publicar — conferir

| O quê | Onde |
|---|---|
| WhatsApp | `js/script.js`, linha `var WPP = '5511995288898';` — muda em um lugar só, o script reescreve todos os links |
| Instagram | `@camilacasco` no `index.html` |
| Endereço | rodapé, bloco "Unidade" (está o da unidade Anália Franco) |


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
**Empresária à frente da unidade Anália Franco**, e o selo da seção
"Quem atende" traz **Sócia · Embracon Anália Franco**.

O site não faz nenhuma afirmação sobre tempo de casa.

---
Nova AI Solutions

## Seção "Sobre nós"

É a mesma estrutura nos dois sites (camila / rafael), com o texto individual
invertido e a barra vermelha destacando a frente de quem é dono daquele site:

- **Rafael Ferraz** — Comercial
- **Camila Casco** — Financeiro e administrativo

Os dois aparecem como **casados e proprietários da franquia Embracon Anália
Franco**. As fotos do casal ficam em `assets/casal-1.jpg` e `casal-2.jpg`,
sem filtro e sem overlay.
