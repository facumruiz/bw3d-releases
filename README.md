# BW ERP 3D — descargas

Acá se publican los instaladores de **BW ERP 3D**, el gestor de productos de impresión 3D y catálogo online de Black & White 3D. Este repositorio solo tiene las versiones; el código está en otro repositorio.

## Descargar

Entrá a **[Releases](../../releases/latest)** y bajá el archivo que corresponda:

| Sistema | Archivo | Se actualiza sola |
|---|---|---|
| Windows | `BW.ERP.3D-<versión>-win.exe` (instalador) | Sí |
| Windows | `BW.ERP.3D-<versión>-win.zip` (portable: descomprimir y abrir) | No |
| Linux | `BW.ERP.3D-<versión>-linux.AppImage` (`chmod +x` y doble clic) | Sí |
| Linux | `BW.ERP.3D-<versión>-linux.tar.gz` | No |

Las versiones no están firmadas: Windows puede mostrar el aviso de SmartScreen la primera vez («Más información» → «Ejecutar de todos modos»).

## Actualizar

Con el instalador de Windows o el AppImage no hace falta volver a instalar: en **Ajustes → Actualizaciones** de la app están los botones para buscar, descargar y actualizar (también avisa sola al abrirse). Se reinicia y conserva todos los datos. Para eso la app consulta este repositorio, por lo que necesita internet.

Los archivos `latest.yml` y `latest-linux.yml` de cada release son los que usa la app para encontrar la versión nueva: no hace falta bajarlos.
