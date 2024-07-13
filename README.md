# React Native con Expo

### Crear APP Vacia
npx create-expo-app@latest webview --template blank

### Instalar Web
npx expo install react-native-web react-dom @expo/metro-runtime

### Ejecutar una APP Web
npm run web

### Instalar Cliente Expo
npm install -g eas-cli

### Autenticar en Expo
eas login

### Verificar autenticación en Expo
eas whoami

### Aplicar Configuración Expo All Ios Android
eas build:configure

### Compilar APP para obtener el Apk
eas build -p android --profile preview
