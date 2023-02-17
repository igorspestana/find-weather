# Iniciar

Criar app
```
npx create-expo-app <nome do app> && cd <nome do app>
```
Criar app escolhendo o template
```
npx create-expo-app --template
```

Para rodar no browser
```
npx expo install react-dom react-native-web @expo/webpack-config
```

Para rodar
```
npx expo start
```
Instalar o emulador android
```
npx expo run:android             
```

---
# Organizar Pastas

- A pasta “src” significa source, ou seja, seria a fonte dos
arquivos da nossa aplicação;
- A pasta @types é usada para armazenar definições de tipos para bibliotecas JavaScript. Estas definições de tipos fornecem informações sobre o que os métodos e propriedades de uma biblioteca específica fazem e como elas se comportam. Isso ajuda a melhorar a experiência do desenvolvedor, pois permite que o editor de código possa oferecer sugestões e correção automática enquanto você escreve código. No React Native, as definições de tipos são usadas para garantir que você esteja usando as APIs da maneira correta;
- A pasta “assets” como diz o nome, seria para ter os ícones, svgs e ilustrações do app.
- A pasta “componentes” guardará os componentes;
- A pasta “routes” guardará os arquivos relacionados as rotas da aplicação;
- A pasta “screens” guardará as telas;
- A pasta “services” conterá as configurações relacionadas a API;
- A pasta “storage” eu geralmente utilizo para guardar as keys do Async Storage;
- A pasta “theme” é responsável por guardar os arquivos com os tokens de cores, fontes, tamanhos, ou seja, tudo relacionado aos estilos;
- Por fim, na pasta “utils” podem ser armazenados todos os arquivos que auxiliam o app de alguma forma, como por exemplo uma função que formata datas.

---
# Escolher fontes

```
npm i @expo-google-fonts/overpass
```
---
# API

- OpenCage API key: 2cc1a40894d448aa9d21d67076de8422
- OpenWeather API key: 3bbb5d739a5c359b03f18309510490a7
- Weather API key: b3b5978bcf5f434ba6502017231702

---