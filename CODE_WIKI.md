# 📚 Wiki técnica de Fotofecha

## Flujo de guardado y compartición

```mermaid
graph TD
    A[Usuario] --> B[Selecciona imagen]
    B --> C[Elige fecha]
    C --> D[Presiona Guardar]
    D --> E{¿Capacitor?}
    E -->|Sí| F[Filesystem.writeFile en Documents]
    F --> G[Guarda ruta en variable]
    G --> H[Muestra botón Compartir]
    H --> I[Usuario presiona Compartir]
    I --> J[Share.share con la URI]
    J --> K[Android abre menú compartir]
    E -->|No (navegador)| L[Descarga con enlace HTML]
