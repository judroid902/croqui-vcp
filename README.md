# Croqui de Vistoria

App para desenhar o croqui da vistoria no tablet, sobre grade de 0,5 m, e exportar em PNG, PDF (com fotos), DXF (CAD) e JSON.
Funciona sem internet depois de instalado. Os desenhos e as fotos ficam salvos só no aparelho; este repositório contém apenas o programa.

Versão atual: 0.4 — paredes curvas, espessura e tipo de parede, pavimento de baixo como referência, varanda/piscina/calçamento/área permeável, pilares, acabamentos, fotos por ambiente e PDF.

## Instalar no tablet

1. Abra o endereço do GitHub Pages deste repositório no Chrome do tablet (precisa de internet só nesta vez).
2. Toque em **⋮ → Instalar app** (ou "Adicionar à tela inicial").
3. Use pelo ícone **Croqui**: abre em tela cheia, sem barra de endereço, e funciona offline.

## Publicar uma versão nova

1. Substitua os arquivos alterados (normalmente só `index.html`).
2. Em `sw.js`, mude `VERSION` (ex.: `croqui-v0.4.0` → `croqui-v0.4.1`).
3. No tablet, abra o app com internet e feche/abra de novo para carregar a versão nova.

## Arquivos

| Arquivo | Para que serve |
|---|---|
| `index.html` | o app inteiro |
| `manifest.webmanifest` | nome, ícone e abertura em tela cheia |
| `sw.js` | guarda o app no aparelho para funcionar offline |
| `icons/` | ícones da tela inicial |
