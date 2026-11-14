<p align="center">
  <img src="imagenes/logo.png" width="84" alt="PKAI">
</p>

<h1 align="center">PKAI · PC y móvil</h1>

<p align="center">
  El editor de partidas, para <b>Windows</b> y <b>Android</b>.<br>
  <a href="../README.md">← Volver al inicio</a> · <a href="PKAI-Link.md">PKAI Link (Switch y 3DS) →</a>
</p>

---

## Qué puedes hacer

- 📂 **Abrir partidas de todas las generaciones** (ver [la lista de juegos](#juegos-que-abre)). PKAI dice de qué juego y de qué consola es cada una.
- 📦 **Ver y ordenar las cajas y el equipo:** mover Pokémon arrastrándolos, marcar varios a la vez, buscar por especie, movimiento, tipo o variocolor, y ordenar por Pokédex, nivel o tipo.
- ✏️ **Editar cualquier Pokémon:** estadísticas, IV y EV, movimientos, naturaleza, habilidad, objeto, Ball, variocolor, teratipo, encuentro y entrenador.
- ✅ **Comprobar la legalidad** antes de guardar. Con el «Modo legal», PKAI no deja hacer cambios que lo volverían ilegal.
- 🎁 **Catálogo de eventos, intercambios y regalos** de todas las generaciones, sin conexión. Cada uno se convierte a tu partida y solo se ofrece si sale legal.
- 🎒 **Mochila, dinero, tiempo de juego, Pokédex y Living Dex** (rellenar las que faltan con Pokémon legales).
- 🏅 **Progreso de la partida:** medallas, legendarios (hacerlos volver para capturarlos otra vez), Pokémon errantes y guardería.
- 🔍 **Comparar dos versiones de una partida:** qué ha cambiado desde una copia de seguridad o desde que la abriste.
- 🤖 **El asistente:** le pides las cosas con tus palabras y las hace él (ver [El asistente](#el-asistente)).
- 🎮 **Partidas de la consola por wifi** con [PKAI Link](PKAI-Link.md).
- 🌍 En **español, inglés e italiano**, con los nombres oficiales de cada idioma.

## Capturas

<table>
  <tr>
    <td width="50%"><img src="imagenes/pkai-inicio.png" alt="El inicio de PKAI"><br><sub>El inicio: abre una partida del equipo o de la consola.</sub></td>
    <td width="50%"><img src="imagenes/pkai-cajas.png" alt="Las cajas"><br><sub>Las cajas, el equipo y el Pokémon elegido, con su legalidad.</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="imagenes/pkai-editor.png" alt="El editor de un Pokémon"><br><sub>El editor: estadísticas, movimientos, encuentro, legalidad…</sub></td>
    <td width="50%"><img src="imagenes/pkai-asistente.png" alt="El asistente creando un Pokémon"><br><sub>El asistente crea un Charizard variocolor legal y lo añade.</sub></td>
  </tr>
</table>

<p align="center">
  <img src="imagenes/pkai-movil-cajas.png" alt="PKAI en el móvil: las cajas" width="260">
  &nbsp;&nbsp;
  <img src="imagenes/pkai-movil-asistente.png" alt="PKAI en el móvil: el asistente" width="260">
  <br><sub>PKAI Móvil: lo mismo, adaptado a la pantalla táctil.</sub>
</p>

## Instalar

### Windows

Hay dos versiones, con las mismas funciones. Elige la que prefieras:

**Con instalador**
1. Descarga `PKAI-PC-<versión>-Instalador.exe` de [la última versión](https://github.com/wyldts/pkai/releases/latest).
2. Ábrelo y pulsa **Instalar**. Se instala en tu usuario, sin ser administrador, con un acceso en el menú Inicio (y, si quieres, en el escritorio).
3. Para desinstalarlo: Configuración de Windows → Aplicaciones instaladas → PKAI.

**Portable (sin instalar)**
1. Descarga `PKAI-PC-<versión>-Portable.zip` de [la última versión](https://github.com/wyldts/pkai/releases/latest).
2. Descomprímelo donde quieras: en Documentos, en otra unidad o en un USB. Sale una carpeta `PKAI`.
3. Abre `PKAI.exe` de esa carpeta. No crea accesos directos ni toca el registro de Windows.
4. Todo lo suyo (partidas recientes, copias de seguridad y ajustes) se guarda en la carpeta `Datos`, junto al programa. Puedes mover la carpeta `PKAI` entera a otro sitio, y para quitarlo basta con borrarla.
5. Se actualiza igual que la otra, con **Actualizar**, y conserva la carpeta `Datos`. No borres el archivo `portable.txt`: es el que le dice que es la portable.

Las dos necesitan WebView2 de Microsoft, que ya viene con Windows 11. En Windows 10, el instalador avisa si falta; si usas la portable y PKAI no se abre, instálalo desde [la página de Microsoft](https://developer.microsoft.com/microsoft-edge/webview2/).

### Android
1. Descarga `PKAI-Movil-<versión>.apk` en el móvil.
2. Ábrelo. La primera vez, Android pide permiso para instalar apps de fuera de la Play Store: dáselo al navegador o a la app de archivos con la que lo abras.

## Cómo se usa

### 1. Abrir una partida
- **Abrir partida…** y elige el archivo: `main`, `.sav`, `.dsv`, `.dat`, `.gci`, `.bin`…
- O **Abrir desde la Switch o la 3DS…** para traerla de la consola por wifi (con [PKAI Link](PKAI-Link.md)).
- Las partidas que abras salen después en **Recientes**, con la carátula de su juego.

Las partidas tienen que estar descifradas, como las sacan los gestores de partidas (Checkpoint, JKSV, JKSM…) o PKAI Link.

### 2. Las cajas
- Un clic elige un Pokémon y lo enseña a la derecha, con su legalidad. Doble clic (o **Enter**) lo edita. En un hueco vacío, **Enter** añade uno nuevo.
- **Mover:** arrástralo a otro hueco, a otra caja (déjalo un momento sobre las flechas) o al equipo. También con **M** y un clic en el destino.
- **Marcar varios:** clic derecho, Ctrl + clic o **Espacio**. En el móvil, mantén pulsado. Con varios marcados puedes moverlos, liberarlos, exportarlos o cambiarlos todos de una vez.
- **Buscar:** la lupa (o **F**) atenúa los que no cumplen y te lleva de un resultado a otro.
- Toca el nombre de la caja para cambiarle el **nombre y el fondo**, como en el juego.

### 3. Editar un Pokémon
El editor tiene pestañas: **Estadísticas**, **Movimientos**, **Principal**, **Encuentro**, **Cosmético**, **Entrenador** y **Legalidad**.
- Con el **Modo legal** encendido, solo deja elegir lo que puede ser legal en tu juego.
- La pestaña **Legalidad** dice qué falla y por qué, con arreglos automáticos cuando los hay, y **Rehacer legal**, que lo vuelve a crear legal conservando todo lo posible.

### 4. Guardar y copias de seguridad
- **Guardar** (o **Ctrl+S**) escribe la partida. Hasta entonces, todo se deshace con **Ctrl+Z**.
- **Antes de tocar una partida, PKAI guarda una copia de seguridad.** Las tienes en el inicio, en **Ver copias**.
- **Herramientas → Comparar cambios…** enseña qué ha cambiado: el dinero, los Pokémon nuevos, los cambiados (y si siguen siendo legales), los movidos, la mochila…

### 5. Llevarla a la consola
- Si la abriste desde la Switch o la 3DS, pulsa **Enviar a la Switch** (o a la 3DS) en la pantalla de cajas. PKAI te enseña antes qué va a cambiar en la consola.
- Si no, cópiala a la consola con tu gestor de partidas, como siempre.

## El asistente

Pulsa **Asistente** en la pantalla de cajas y escríbele (o díctale con el micrófono). Tiene las mismas herramientas que tú y las usa por ti:

| Le dices | Hace |
|---|---|
| «Créame un Charizard variocolor legal» | Lo crea desde un encuentro legal de tu juego y lo añade. |
| «¿Tengo algún Pokémon ilegal?» | Revisa el equipo y todas las cajas. |
| «Arregla los ilegales de la caja 1» | Los legaliza, si se puede. |
| «Prepara a Garchomp para competitivo» | Naturaleza, IV, EV, movimientos y objeto. |
| «Añade todos los Pokémon de intercambio y de regalo desde la caja 10» | Los pone uno de cada en los huecos libres (solo si caben todos). |
| «Dame 99 caramelos raros» · «Ponme 100000 de dinero» | Lo hace al momento. |
| «¿Qué he cambiado?» | Compara con lo que había al abrir la partida. |
| «Ordena las cajas por número de Pokédex» | Las ordena. |

- Antes de hacer algo que cambia muchos Pokémon de golpe, o que los dejaría ilegales, te pide que lo confirmes.
- Antes de liberar, te enseña las tarjetas de los Pokémon y espera tu «sí».
- Solo habla de Pokémon y de tu partida.
- Necesita internet y tiene un **límite de uso al día**. Todo lo demás de PKAI funciona sin conexión.

## Atajos de teclado

| Tecla | Qué hace |
|---|---|
| **Q** / **E** | Caja anterior / siguiente |
| **Enter** | Editar el Pokémon (o añadir uno en un hueco vacío) |
| **M** | Mover |
| **Espacio** | Marcar varios (también clic derecho) |
| **F** | Buscar en las cajas |
| **X** | Herramientas |
| **Supr** | Liberar |
| **Ctrl+Z** | Deshacer |
| **Ctrl+S** | Guardar |

También se maneja con un **mando**.

## Juegos que abre

| Generación | Juegos |
|---|---|
| 1.ª | Rojo, Azul, Verde y Amarillo (también los de la consola virtual de 3DS) · Stadium |
| 2.ª | Oro, Plata y Cristal (también los de la consola virtual de 3DS) · Stadium 2 |
| 3.ª | Rubí, Zafiro, Esmeralda, Rojo Fuego y Verde Hoja · Colosseum, XD y Pokémon Box |
| 4.ª | Diamante, Perla, Platino, HeartGold y SoulSilver · Battle Revolution y Mi Rancho Pokémon |
| 5.ª | Negro, Blanco, Negro 2 y Blanco 2 |
| 6.ª | X, Y, Rubí Omega y Zafiro Alfa |
| 7.ª | Sol, Luna, Ultrasol y Ultraluna · Let's Go, Pikachu y Let's Go, Eevee |
| 8.ª | Espada, Escudo, Diamante Brillante, Perla Reluciente y Leyendas Arceus |
| 9.ª | Escarlata, Púrpura y Leyendas Z-A |

También abre Pokémon sueltos (`.pk*`), regalos misteriosos (`.wc*`, `.pgf`, `.pcd`…) y tarjetas de memoria de GameCube.

## Preguntas frecuentes

**¿Puedo estropear mi partida?**
PKAI guarda una copia antes de tocarla, y todo se deshace con Ctrl+Z hasta que guardas. Aun así, haz tu propia copia la primera vez.

**¿Los Pokémon que crea son legales?**
Se crean desde encuentros, eventos e intercambios reales de cada juego y se comprueban antes de añadirlos. Si algo no puede ser legal en tu juego, PKAI lo dice con el motivo.

**¿Necesito internet?**
Solo para el asistente y para ver si hay una versión nueva. Abrir, editar y guardar funciona sin conexión.

**¿Cómo se actualiza?**
Cuando hay una versión nueva, el inicio enseña **Actualizar**. Se descarga e instala dentro de la app, sin perder tus partidas ni tus copias.
