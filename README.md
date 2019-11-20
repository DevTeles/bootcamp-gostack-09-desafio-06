<h1 align="center">
    <img alt="GoStack" src="https://rocketseat-cdn.s3-sa-east-1.amazonaws.com/bootcamp-header.png" width="200px" />
</h1>

<h3 align="center">
  Desafio 6: Primeiro projeto com React Native
</h3>

<blockquote align="center">“Só deseje as coisas as quais você está disposto a lutar”!</blockquote>

## :rocket: Sobre o desafio

Nesse desafio você adicionará novas funcionalidades na aplicação que desenvolvemos ao longo desse módulo.

### Funcionalidades

#### 1. Loading de repositórios

#### 2. Scroll infinito

#### 3. Pull to Refresh

#### 4. WebView

Crie uma nova página na aplicação que vai ser acessada quando o usuário clicar em um repositório favoritado, essa página deve conter apenas o Header da aplicação. O conteúdo da página será uma WebView, ou seja, um browser integrado que exibe o atributo `html_url` presente no objeto do repositório que vem da API do Github.

Documentação de utilização da [WebView](https://github.com/react-native-community/react-native-webview/blob/master/docs/Getting-Started.md).

Exemplo de código:

```js
<WebView source={{ uri: repository.html_url }} style={{ flex: 1 }} />
```

Resultado:

![WebView](.github/exemplo-web-view.png)
