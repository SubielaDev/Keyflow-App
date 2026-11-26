# Guía de uso

KeyFlow App es una barra de búsqueda que aparece encima de cualquier ventana. Se abre con **Alt + Espacio** (el atajo se puede cambiar en los [ajustes](ajustes.md)), escribes lo que quieres y pulsas **Enter**.

- [Abrir y cerrar KeyFlow App](#abrir-y-cerrar-keyflow-app)
- [Aplicaciones](#aplicaciones)
- [Calculadora](#calculadora)
- [Conversor de divisas](#conversor-de-divisas)
- [Búsqueda en la web](#búsqueda-en-la-web)
- [Historial del portapapeles](#historial-del-portapapeles)
- [Emojis](#emojis)
- [Selector de color](#selector-de-color)
- [Cronómetro](#cronómetro)
- [Alarmas y temporizador](#alarmas-y-temporizador)
- [Comandos de KeyFlow App](#comandos-de-keyflow-app)
- [Atajos de teclado](#atajos-de-teclado)

---

## Abrir y cerrar KeyFlow App

| Acción | Cómo |
|---|---|
| Abrir / cerrar | `Alt + Espacio` |
| Cerrar | `Esc` con la barra vacía, o hacer clic fuera de la ventana |
| Borrar lo escrito | `Esc` con texto en la barra |
| Volver de un panel (emojis, ajustes…) | `Esc` o la flecha **←** de arriba a la izquierda |

KeyFlow App se queda en la **bandeja del sistema** (junto al reloj). Desde su icono puedes mostrarlo, abrir los **Ajustes** o **Salir**.

## Aplicaciones

Escribe parte del nombre de cualquier programa del menú Inicio: apps de escritorio, de la Microsoft Store y juegos de Steam, cada uno con su icono.

- No hace falta escribir el nombre entero: valen las iniciales o letras sueltas en orden (`vsc` encuentra *Visual Studio Code*).
- Las apps que más abres suben en los resultados.
- Con la barra vacía verás tus **apps recientes** y debajo el resto, de la A a la Z.

**Clic derecho sobre una app:**

| Opción | Qué hace |
|---|---|
| Abrir | Abre la app (lo mismo que Enter). |
| Mostrar en el explorador de archivos | Abre la carpeta del programa con su ejecutable seleccionado. En los juegos de Steam abre su carpeta de instalación y en las apps de la Store la carpeta del paquete (Windows puede pedir permiso para entrar). |
| Ejecutar como administrador | Abre la app con permisos de administrador (Windows mostrará su aviso de control de cuentas). No disponible para apps de la Microsoft Store. |
| Quitar de recientes | La quita de la lista de recientes (solo aparece si la app está en ella). |

> Si acabas de instalar un programa y no aparece, usa el comando **Recargar aplicaciones**.

## Calculadora

Escribe la operación directamente; el resultado aparece en una tarjeta y **Enter** lo copia al portapapeles.

| Escribe | Resultado |
|---|---|
| `12*(3+4)` | 84 |
| `6 ÷ 2 × 3` | 9 |
| `1,5+2` | 3,5 (la coma decimal también vale) |
| `20% de 150` | 30 |
| `150 + 10%` · `150 - 10%` | 165 · 135 |
| `2^10` | 1024 |
| `2pi` · `3(4+1)` | 6,283… · 15 (multiplicación implícita) |

**Funciones:** `sqrt` / `raiz`, `cbrt`, `abs`, `round` / `redondear`, `floor`, `ceil`, `exp`, `ln`, `log` (base 10), `sin` / `sen`, `cos`, `tan` (en grados).
**Constantes:** `pi` (o `π`) y `e`.

## Conversor de divisas

Escribe una cantidad y una moneda:

| Escribe | Convierte |
|---|---|
| `100 usd` | 100 dólares a tu moneda local (y a USD/EUR) |
| `50 € a jpy` | 50 euros a yenes |
| `$100 eur` | 100 dólares a euros |
| `1.000,50 gbp en usd` | 1.000,50 libras a dólares |

- Acepta códigos (`usd`, `eur`, `mxn`…), símbolos (`$ € £ ¥ ₹ ₩ ₽ ₺ ₿`) y nombres (`dólares`, `euros`, `libras`, `yenes`…).
- Para indicar el destino vale `a`, `en`, `to`, `in`, `=` o `→`.
- Sin destino, convierte a tu **moneda local**, que se toma de la región de Windows o de la que elijas en los ajustes.
- **Enter** copia el resultado.
- Más de 160 monedas. Los tipos de cambio son diarios ([ExchangeRate-API](https://www.exchangerate-api.com)); sin conexión se usan los últimos descargados.

## Búsqueda en la web

1. Escribe lo que quieras buscar.
2. Pulsa **Tab**: el icono de la izquierda cambia a **Google**.
3. Pulsa **Tab** otra vez para **YouTube**, y una tercera vez para volver a la búsqueda normal (`Shift + Tab` va al revés).
4. **Enter** abre la búsqueda en tu navegador predeterminado.

Con la barra vacía, Enter abre la página principal de Google o YouTube. `Esc` sale del modo web sin borrar lo escrito.

## Historial del portapapeles

Busca **portapapeles** y abre *Historial del portapapeles*. Ahí está todo el texto que has copiado, lo más reciente arriba.

| Tecla | Acción |
|---|---|
| `Enter` o clic | Lo pega en la app en la que estabas |
| `Ctrl + Enter` | Solo lo copia |
| `Supr` | Lo borra del historial |
| Clic derecho | Pegar, Copiar o Eliminar |

- Solo guarda **texto** y se queda **en tu PC**.
- El botón **Borrar todo** vacía el historial (pide confirmación).
- No se guarda lo que los gestores de contraseñas marcan como privado.
- El número máximo de elementos (25 a 500) y si se guarda o no se cambian en los [ajustes](ajustes.md#portapapeles).

## Emojis

Busca **emoji** y abre *Emojis*. Escribe en español o en inglés (`fuego`, `fire`, `corazón`…) o navega por categorías con las flechas.

- **Enter** o clic: pega el emoji en la app en la que estabas.
- **Ctrl + Enter**: solo lo copia.
- Arriba aparecen los últimos que has usado.

## Selector de color

Busca **color** y abre *Selector de color*. El cursor se convierte en una flecha oscura: haz clic en cualquier punto de la pantalla para capturar su color.

- El color se copia en hexadecimal (por ejemplo `#8B3BF0`) y KeyFlow App lo muestra en una tarjeta con sus valores RGB.
- `Esc` cancela. Si no eliges nada en 60 segundos, se cancela solo.

## Cronómetro

Busca **cronómetro**. Botones **Iniciar / Pausar / Reanudar**, **Vuelta** para marcar tiempos parciales y **Reiniciar**. Sigue contando aunque ocultes la ventana de KeyFlow App.

## Alarmas y temporizador

Busca **alarmas** o **temporizador**.

| Tipo | Para qué |
|---|---|
| **Una vez** | Suena a una hora concreta, la próxima vez que llegue. |
| **Repetir** | Suena a una hora los días de la semana que elijas. |
| **Temporizador** | Cuenta atrás. Hay duraciones rápidas: 1, 3, 5, 10, 15, 20, 25, 30, 45, 60, 90 y 120 minutos. |

- Cada alarma puede llevar un nombre y uno de cuatro sonidos tranquilos: **Cuenco**, **Marimba**, **Gotas** o **Amanecer** (puedes escucharlos antes de elegir).
- Haz clic en una alarma de la lista para editarla; el interruptor la activa o desactiva.
- Cuando suena, KeyFlow App aparece en pantalla con **Detener** y **Posponer 5 min**. Si nadie la para, deja de sonar sola a los 5 minutos.
- Las alarmas funcionan aunque la ventana de KeyFlow App esté cerrada, siempre que KeyFlow App siga en marcha (icono en la bandeja).

## Comandos de KeyFlow App

Además de lo anterior, puedes buscar estos comandos:

| Comando | Qué hace |
|---|---|
| Ajustes de KeyFlow App | Abre los [ajustes](ajustes.md) (también con `Ctrl + ,` o el engranaje de abajo a la derecha). |
| Recargar aplicaciones | Vuelve a leer las apps del menú Inicio. |
| Salir de KeyFlow App | Cierra KeyFlow App por completo. |

## Atajos de teclado

| Atajo | Dónde | Acción |
|---|---|---|
| `Alt + Espacio` | En cualquier sitio | Abrir / cerrar KeyFlow App (configurable) |
| `↑` `↓` | Resultados | Moverse |
| `Enter` | Resultados | Abrir, ejecutar o copiar |
| `Tab` / `Shift + Tab` | Barra | Cambiar entre Google, YouTube y la búsqueda normal |
| `Ctrl + ,` | Barra | Abrir los ajustes |
| `Esc` | En cualquier vista | Borrar, volver atrás o cerrar |
| `Ctrl + Enter` | Emojis y portapapeles | Copiar en vez de pegar |
| `Supr` | Portapapeles | Borrar el elemento seleccionado |
