# app_cardibascular
# 🫀 Sistema de Gestión Cardiovascular

Aplicación móvil desarrollada con Flutter y Dart, utilizando GetX para la gestión del estado y la organización de la lógica de la aplicación.

## 📌 Descripción del proyecto
`
El fin de la aplicación es el poder predecir y alertar al usuario si podra desarrollar alguna enfermedad cardiovascular o esta entrando en un cuadro. 

`
## 🚀 Tecnologías utilizadas

- **Flutter:** Framework para el desarrollo multiplataforma.
- **Dart:** Lenguaje de programación.
- **GetX:** Gestión de estado, dependencias y navegación.
- **Git:** Control de versiones.
- **GitHub:** Alojamiento del repositorio.

## 📂 Estructura del proyecto

lib/
├── main.dart
├── models/
│   └── registro_model.dart
├── data/
│   ├── services/
│   │   ├── auth_service.dart
│   │   └── drive_service.dart
│   └── repositories/
│       └── registro_repository.dart
├── application/
│   ├── bindings/
│   │   └── initial_binding.dart
│   ├── controllers/
│   │   ├── login_controller.dart
│   │   ├── home_controller.dart
│   │   └── graficas_controller.dart
│   └── routes/
│       ├── app_routes.dart
│       └── app_pages.dart
└── presentation/
    ├── login_page.dart
    ├── home.dart
    ├── graficas_page.dart
    └── widgets/
        ├── grafica_rueda.dart
        ├── grafica_lineal.dart
        └── tarjeta_dato.dart

## ⚙️ Requisitos previos

Antes de ejecutar el proyecto, debes tener instalado:

- Flutter SDK.
- Dart SDK (incluido con Flutter).
- Android Studio o Visual Studio Code.
- Git.

## 📥 Instalación

1. Clonar el repositorio:

```bash
git clone https://github.com/Twokarma/Dsipos_moviles_cardio_vascular.git
```


2. Ingresar al directorio de la aplicación:

```bash
cd Dsipos_moviles_cardio_vascular/app_cardibascular
```


3. Instalar las dependencias:

```bash
flutter pub get
```

## ▶️ Ejecución

Ejecutar la aplicación con:

```bash
flutter run
```

Para generar un APK:

```bash
flutter build apk --release
```
