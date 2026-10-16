# VTCompi — descargas

Aquí sólo están los **paquetes** de VTCompi, tu asistente VTC, para que el
programa pueda buscar e instalar sus versiones nuevas, y el catálogo de sus
extensiones. El código no está en este repositorio.

Cada versión está en [Releases](../../releases):

| Paquete | Para |
|---|---|
| `VTCompi-Setup.exe` | **Windows 10/11: el instalador** (programa y mantenimiento, con sus accesos en el menú Inicio) |
| `VTCompi-Windows.zip` | Windows, sin instalar: el programa |
| `VTCompi-mantenimiento-Windows.zip` | Windows, sin instalar: copias, restauración y credenciales |
| `VTCompi-X.Y.Z-macOS-intel.zip` | Mac con Intel |
| `VTCompi-mantenimiento-X.Y.Z-macOS-intel.zip` | Mac con Intel: el mantenimiento |
| `VTCompi-macOS-AppleSilicon.zip` | Mac con chip Apple (M1, M2…), cuando esté |
| `sha256.txt` | La huella de cada paquete, para comprobarlo |

**Mac con chip Apple:** mientras no haya paquete propio, la versión de Intel
funciona en ellos (macOS la abre con Rosetta) y se actualiza sola con la de
Intel.

Las versiones marcadas como *pre-release* son pruebas: se pueden descargar,
pero el programa no se actualiza a ellas.

En `extensiones/` y `conectores/` está lo que lee el programa para su gestor
de extensiones y para los arreglos de los conectores de las plataformas.

Hace falta una licencia para usarlo.
