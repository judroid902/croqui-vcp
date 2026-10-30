# Croqui de Vistoria

App para desenhar o croqui da vistoria no tablet, sobre grade de 0,5 m, e exportar em PNG, PDF (com fotos), DXF (CAD) e JSON.
Funciona sem internet depois de instalado. Os croquis, as fotos e os usuários ficam salvos só no aparelho; este repositório contém apenas o programa.

Versão atual: 0.7 — quantitativos (pisos, revestimento de paredes por faixa, tetos, rodapé, vedação por tipo, esquadrias, pilares, piscina e instalações) na tela, no PDF e em planilha CSV para orçamento; Compartilhar explica e oferece alternativa quando o Android recusa o arquivo (DXF e JSON). Na 0.6: importação de desenho pronto: DXF (linhas editáveis, paredes e notas), PDF e imagem (fundo em escala, com calibração) e o JSON exportado pelo próprio app. Desde a 0.5: entrada por PIN com lista de croquis de cada desenhista, esquadrias, ambiente contornado pelas paredes, acabamento de parede por faixas de altura, instalações de esgoto e drenagem, norte real com giro do desenho na exportação.

Para importar PDF, o tablet precisa de internet no momento da importação (o leitor de PDF é carregado da internet). DXF, imagens e JSON importam sem internet.

## Instalar no tablet

1. Abra o endereço do GitHub Pages deste repositório no Chrome do tablet (precisa de internet só nesta vez).
2. Toque em **⋮ → Instalar app** (ou "Adicionar à tela inicial").
3. Use pelo ícone **Croqui**: abre em tela cheia, sem barra de endereço, e funciona offline.
4. No primeiro acesso, cadastre o administrador (nome e PIN de 4 números). Ele cadastra os demais desenhistas.

## Publicar uma versão nova

1. Substitua os arquivos alterados (normalmente só `index.html`).
2. Em `sw.js`, mude `VERSION` (ex.: `croqui-v0.7.0` → `croqui-v0.7.1`).
3. No tablet, abra o app com internet e feche/abra de novo para carregar a versão nova.

## Arquivos

| Arquivo | Para que serve |
|---|---|
| `index.html` | o app inteiro |
| `manifest.webmanifest` | nome, ícone e abertura em tela cheia |
| `sw.js` | guarda o app no aparelho para funcionar offline |
| `icons/` | ícones da tela inicial |
