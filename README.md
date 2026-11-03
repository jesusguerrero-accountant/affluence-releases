# Affluence · descargas

Affluence es una aplicación de escritorio para despachos contables: descarga los CFDI de tus
clientes desde el SAT con su e.firma, revisa su vigencia, aplica reglas fiscales y genera PDF,
reportes en Excel y expedientes. Todo se guarda en tu computadora; nada se sube a internet.

**Descarga la versión más reciente:**
[Releases → Latest](https://github.com/jesusguerrero-accountant/affluence-releases/releases/latest)
(el archivo `Affluence-Setup-X.Y.Z.exe`).

## Guías

| Guía | Para qué |
|---|---|
| [Instalación y primer arranque](INSTALACION.md) | Instalar, el aviso de Windows y crear al administrador |
| [Guía rápida](GUIA-RAPIDA.md) | De cero a tus primeros CFDI descargados en 6 pasos |
| [Dónde están mis archivos](DONDE-ESTAN-MIS-ARCHIVOS.md) | Carpetas de XML, PDF, Excel y expedientes, y cómo abrirlas |
| [Cómo enviar comentarios y reportar fallas](COMO-REPORTAR.md) | Qué anotar para que una falla se resuelva rápido |

## Atajo a tus XML

Pega esto en la barra de direcciones del Explorador de archivos de Windows y presiona Enter:

```
%LOCALAPPDATA%\Affluence\xml\cfdi
```

## Qué trae cada versión

- `Affluence-Setup-X.Y.Z.exe`: el instalador.
- `Affluence-Setup-X.Y.Z.exe.sha256`: la huella para comprobar la descarga.
- `actualizacion.json` y `actualizacion.json.sig`: los usa la aplicación para actualizarse sola de
  forma segura. No necesitas descargarlos.

Después de instalar no hace falta volver a esta página: cuando hay una versión nueva, Affluence te
avisa y se actualiza sola, con un respaldo previo.

## Soporte

affluence.contacto@gmail.com
