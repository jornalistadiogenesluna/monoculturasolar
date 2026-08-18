# Monocultura Solar — gráfico interativo

Pacote estático pronto para GitHub Pages.

## Arquivos

- `index.html` — página completa do gráfico interativo
- `.nojekyll` — evita processamento desnecessário pelo Jekyll

## Publicação no GitHub Pages

1. Crie um repositório no GitHub.
2. Envie `index.html` e `.nojekyll` para a raiz do repositório.
3. Abra **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Selecione a branch `main` e a pasta `/ (root)`.
6. Salve.

A URL ficará no formato:

`https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`

## Incorporação em outro site

Depois de publicado, use:

```html
<iframe
  src="https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/"
  title="Quando a usina ocupa mais chão do que a cidade inteira"
  width="100%"
  height="800"
  scrolling="yes"
  style="width:100%;height:800px;border:0;display:block;background:#fff;"
></iframe>
```
