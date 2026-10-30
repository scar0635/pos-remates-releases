# Caja Remate · instaladores

Aquí se publican los instaladores de Windows de la caja del POS Remates. El código fuente vive en un
repositorio privado; este solo contiene las releases para que la actualización automática de las
cajas pueda descargarlas.

## Instalar

1. Descarga `Caja-Remate-Setup-X.Y.Z.exe` de la última release.
2. Ejecútalo. Windows mostrará "Windows protegió su PC" porque el instalador no está firmado:
   toca **Más información → Ejecutar de todas formas**.
3. Se instala para el usuario actual (sin permisos de administrador), crea el acceso directo y abre la caja.

## Actualizar

No hay que hacer nada: la caja busca actualizaciones al arrancar y cada 6 horas, las descarga en
segundo plano y las instala al cerrar la aplicación.

Los archivos `latest.yml` y `.blockmap` de cada release son los que usa la actualización automática;
no los borres.
