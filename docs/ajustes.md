# Ajustes

Ábrelos de cualquiera de estas formas:

- el **engranaje** de la esquina inferior derecha,
- `Ctrl + ,` con KeyFlow abierto,
- buscando **ajustes**,
- clic derecho en el icono de KeyFlow de la bandeja del sistema → **Ajustes**.

Los cambios se aplican y se guardan al momento; no hay botón de guardar. Cada sección tiene un botón **Restablecer**, que aparece solo cuando algo de esa sección es distinto del valor original y la devuelve a como venía. Al final del panel, **Restablecer ajustes** lo devuelve todo a la vez (hay que pulsarlo dos veces para confirmar).

---

## Apariencia

| Ajuste | Opciones | Por defecto |
|---|---|---|
| **Estilo** | *Clásico*: esquinas cuadradas, al estilo de otros lanzadores de escritorio. *Redondeado*: barra y botones en forma de píldora. | Clásico |
| **Aureola** | El borde de color que rodea la barra de búsqueda mientras escribes: degradado de KeyFlow, cian, azul, violeta, rosa, rojo, naranja, verde, blanco o sin aureola. | Degradado |
| **Transparencia** | De 0 % (opaco) a 70 %: cuanto más alta, más se ve el escritorio a través de la ventana. | 8 % |
| **Color de fondo** | Siete colores oscuros predefinidos o un código hexadecimal (`#RRGGBB`). | Carbón (`#0B0B0F`) |
| **Tono, Saturación, Brillo** | Ajuste fino del color de fondo. El brillo llega como máximo al 40 % para que el texto blanco siga leyéndose. | — |

## General

| Ajuste | Qué hace | Por defecto |
|---|---|---|
| **Atajo para abrir KeyFlow** | Pulsa el botón y después la combinación nueva (por ejemplo `Ctrl + Mayús + K`). Necesita al menos una tecla modificadora (`Ctrl`, `Alt`, `Mayús` o `Win`), salvo las teclas `F1`–`F24`, que valen solas. `Esc` cancela. Si otra aplicación ya usa esa combinación, KeyFlow avisa y mantiene el atajo anterior. | `Alt + Espacio` |
| **Iniciar con Windows** | Abre KeyFlow al iniciar sesión. Aparece en la pestaña *Inicio* del Administrador de tareas. | Desactivado |
| **Ocultar al hacer clic fuera** | Cierra KeyFlow cuando haces clic en otra ventana. Si lo desactivas, solo se cierra con `Esc` o con el atajo. | Activado |
| **Recordar la última búsqueda** | Al abrir KeyFlow aparece lo último que escribiste, seleccionado: si escribes, lo reemplazas; si pulsas Enter, lo repites. | Desactivado |

## Búsqueda

| Ajuste | Qué hace | Por defecto |
|---|---|---|
| **Mostrar aplicaciones recientes** | Con la barra vacía, enseña primero las apps que abriste hace poco. | Activado |
| **Buscar en la web con Tab** | Activa el cambio a Google / YouTube con la tecla Tab. | Activado |
| **Divisa local** | Moneda a la que se convierte cuando no indicas destino (`100 usd`). *Automática* usa la región configurada en Windows. | Automática |

## Portapapeles

| Ajuste | Qué hace | Por defecto |
|---|---|---|
| **Guardar historial** | Guarda el texto que copias. Al desactivarlo deja de guardar, pero lo que ya está guardado se conserva (puedes vaciarlo con *Borrar todo* en el historial). | Activado |
| **Máximo de elementos** | 25, 50, 100, 200 o 500. Si lo bajas, se borran los elementos más antiguos que sobren. | 100 |

---

Los ajustes se guardan en `%APPDATA%\KeyFlow\settings.json`, salvo *Iniciar con Windows*, que vive en la lista de inicio de Windows.
