# Instalación y primer arranque

## Requisitos

- Windows 10 u 11 de 64 bits.
- No necesitas permisos de administrador: Affluence se instala para tu usuario.
- Internet para descargar del SAT y consultar vigencias.
- La e.firma (archivos `.cer` y `.key` y su contraseña) de cada cliente que quieras descargar.

## 1. Descargar

Entra a [la versión más reciente](https://github.com/jesusguerrero-accountant/affluence-releases/releases/latest)
y descarga `Affluence-Setup-X.Y.Z.exe`.

## 2. El aviso azul de Windows

Durante la beta el instalador todavía no lleva firma digital de Microsoft, así que la primera vez
Windows puede mostrar **"Windows protegió su PC"**. Es normal:

1. Haz clic en **Más información**.
2. Haz clic en **Ejecutar de todas formas**.

Si tu antivirus pregunta, permite la instalación.

## 3. Instalar

Sigue las pantallas del instalador: acepta los términos de la beta y el aviso de privacidad, y
termina. Queda un acceso en el menú Inicio.

## 4. Primer arranque: crear al administrador

La primera vez que abres Affluence te pide tres cosas:

1. **Esta computadora.** Affluence comprueba solo que es el equipo donde se instaló.
2. **Administrador.** Tu nombre, un usuario y una contraseña de al menos 10 caracteres.
3. **Tu frase de recuperación.** Se muestra **una sola vez**.

> **Anota la frase en papel y guárdala fuera de la computadora.** Es la única forma de recuperar
> las e.firmas de tus clientes si cambias de equipo. Affluence no la guarda y no la puede mostrar
> otra vez.

Marca "Ya guardé mi frase en un lugar seguro" y entra.

## Cada vez que abres Affluence

- Te pide usuario y contraseña (la sesión no se recuerda, a propósito).
- Si la barra de abajo dice "Iniciando el Servicio de Affluence", espera unos segundos: es la parte
  que trabaja detrás de la ventana.
- Puedes cerrar la ventana: las descargas en curso siguen.

## Actualizaciones

Cuando hay una versión nueva, Affluence te avisa. Al aceptar, hace un respaldo, instala y se vuelve
a abrir sola. No pierdes nada.

## Desinstalar

Configuración de Windows → Aplicaciones instaladas → Affluence → Desinstalar. Tus datos **no se
borran** a menos que lo pidas en el desinstalador: si reinstalas, todo sigue ahí.
