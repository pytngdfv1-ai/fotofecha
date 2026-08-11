# 📅 Fotofecha

**Fotofecha** es una aplicación minimalista para Android que permite guardar imágenes asignándoles como nombre la fecha seleccionada, con el formato: **viernes 15 noviembre 2026.jpg**.

## Características
- Seleccionar una imagen desde la galería o cámara.
- Elegir cualquier fecha con un calendario.
- Vista previa de la imagen sin pérdida de calidad.
- Guarda la imagen en el almacenamiento local con el nombre formateado.
- Tema oscuro, interfaz limpia y sencilla.
- Funciona completamente offline.

## Cómo usar la app

1. **Abrir Fotofecha** en tu dispositivo.
2. Presioná el botón `📷 Seleccionar imagen` para elegir una foto de tu galería.
3. Verás la vista previa en el recuadro superior.
4. Debajo, seleccioná la **fecha** que desees usando el calendario.
5. Presioná `💾 Guardar`.
   - Si estás en el navegador, se descargará la imagen.
   - En la app (Android), se guardará en la carpeta `Documentos` con el nombre `[día de la semana] [día] [mes] [año].extensión`.

## Instalación (para desarrolladores)

```bash
git clone https://github.com/tuusuario/fotofecha.git
cd fotofecha
npm install
npx cap add android
npx cap sync
npx cap open android
