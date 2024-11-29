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
