# FitNES-page

Site para o projeto de Prática e Pesquisa do Novo Ensino Suplementar

## Como rodar?

```sh
npm i
npx npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
npx serve src
```

## Como contribuir?

Faça as alterações e depois rode os seguintes comandos:
```sh
git add .. -p
git commit -m "Mensagem"
git push
git subtree push --prefix src origin gh-pages
```

## Requisitos
- Conter no mínimo 3 páginas diferentes: ✅ (`index.html`, `academias.html`, `cliente.html`, `planos.html`)
- Respeitar a construção semântica do layout: ✅ (uso das tags `footer`, `nav` e `section`)
- Ser responsivo (lembre do uso de flex, grid e dos breakpoints do Tailwind): ✅ (uso de `flex` e breakpoints em todas as páginas, e `grid` na página `academias.html`)
- Ter uma diversidade nas tipografias (trabalhe com font-size, font-weight e text-color): ✅ (uso de font-size, font-weight e text-color em todas as páginas)
- Utilizar a variedade de cores disponível na paleta de cores padrão do Tailwind (ou criar a sua própria): ✅ (uso da paleta de cores do TailwindCSS)
- Adicionar pelo menos 2 variações quanto a pseudo classes (estados dos elementos): ✅ (uso das pseudo classes `focus` e `hover`)
- Adicionar pelo menos 1 tabela personalizada: ✅ (uso do `grid` na página `academias.html`)
