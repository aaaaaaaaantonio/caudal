# Caudal

Finanzas personales y del negocio en bolívares, dólares, euros y USDT, con Lochita.

## Cómo obtener el APK

Cada vez que se sube un cambio a `main`, GitHub compila la app sola (tarda unos 5 a 8 minutos).

1. Abre la pestaña **Releases** de este repositorio desde tu teléfono.
2. Toca la versión más reciente y descarga **Caudal.apk**.
3. Ábrelo y permite instalar apps de este origen cuando Android lo pida.

Para compilar sin subir cambios: pestaña **Actions** → **Compilar APK** → **Run workflow**.

Las actualizaciones se instalan encima de la versión anterior sin borrar tus datos, porque todas usan la misma firma (`debug.keystore`). Mantén este repositorio privado.

## Estructura

- `www/index.html`: la app completa.
- `assets/`: ícono y pantalla de inicio.
- `capacitor.config.json`: configuración de la app Android.
- `.github/workflows/build-apk.yml`: la compilación en la nube.
