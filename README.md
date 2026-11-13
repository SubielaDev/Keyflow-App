<p align="center">
  <img src="assets/logo.png" width="96" alt="KeyFlow">
</p>

<h1 align="center">KeyFlow</h1>

<p align="center">Lanzador rápido para Windows: abre apps, calcula, convierte divisas, busca en la web y mucho más desde una sola barra.</p>

<p align="center">
  <a href="../../releases/latest"><b>⬇ Descargar el instalador</b></a>
</p>

<p align="center">
  <a href="https://ko-fi.com/subidev"><img src="https://img.shields.io/badge/Ko--fi-Support%20Me-FF5E5B?logo=ko-fi&logoColor=white" alt="Ko-fi"></a>
</p>

---

## Instalación

1. Descarga `KeyFlow_0.1.0_x64-setup.exe` desde [Releases](../../releases/latest).
2. Ejecútalo y sigue el asistente.
3. Pulsa **Alt + Espacio** para abrir KeyFlow.

### Requisitos

- Windows 10 u 11 (64 bits).
- **[Node.js](https://nodejs.org/) 20 o superior** instalado y disponible en el `PATH`. KeyFlow lo usa para buscar apps, convertir divisas, gestionar alarmas, etc. Sin Node.js la ventana abre pero no muestra resultados.

> El instalador no está firmado digitalmente, así que Windows SmartScreen puede mostrar el aviso «Windows protegió su PC». Pulsa **Más información → Ejecutar de todas formas**.

---

## Funciones

### 🔎 Buscador de aplicaciones
- Encuentra cualquier app del menú Inicio, incluidas las de la Microsoft Store y los juegos de Steam, con sus iconos.
- Con la barra vacía muestra tus **apps recientes** y debajo el resto, de la A a la Z.
- Aprende de lo que usas: lo que abres más sube en los resultados.
- **Clic derecho** en una app:
  - Abrir
  - Mostrar en el explorador de archivos
  - Ejecutar como administrador
  - Quitar de recientes

### 🧮 Calculadora
Escribe la operación directamente en la barra: `12*(3+4)`, `20% de 150`, `150 + 10%`, `sqrt(16)`, `sin 30`, `2pi`… El resultado aparece en una tarjeta y **Enter** lo copia.

### 💱 Conversor de divisas
- `100 usd`, `50 € a yenes`, `1.000,50 gbp en eur`…
- Más de 160 monedas, con banderas.
- Sin moneda de destino, convierte a tu **moneda local** (según la región de Windows) y además a USD/EUR.
- Tipos de cambio diarios de [ExchangeRate-API](https://www.exchangerate-api.com).

### 🌐 Búsqueda en la web
Escribe algo y pulsa **Tab** para buscar en **Google**, **Tab** otra vez para **YouTube**. El icono de la izquierda indica dónde vas a buscar y **Enter** abre el navegador.

### 📋 Historial del portapapeles
- Guarda lo último que copias (solo texto, hasta 500 elementos y solo en tu PC).
- **Enter** pega en la app en la que estabas; **Ctrl+Enter** solo copia; **Supr** borra.
- Respeta el contenido que los gestores de contraseñas marcan como privado: no se guarda.

### 😀 Emojis
Busca emojis en español o en inglés («fuego», «fire»…). **Enter** lo pega en la app anterior y **Ctrl+Enter** lo copia. Recuerda los que usas más.

### 🎨 Selector de color
Un cuentagotas para elegir cualquier píxel de la pantalla. El color se copia en hexadecimal y se muestra en una tarjeta con sus valores RGB.

### ⏱ Cronómetro, alarmas y temporizador
- **Cronómetro** con vueltas.
- **Alarmas** de una vez o repetidas por días de la semana.
- **Temporizador** con duraciones rápidas (1 min, 5 min, 25 min…).
- Cuatro sonidos tranquilos (cuenco, marimba, gotas, amanecer), con posposición de 5 minutos.

---

## Ajustes

Ábrelos con el **engranaje** de la esquina inferior derecha, con **Ctrl + ,**, buscando «ajustes» o desde el icono de la bandeja del sistema. Cada sección tiene su botón **Restablecer** para volver a los valores originales.

| Sección | Opciones |
|---|---|
| **Apariencia** | Estilo *Clásico* o *Redondeado* · color de la aureola de la barra (degradado, colores o ninguna) · transparencia · color de fondo con tono, saturación y brillo |
| **General** | Atajo para abrir KeyFlow · iniciar con Windows · ocultar al hacer clic fuera · recordar la última búsqueda |
| **Búsqueda** | Mostrar apps recientes · búsqueda web con Tab · divisa local |
| **Portapapeles** | Guardar historial · máximo de elementos (25–500) |

---

## Atajos de teclado

| Atajo | Acción |
|---|---|
| `Alt + Espacio` | Abrir / cerrar KeyFlow (configurable) |
| `↑` `↓` | Moverse por los resultados |
| `Enter` | Abrir o ejecutar el resultado |
| `Tab` / `Shift + Tab` | Cambiar entre Google, YouTube y la búsqueda normal |
| `Ctrl + ,` | Abrir los ajustes |
| `Esc` | Borrar la búsqueda, volver atrás o cerrar |

---

## Privacidad

- Todo se guarda en tu PC, en `%APPDATA%\KeyFlow`.
- KeyFlow solo se conecta a internet para descargar los tipos de cambio y cuando tú abres una búsqueda web.

---

## Apoya el proyecto

KeyFlow es gratis. Si te resulta útil, puedes invitarme a un café en Ko-fi:

[![Ko-fi](https://img.shields.io/badge/Ko--fi-Support%20Me-FF5E5B?logo=ko-fi&logoColor=white)](https://ko-fi.com/subidev)

---

© 2026 SubielaDev. Todos los derechos reservados.
