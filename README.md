# Slides — Oficina "Segurança Digital"

Apresentação da oficina presencial de extensão curricular (Unisanta, Análise e Desenvolvimento de Sistemas): como reconhecer e evitar golpes pela internet no dia a dia, com os resultados de um questionário aplicado à comunidade, exemplos de golpes comuns, sinais de alerta, como se proteger e a verificação em duas etapas do WhatsApp.

Publicada em **https://bornadin.github.io/extensao-slides/** (GitHub Pages, branch `master`; todo push publica).

## Como usar

Página única, sem dependências: abra `index.html` no navegador ou use o link acima.

| Tecla / gesto | Ação |
|---|---|
| ← → , espaço, clique, swipe | navegar |
| F | tela cheia |
| P | imprimir (um slide por página) |
| ? | lista de atalhos |

O número do slide fica na URL (`#6`), então dá para retomar de onde parou ou mandar o link de um slide específico.

## Arquivos

```
index.html        a apresentação (HTML + CSS + JS inline, identidade visual Unisanta)
assets/           logo
dist/artifact.html  cópia single-file com o logo embutido, para hospedar em qualquer lugar
docs/superpowers/specs/  spec da apresentação (conteúdo, ordem dos slides, decisões)
```

## Editar

Os slides são `<section>` dentro de `index.html`; o texto, a ordem e as notas estão lá. Depois de editar, regenerar `dist/artifact.html` embutindo o logo em base64 (ou copiar `index.html` + `assets/` para onde for hospedar).
