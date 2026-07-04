# Font Tester

Página HTML para visualizar e comparar fontes customizadas.

Carregue arquivos de fonte diretamente do seu computador, ajuste o tamanho de cada uma individualmente e compare a renderização lado a lado com o mesmo texto — sem frameworks, sem servidor, sem dependências externas.

## Funcionalidades

- **Comparação múltipla** — adicione várias fontes e veja todas renderizando o mesmo texto
- **Carregamento local** — selecione arquivos `.woff2`, `.ttf` ou `.otf` direto do disco; funciona sem servidor
- **Texto de comparação** — textarea editável compartilhada entre todos os blocos
- **Presets de texto** — atalhos para alfabeto latino (maiúsculo/minúsculo), hiragana e katakana
- **Tamanho independente** — slider de 8–200 px por bloco de fonte
- **Export SVG** — exporta o texto com as letras convertidas em curvas vetoriais

## Como usar

Abra o `index.html` diretamente no navegador — nenhum servidor é necessário.

Clique em **+ Adicionar fonte** e selecione um ou mais arquivos de fonte. Múltiplos arquivos podem ser selecionados de uma vez.

## Exportar SVG

Cada bloco de fonte tem um botão **SVG ↓** que exporta o texto atual com as letras convertidas em curvas vetoriais. O arquivo resultante não depende da fonte para ser aberto em editores como Inkscape, Illustrator ou Figma.

## Estrutura do projeto

```
font_test/
├── index.html          # Página principal
├── serve.bat           # Servidor local opcional (Python 3)
├── README.md
└── fonts/
    ├── sources.txt     # Referências de origem das fontes
    ├── original/       # Arquivos de fonte nos formatos originais
    └── woff2/          # Fontes em woff2
```

## Fontes incluídas

| Nome | Arquivo | Fonte |
|------|---------|-------|
| Mikiyu Mokomori Kuro | `mikiyu-mokomori-kuro.woff2` | [freejapanesefont.com](https://www.freejapanesefont.com/mokomori-kuro-beta-download/) |
| Mini Wakuwaku | `mini-wakuwaku.woff2` | [freejapanesefont.com](https://www.freejapanesefont.com/mini-wakuwaku/) |
| KF Himaji Fude | `KFhimajiFUDE.woff2` | [freejapanesefont.com](https://www.freejapanesefont.com/kf-himaji-fude-font-download/) |
| Keinann Maru POP JP | `けいなん丸ポップ体JP.woff2` | [freejapanesefont.com](https://www.freejapanesefont.com/keinannmarupop-jp-font-download/) |
| Nikumaru | `nikumaru.woff2` | [freejapanesefont.com](https://www.freejapanesefont.com/nikumaru-free-font/) |
| Doki Doki Fantasia | `DokiDokiFantasia.woff2` | [freejapanesefont.com](https://www.freejapanesefont.com/doki-doki-fantasia-download/) |
| MOBO Bold | `MOBO-Bold.woff2` | [booth.pm](https://flopdesign.booth.pm/items/4647262) |
| Petanko Bold | `Petanko-Bold.woff2` | [booth.pm](https://flopdesign.booth.pm/items/7857280) |
| Futehodo Maru Gothic | `Futehodo-MaruGothic.woff2` | [freejapanesefont.com](https://www.freejapanesefont.com/futehodo-maru-gothic-font-download/) |
| Natsusemi Maru Gothic | `Natsusemi-Maru-Gothic.woff2` | [booth.pm](https://booth.pm/ja/items/4525676) |
| Caramel Hops | `YDWcaramelhop.woff2` | [booth.pm](https://booth.pm/ja/items/7748814) |
| Hakoberamaru Gothic A - ExtraBold | `HakoberaMaruGothicA-ExtraBold.woff2` | [booth.pm](https://booth.pm/ja/items/4898678) |
| daidaidaidaidaaisuki | `daidaidaidaidaaisuki.woff2` | [booth.pm](https://booth.pm/ja/items/8170479) |
| Chikara Yowaku | `851CHIKARA-YOWAKU_002.woff2` | [pm85122.onamae.jp](https://pm85122.onamae.jp/851ch-yw.html) |
| Elmer Font A | `Elmer-Font-A.woff2` | [freejapanesefont.com](https://www.freejapanesefont.com/elmer-font-%e3%81%88%e3%82%8b%e3%81%be%e3%83%bc%e3%83%95%e3%82%a9%e3%83%b3%e3%83%88/) |
| Elmer Font B | `Elmer-Font-B.woff2` | [freejapanesefont.com](https://www.freejapanesefont.com/elmer-font-%e3%81%88%e3%82%8b%e3%81%be%e3%83%bc%e3%83%95%e3%82%a9%e3%83%b3%e3%83%88/) |
