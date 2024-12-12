<p align="center">
  <img src="https://docs.google.com/uc?id=1ajY5_l_Pfcxk0NBkb786tgUqUCZtszcV" width="100%" />
</p>

# Nearby - Mobile App

Esta aplicação com o nome de Nearby consiste basicamente na exibição de lojas parceiras, para benefícios como ativação de cupons. 🚀

## Executando o projeto

Abaixo seguem as instruções para você executar o projeto em sua máquina.

Comece clonando o repositório:

```sh
git clone https://github.com/matheushdmoreira/nearby
```

### Back-end

O back-end desse projeto é construído em Node.js, mais especificamente sua versão LTS.

> Você pode instalar o Node.js seguindo [esse guia](https://efficient-sloth-d85.notion.site/Instalando-o-Node-js-d40fdabe8f0a491eb33b85da93d90a2f).

Após instalar o Node.js, vamos acessar a pasta api do projeto, instalar as dependências e, então, subir o servidor HTTP.

```sh
cd api

# Instalando as dependências
npm install

# Subir o servidor HTTP
npm start
```

### Mobile

Para executar o app pass.in utilizamos o Expo, uma ferramenta incrível da comunidade React Native. Além do Expo, é necessário que você utilize algum emulador local ou um dispositivo físico pra visualizar a aplicação.

> Você pode instalar o Expo e os emuladores seguindo [esse guia](https://react-native.rocketseat.dev/).

Instalando suas dependências:

```sh
cd mobile

# Instalando as dependências
npm install
```

Após configurar o ambiente mobile, você pode abrir o emulador e executar o projeto de acordo com a plataforma que estiver utilizando:

```sh
npx expo start
```

## Links rápidos ↗

- [Layout | Figma 🎨](https://www.figma.com/design/RSAbVmE4SZULXy7zRaX1Me/NLW-Pocket-Mobile-%E2%80%A2-Nearby-(Community)?node-id=0-1&node-type=canvas&t=JDZqmLWlNg7yMsmk-0)

**📱 Mobile:**

- [Expo](https://github.com/expo/expo)
- [TypeScript](https://github.com/microsoft/TypeScript)
- [Expo Google Fonts](https://github.com/expo/google-fonts)
- [React Native Bottom Sheet](https://gorhom.dev/react-native-bottom-sheet/)
- [MapView](https://docs.expo.dev/versions/latest/sdk/map-view/)
- [Expo Location](https://docs.expo.dev/versions/latest/sdk/location/)
- [Expo Camera](https://docs.expo.dev/versions/latest/sdk/camera/)

## License

MIT License © [Matheus Moreira](https://github.com/matheushdmoreira)

