# Ejemplos de Login Multiplataforma

Comparación simple de implementación de una pantalla de login en tres frameworks de desarrollo móvil.

## 📱 Tecnologías

Este repositorio contiene tres ejemplos de una pantalla de login básica:

1. **Flutter (Dart)** - Framework multiplataforma de Google
2. **React Native (TypeScript)** - Framework multiplataforma de Meta/Facebook
3. **Android Jetpack Compose (Kotlin)** - Framework nativo de Android

## 📂 Estructura del Proyecto

```
.
├── login_example_flutter/          # Proyecto Flutter
│   └── lib/main.dart               # Código principal
├── login_example_reactnative/      # Proyecto React Native
│   └── App.tsx                     # Código principal
└── login_example_compose/          # Proyecto Jetpack Compose
    └── app/src/main/java/.../MainActivity.kt  # Código principal
```

## 🚀 Cómo ejecutar

### Flutter
```bash
cd login_example_flutter
flutter run
```

### React Native
```bash
cd login_example_reactnative
npm install
npm start                      # Terminal 1: Metro bundler
npm run android                # Terminal 2: Ejecutar app
```

### Jetpack Compose
```bash
cd login_example_compose
# Abrir en Android Studio y ejecutar
```

## ✨ Características

Cada ejemplo incluye:
- 2 campos de entrada (Email y Contraseña)
- Botón de inicio de sesión
- Validación básica de campos
- Mensaje de confirmación

## 🎯 Propósito

Estos ejemplos son para fines educativos y demostrativos, mostrando las diferencias sintácticas y estructurales entre los tres enfoques de desarrollo móvil.
