# Font Tester

Página HTML estática para visualizar e testar fontes customizadas em formato **woff2**.

Selecione uma fonte no menu, ajuste o tamanho e digite qualquer texto para ver como ela se comporta — sem frameworks, sem dependências externas.

## Funcionalidades

- **Seletor de fontes** — lista todas as fontes registradas no projeto
- **Texto livre** — textarea editável renderizada na fonte selecionada
- **Controle de tamanho** — slider de 8 px a 200 px com exibição ao vivo
- **Espécime tipográfico** — alfabeto e pangramas em 4 tamanhos fixos para avaliação rápida

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

3. Recarregue a página — a fonte aparecerá automaticamente no menu.

## Estrutura do projeto

```
font_test/
├── index.html          # Página principal
├── README.md
└── fonts/
    ├── sources.txt     # Referências de origem das fontes
    ├── original/       # Arquivos de fonte nos formatos originais
    └── woff2/          # Fontes em woff2 prontas para uso na página
```

## Fontes incluídas

| Nome | Arquivo | Fonte |
|------|---------|-------|
| Mikiyu Mokomori Kuro | `mikiyu-mokomori-kuro.woff2` | [freejapanesefont.com](https://www.freejapanesefont.com/mokomori-kuro-beta-download/) |
