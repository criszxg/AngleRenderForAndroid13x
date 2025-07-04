# AnglePortOneUI

Módulo Magisk para portar ANGLE desde una GSI a One UI con Android 13. Incluye librerías, permisos y la app de preferencias para activación por app.

##  Estructura
- `system/lib*/libEGL_angle.so`
- `priv-app/ANGLE/ANGLE.apk`
- `permissions/android.software.angle.xml`

## Requisitos
- Magisk instalado
- Soporte Vulkan 1.1
- One UI 5.1 (opcional) con Android 13 (semiobligatorio)

##  Activación
1. Instala el módulo.
2. Reiniciá.
3. Activá ANGLE por app desde la app de preferencias en opciones de desarrollador.

**⚠️ No activar como render global si no sabés, puede causar bootloop.**
