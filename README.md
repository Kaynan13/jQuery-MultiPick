# jQuery-MultiPick
 jQuery easy multi select component

## Requisitos

[jQuery](https://jquery.com/)

## Utilização

Importe os arquivos css e js em seu html.

```html
  <link rel="stylesheet" href="multiPick.css">
  <script src="multipick.js"></script>
```

Usando o selector jQuery faça a chamada para o componente passando os parametros desejados.

```js
  $('#multiSelect').multiPick({
        limit: 3,
        image: true,
        closeAfterSelect: false,
        search: true,
        placeholder: 'Select',
        slim: false
    });
```