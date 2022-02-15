
https://github.com/Klerith/curso-VSCode
https://github.com/Klerith/curso-VSCode/releases

Atajos Teclado:
Menu View--> command palette --> escribir ppor ejemplo: move y se verán los atajos
Orden ascendente: escribir: asc y seleccionar Sort Lines Ascendenting
Alt+flechas: mueve la línea abajo o arriba
Shift+TAB: identa a la izquierda
Ctrl+K + Ctrl+C: Comenta y descomenta líneas
Shift+Alt+A: comenta un bloque dentro de una linea, no  toda la linea sino lo seleccionado en esa linea
Ctrl+Click: encima del nombre de una función, te lleva a dicha función
Alt+F12: puedes ver la función sin salir de la pantalla, abre un cuadro para visualizar
ctrl+Shift+k: borra la línea donde estoy y sube el codigo
Ctrl+Shift+L: selecciona la palabra en donde este repetda y luego puedo borrarlas con ctrl+shift+K
Ctrl+Shift+Z: funciona con deshacer como el ctrl+y
Ctrl+b: oculta la barra lateral de la izquierda
Modo Zen: Ctrl + k y luego Z (solita)
Ctrl+P: abre la busqueda, escribir el archivo que deseamos abrir y enter, asi no se esta abreidno la barra lateral
Ctrl+shit+p: abre para buscar wrap with abreviattion, enter y escribir las etiquetas que quieres poner: code, ejemplo <code>hola</code>
Asignar un atajo: File--> preferencies --> keyboard shorcuts, buscarlo y asignar

ctrl + shift + u : abre y cierra la terminal

Tabs: abrir y reabrir.
Ctrl + w : cierra tab
Ctrl + k Ctrl + w : cierra todos los tabs
Ctrl + shift + t : reabre anterior
Ctrl + tab : cambia de tab

MultiCursor: seleccionar lo mismo en varias líneas 

Clonar lineas: Shift + alt + flecha abajo: (buscar con ctrl+shit+p copy line down .. ojo no es necesario seleccionar toda la linea solo posicionarse en ella. copia la linea abajo

ctrl + shitf + alt + flecha arriba o abajo: seleccionas las lineas (caracter por caracter) y escribes loque deseas
luego shift + flecha puedes ir seleccionando de uno en uno caracter
o alt + shitf + flechas : selecciona toda la palabra de una vez
luego alt + flecha hacia adelante y se posiciona al final de la palabra
luego solo la flecha derecha y va al inicio de la palabra siguiente, luego shift + flecha der y coloco mayuscula
ver video 25.

mayusculas : ctrl + shift + u
minusculas : ctrl + shift + l

quede en el video 26

https://code.visualstudio.com/docs/getstarted/tips-and-tricks

Con la tecla Alt puedo seleccionar varias palabras a la vez de líneas diferentes

poner una lista:
Ctrl+shit+p: abre para buscar wrap with abreviattion, enter y escribir las etiquetas que quieres poner: ul y enter
seleccionar spam y con ctrl+d selecciono cada una de esa etiqueta y escribo li


ctrl+shift+o: abre lista de los métodos, atributos, clases etc de un archivo, 
si luego pulso dos puntos (:) las agrupa por características en común (clases, metodos, etc)

ctrl+g : va a una línea específica, colocar el nro de línea a ir
o ctrl+p , cambiar el @ por : y luego escribir el nro de línea a ir


markdown: vscode tiene integrado el markdown , no como extensión, para visualizar el archivo hacer esto:
ctrl+p signo > y escribir markdown, seleccionar el open preview
o ctrl + shitf+ p y escribir escribir markdown, seleccionar el open preview to the side: esto abre al lado la previsualización  y los cambios se visualizarán en tiempo real
con alt+z: las líneas no se bajan, sino que se visualizan en una sola línea

Reemplazar una definición:
seleccionar la palabra, pulsar F2 y escribir el nuevo nombre
solo cambiará las definiciones no todas las palabras igualas

Para cambiar desde la clase, seleccionar el nombre de la clase, F2 , cambiar nombre, enter y cambiará todo en donde se hace referencia


Snippets: pedazo de código que se puede insertar de forma automática en algún sitio cuando lo necesitemos
Crear : Menpu Code o File -> Preferences -> User snippets enter, seleccionar el lenguaje donde se programara, en este caso typescript.json
escribir en formato json el código:
	"Mostrar Log": {
		"prefix": "ccc",
		"body": [
			"console.log('$1');",
			"$2"
		],
		"description": "Log output to console"
	}
  guardar y listo, ir a un archivo y escribir ccc tab y debería escribirse solo el console.log(...
  el $1 es para poner el cursor en ese punto
  el $2 es para que en el segundo tab vaya a la línea donde esta ese $2
  otro ejemplo: "console.log('${1:'Hola Mundo'}');", -- selecciona lo que está en las llaves


Extensiones:
https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype

ToDo:
https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree
https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight

bookmarks:
https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks

icon theme:
https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme

Material theme:

Live Server:

bracket pair colorizer 2:

Todas las extensiones del profesor: https://gist.github.com/Klerith/5a572bf9835b090d4cd8304d523365c7

