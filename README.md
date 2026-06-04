# Asistencia · Orientadores

Sistema de registro de asistencia a reuniones de coordinación territorial de orientadores. Permite firmar desde el móvil escaneando un QR y genera un acta PDF automáticamente.

---

## Cómo usarlo

### La coordinadora (desde el ordenador)

1. Abre [https://coordinacion-territorial.github.io/asistencia/](https://coordinacion-territorial.github.io/asistencia/)
2. Introduce la contraseña
3. Rellena los datos de la reunión (tipo, lugar, fecha, hora)
4. Pulsa **Generar QR** y proyecta la pantalla
5. Cuando termine la reunión, pulsa **Generar acta PDF**
6. Para la siguiente reunión, pulsa **Nueva reunión**

### Los orientadores (desde el móvil)

1. Escanear el QR proyectado con la cámara del móvil
2. Rellenar nombre, apellidos, centro y agrupación
3. Firmar con el dedo
4. Pulsar **Firmar asistencia** → confirmación inmediata

---

## Archivos

| Archivo | Descripción |
|---|---|
| `index.html` | Aplicación completa (coordinadora + móvil) |
| `README.md` | Este documento |

---

## Notas técnicas

- Los datos se almacenan en [JSONBin.io](https://jsonbin.io) (bin privado, acceso solo con API key)
- No se requiere instalación ni servidor propio
- Funciona desde cualquier navegador y cualquier red
- Las firmas se guardan como imagen PNG en base64
