# React Native con Expo

### Crear APP Vacia
npx create-expo-app@latest webview --template blank

### Instalar webview
npm i react-native-webview

### Instalar Web
npx expo install react-native-web react-dom @expo/metro-runtime

### Ejecutar una APP Web
npm run web

### Instalar Cliente Expo
npm install -g eas-cli

### Registrar en Expo
https://expo.dev

### Autenticar en Expo
eas login

### Verificar autenticación en Expo
eas whoami

# Compilar APP Reac Native

## Aplicar Configuración Expo
eas build:configure

## Compilar APP para obtener el Instalador
eas build -p android --profile preview




