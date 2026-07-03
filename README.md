# Font Tester

Página HTML para visualizar e comparar fontes customizadas em formato **woff2**.

Adicione quantas fontes quiser, ajuste o tamanho de cada uma individualmente e compare a renderização lado a lado com o mesmo texto — sem frameworks, sem dependências externas.

## Funcionalidades

- **Comparação múltipla** — adicione várias fontes e veja todas renderizando o mesmo texto
- **Texto de comparação** — textarea editável compartilhada entre todos os blocos
- **Presets de texto** — atalhos para alfabeto latino (maiúsculo/minúsculo), hiragana e katakana
- **Tamanho independente** — slider de 8–200 px por bloco de fonte

## Como usar

Abra o arquivo `index.html` diretamente no navegador. Nenhum servidor ou build é necessário.

## Adicionando fontes

1. Coloque o arquivo `.woff2` na pasta `fonts/woff2/`
2. Registre a fonte no array `FONTS` dentro do `<script>` em `index.html`:

```js
const FONTS = [
  { name: "Mikiyu Mokomori Kuro", file: "mikiyu-mokomori-kuro.woff2" },
  { name: "Nome da Fonte",        file: "nome-do-arquivo.woff2" },
];
```

3. Recarregue a página — a fonte aparecerá no seletor.

## Estrutura do projeto

```
font_test/
├── index.html          # Página principal
├── serve.bat           # Atalho para iniciar o servidor local (Python 3)
├── README.md
└── fonts/
    ├── sources.txt     # Referências de origem das fontes
    ├── original/       # Arquivos de fonte nos formatos originais
    └── woff2/          # Fontes em woff2 prontas para uso na página
```

## Fontes incluídas

| Nome | Arquivo | Fonte |
|------|---------|-------|
| Mokomori Kuro | `mikiyu-mokomori-kuro.woff2` | [freejapanesefont.com](https://www.freejapanesefont.com/mokomori-kuro-beta-download/) |
| Mini wakuwaku | `mini-wakuwaku.woff2` | [freejapanesefont.com](https://www.freejapanesefont.com/mini-wakuwaku/) |
| Mini wakuwaku maru | `mini-wakuwaku-maru.woff2` | [freejapanesefont.com](https://www.freejapanesefont.com/mini-wakuwaku/) |
