# 📱 Hola Mundo — App Android

Primera aplicación Android desarrollada como parte de la **Actividad 2.2** del módulo *Kits de desarrollo de software para dispositivos móviles*. El objetivo fue familiarizarse con el IDE Android Studio, el paradigma declarativo de **Jetpack Compose** y el flujo de trabajo con **Git/GitHub**.

## ✨ Vista previa

<!-- Reemplaza esta línea por tu captura, por ejemplo: -->
<!-- ![Vista de la app](screenshots/app_preview.png) -->

📎 *Pega aquí una captura de la app corriendo (la misma que usaste en el informe).*

## 🚀 Características

- Interfaz construida 100% con Jetpack Compose (sin XML de layout)
- Fondo con degradado y tarjeta con sombra (Material Design 3)
- Botón interactivo con contador de clics usando `remember` / `mutableStateOf`
- Animación de entrada (`fadeIn` + `slideInVertically`)
- Probada en dispositivo físico mediante Device Mirroring

## 🛠️ Tecnologías

- **Kotlin**
- **Jetpack Compose**
- **Android Studio**
- **Material Design 3**

## 📂 Estructura del proyecto

```
app/
 ├─ manifests/AndroidManifest.xml
 ├─ kotlin+java/com.SebastianMelo.holamundo/
 │   ├─ MainActivity.kt
 │   └─ ui.theme/
 │       ├─ Color.kt
 │       ├─ Theme.kt
 │       └─ Type.kt
 └─ res/
     ├─ drawable/
     ├─ mipmap/
     └─ values/
```

## ▶️ Cómo correrlo

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/HolaMundo.git
   ```
2. Ábrelo en **Android Studio** (Open → selecciona la carpeta del proyecto).
3. Espera a que termine la sincronización de Gradle.
4. Conecta un dispositivo físico con Depuración USB activa (o usa un emulador) y dale **Run ▶️**.

## 👤 Autor

**Sebastian Melo**
Actividad 2.2 — Kits de desarrollo de software para dispositivos móviles

---

*Proyecto académico desarrollado con fines educativos.*
