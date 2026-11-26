# Preguntas frecuentes y solución de problemas

### KeyFlow App se abre pero no muestra resultados
Falta **Node.js**. KeyFlow App lo usa para buscar apps, convertir divisas, gestionar alarmas, etc. Instala [Node.js](https://nodejs.org/) 20 o superior (la versión LTS vale), asegúrate de que queda en el `PATH` (el instalador lo hace por defecto) y vuelve a abrir KeyFlow App.

### Windows dice «Windows protegió su PC» al instalar
El instalador no está firmado digitalmente, así que SmartScreen no lo reconoce. Pulsa **Más información → Ejecutar de todas formas**.

### Alt + Espacio no abre KeyFlow App
Otra aplicación está usando ese atajo (por ejemplo PowerToys Run u otro lanzador). Cierra esa app o elige otro atajo en **Ajustes → General → Atajo para abrir KeyFlow App**. Puedes abrir KeyFlow App mientras tanto desde su icono en la bandeja del sistema.

### No encuentro una app que acabo de instalar
Busca el comando **Recargar aplicaciones** para que KeyFlow App vuelva a leer el menú Inicio.

### «Mostrar en el explorador de archivos» dice que no encuentra la carpeta
Pasa con los accesos que no son programas: enlaces a páginas web y elementos de Windows como *Este equipo* o *Panel de control*. No tienen carpeta en el disco.

### «Ejecutar como administrador» no funciona con algunas apps
Windows no permite elevar las apps de la Microsoft Store; KeyFlow App lo avisa.

### Las conversiones de divisas no se actualizan
Los tipos de cambio se descargan una vez al día. Sin conexión, KeyFlow App usa los últimos que descargó; la tarjeta indica cuándo se actualizaron.

### ¿KeyFlow App envía mis datos a algún sitio?
No. Todo se guarda en tu PC. KeyFlow App solo se conecta a internet para descargar los tipos de cambio, y abre tu navegador cuando haces una búsqueda web.

### ¿Dónde guarda KeyFlow App sus datos?
En `%APPDATA%\KeyFlow` (pega esa ruta en la barra del Explorador):

| Archivo | Contenido |
|---|---|
| `settings.json` | Ajustes |
| `clipboard-history.json` | Historial del portapapeles |
| `alarms.json` | Alarmas |
| `frecency.json` | Apps usadas y recientes |
| `emoji-recent.json` | Emojis recientes |
| `rates.json` | Tipos de cambio descargados |
| `icons\` | Iconos de las apps |

### ¿Cómo cierro KeyFlow App del todo?
Clic derecho en su icono de la bandeja del sistema → **Salir**, o busca el comando **Salir de KeyFlow App**. Al cerrar la ventana con `Esc` KeyFlow App sigue en marcha (por eso funcionan el atajo y las alarmas).

### ¿Cómo lo desinstalo?
**Configuración de Windows → Aplicaciones → KeyFlow App → Desinstalar**. Si quieres borrar también tus datos, elimina la carpeta `%APPDATA%\KeyFlow`. Si activaste *Iniciar con Windows*, desactívalo antes en los ajustes.
