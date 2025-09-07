# 🎮 AnglePortOneUI - ANGLE Renderer para Android 13 (One UI)

Módulo **Magisk** que porta y activa **ANGLE** (Almost Native Graphics Layer Engine) extraído de una **GSI con Android 14**, adaptado para **One UI 5.1 en Android 13** con soporte de **activación por app**, sin necesidad de usarlo como render global.

> ⚠️ Ideal para dispositivos con **GPU Mali-G52 MC2** y soporte de **Vulkan 1.1**.

---

## 🚀 Características

- Porta las librerías ANGLE necesarias (`libEGL_angle.so`, etc).
- Añade la app oficial de **preferencias ANGLE** (com.android.angle).
- Incluye permisos y configuración para activarlo por aplicación.
- Compatible con **Samsung One UI 5.1** (probado en Galaxy A22 4G).
- solo Magisk.

---

## 🛠️ Requisitos

- Android 12+.
- Magisk instalado (cualquier versión reciente).
- Soporte de Vulkan 1.1 (ej: Mali-G52 con drivers 26.0.0 o superior).
- App **ANGLE Preferences** instalada desde el módulo.

---

## 📦 Instalación

1. Descargá el ZIP del módulo desde la [sección Releases]
2. Abrí la app Magisk > Módulos > Instalar desde almacenamiento.
3. Seleccioná el ZIP `AnglePortOneUI.zip`.
4. Reiniciá el dispositivo.
5. Entrá a la app **"Preferencias de ANGLE"** y activalo por app manualmente en opciones de desarrolladores (recomendado).

---

## ⚠️ Advertencias

- **No activarlo como render global**, puede causar bootloop o errores visuales.
- No compatible con todas las GPUs ni versiones de Android.
- Algunas apps no usan ANGLE aunque esté forzado (depende de implementación).

---

## 👨‍💻 Autor

Port hecho por **@criszxg**  
Guía y soporte por **ChatGPT (OpenAI)** 😎

---

## 🧪 Probado en:

- 📱 Samsung Galaxy A22 4G (Mali-G52 MC2)
- ⚙️ One UI 5.1 - Android 13
- ✅ PojavLauncher (Zink backend) con mejor rendimiento y "soporte" (solo angle render)

---

## 📘 Licencia

Este proyecto se comparte de forma libre para fines educativos y de prueba. Usalo bajo tu propio riesgo.
