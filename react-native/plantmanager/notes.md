# Aula 01 - Liftoff

`https://www.youtube.com/watch?v=vrABToPdOyg`

Material Complementar: `https://www.notion.so/Trilha-React-Native-525e7888c5d941f5ab8162a200cd2f35`

```bash
# Iniciar projeto
expo init plantmanager
> blank (TypeScript)

cd plantmanager
expo start
```

# Aula 02 - Maximum Speed

`https://www.youtube.com/watch?v=R19Dz_d0Wp4`

```bash
# Adicionar icones - https://docs.expo.io/guides/icons/
expo install @expo/vector-icons

# Adicionar fontes - https://docs.expo.io/guides/using-custom-fonts/
expo install expo-font @expo-google-fonts/jost
# Mostrar a tela de Splash até a fonte ser carregada
expo install expo-app-loading
```

```bash
# Navegação - https://reactnavigation.org
yarn add @react-navigation/native

expo install react-native-gesture-handler react-native-reanimated react-native-screens react-native-safe-area-context @react-native-community/masked-view

yarn add @react-navigation/stack
```

# Aula 03 - In Orbit

`https://www.youtube.com/watch?v=HZfuL7pN9Wo`

```bash
# Lidar com o espaçamento no header do iphone
yarn add react-native-iphone-x-helper

# Biblioteca para comunicação com API
yarn add axios

# Biblioteca para APIs fake - https://github.com/typicode/json-server
npm install -g json-server

# Executar API Fake
json-server ./src/services/server.json --host 192.168.0.107 --port 3333

# Executar API Fake com delay de 700ms
json-server ./src/services/server.json --host 192.168.0.107 --port 3333 --delay 700

```

```bash
# Utilizar imagens SVG - https://docs.expo.io/versions/latest/sdk/svg/
expo install react-native-svg
```

```bash
# Animações com Lottie
# https://docs.expo.io/versions/latest/sdk/lottie/
expo install lottie-react-native
```

# Aula 04 - Landing

`https://www.youtube.com/watch?v=PIgXHztZ-Fo`

```bash
# Salvar algum valor no dispositivo do usuario - https://docs.expo.io/versions/latest/sdk/async-storage/
expo install @react-native-async-storage/async-storage
```

```bash
# DateTimePicker - https://docs.expo.io/versions/latest/sdk/date-time-picker/
expo install @react-native-community/datetimepicker

# Biblioteca para trabalhar com data - https://date-fns.org/
yarn add date-fns
```

```bash
# Navegação por Tabs - https://reactnavigation.org/docs/tab-based-navigation
yarn add @react-navigation/bottom-tabs
```

# Aula 05 - Surface Exploration

`https://www.youtube.com/watch?v=FxsXRIhD_Wk`

```bash
# Notificações - https://docs.expo.io/versions/latest/sdk/notifications/
expo install expo-notifications
```
