# Rich Platform

Rich Platform es el estudio de creación de contenido de **The Kid Company**: guiones,
voces, imágenes, video y subtítulos en una sola app que corre en tu computadora.

Para usarla necesitás una **membresía activa**. Tu correo y tu contraseña temporal te
los da el equipo por Skool. Acá sólo están las descargas: el código de la app no es
público.

## Descargar

Estos enlaces bajan siempre la última versión:

| Sistema | Descarga |
|---|---|
| **Windows 10 / 11** | [Rich-Platform-windows.zip](https://github.com/cano4est/rich-platform-releases/releases/latest/download/Rich-Platform-windows.zip) |
| **Mac con chip Apple** (M1 o posterior) · experimental | [Rich-Platform-mac.zip](https://github.com/cano4est/rich-platform-releases/releases/latest/download/Rich-Platform-mac.zip) |
| **Linux** (64 bits) | [Rich-Platform-linux.tar.gz](https://github.com/cano4est/rich-platform-releases/releases/latest/download/Rich-Platform-linux.tar.gz) |

Las notas de cada versión y las versiones anteriores están en
[Releases](https://github.com/cano4est/rich-platform-releases/releases).

## Instalar en Windows

1. Descomprimí el `.zip` en una carpeta tuya, por ejemplo `Documentos\Rich-Platform`.
   No la abras desde adentro del `.zip`.
2. Abrí `Rich-Platform.exe`. Se abre el navegador con la app.
3. La primera vez Windows muestra un aviso azul de SmartScreen, porque la app todavía no
   tiene firma digital. Tocá **Más información** y después **Ejecutar de todas formas**.
4. Entrá con tu correo y tu contraseña temporal. La primera vez la app te pide elegir
   una contraseña propia.

Para cerrar la app usá el botón **Salir** de la barra lateral. Cerrar la pestaña del
navegador no la cierra.

## Instalar en Mac (experimental)

Sólo para Mac con chip Apple (M1 o posterior). La exportación a CapCut y el render por
GPU todavía no andan en Mac.

1. Descomprimí el `.zip` y mové `Rich-Platform.app` a **Aplicaciones** antes de abrirla.
2. Abrila. La primera vez macOS la bloquea porque no está firmada por Apple: andá a
   **Ajustes del Sistema → Privacidad y seguridad**, bajá hasta el aviso de Rich Platform
   y tocá **Abrir igualmente**.
3. La app no aparece en el Dock: se cierra con el botón **Salir** de la barra lateral.

## Instalar en Linux

```bash
tar -xzf Rich-Platform-linux.tar.gz
./Rich-Platform/Rich-Platform
```

## Actualizar

1. Cerrá la versión que tenés abierta con el botón **Salir**.
2. Bajá la nueva desde los enlaces de arriba y descomprimila.
3. Borrá la carpeta vieja.

Tus proyectos, ajustes y tu sesión se guardan aparte, no en la carpeta de la app: no se
pierden al actualizar.

## Tu cuenta

- Podés usar la app en **dos equipos**. Para usarla en uno nuevo, la app te deja liberar
  uno de los anteriores (hasta tres veces por mes).
- La app necesita internet para entrar y revisa tu membresía cada tanto. Sin conexión
  sigue funcionando hasta 7 días.
- ¿Olvidaste tu contraseña? Escribinos a thekidcompanysas@gmail.com desde el correo de
  tu cuenta y te mandamos una contraseña temporal nueva.

## Si algo falla

Escribinos por Skool o a thekidcompanysas@gmail.com contando qué pasó, y adjuntá el
archivo de registro de la app:

- **Windows**: `%LOCALAPPDATA%\Rich-Platform\data\logs\rich-platform.log`
- **Mac**: `~/Library/Application Support/Rich-Platform/logs/rich-platform.log`
- **Linux**: `~/.local/share/Rich-Platform/logs/rich-platform.log`

El registro no guarda tus contraseñas ni tus claves.

## Verificar una descarga

Cada versión trae un archivo `SHA256SUMS.txt` con la huella de cada paquete. En Windows
(PowerShell):

```powershell
Get-FileHash .\Rich-Platform-windows.zip -Algorithm SHA256
```

El resultado tiene que coincidir con la línea de ese archivo en `SHA256SUMS.txt`.

---

© The Kid Company. Rich Platform es software privado: estas descargas son sólo para
miembros con una membresía activa.
