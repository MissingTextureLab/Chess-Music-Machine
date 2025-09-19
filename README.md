# Chess Music Machine

Un proyecto en **Python** que sonoriza partidas de ajedrez en archivos **PGN**, inspirado en la performance de **Duchamp y Cage, "La reunión"**.  
Utiliza las librerías **python-chess**, **mido** y **chessboard**.  
La comunicación entre Python y el DAW se realiza mediante **LoopMIDI**, creando un puerto MIDI virtual capaz de controlar cualquier **VST, instrumento, sonido o efecto**.

---

## Características
- Lectura de partidas en formato **PGN** (ejemplo incluido: `morphy_duke_karl_count_isouard_1858.pgn`).
- Visualización dinámica del tablero con la librería **chessboard**.
- Mapeo de casillas a una amplia paleta de acordes: mayores, menores, séptimas, aumentados y sus4.
- Generación de mensajes MIDI con **mido**, listos para ser recibidos por sintetizadores, DAWs o motores de audio/visualización como Unity.
- Flujo en vivo: al avanzar cada jugada se apagan las notas del acorde anterior y se encienden las nuevas.

---

## Uso
1. Conecta o selecciona un puerto MIDI.  
2. Asígnalo en un DAW a un instrumento VST.  
3. Carga una partida PGN y ejecuta el script.  

---

## Dependencias
```bash
pip install python-chess mido chessboard
```

---

## Características
1. Explorar escalas y modos alternativos.
2. Sincronizar con tempo y secuenciadores externos.
3. Generar visualizaciones audiovisuales en Unity o TouchDesigner.
4. Jugar partidas en vivo y escuchar cómo emergen nuevas sonoridades de cada movimiento.
5. Aumentar el número de reglas (cantidad de piezas en el tablero, tipo de pieza que cae en la casilla, etc).

---

## Marco conceptual
Este proyecto explora las sinergias entre la práctica deportiva y la artística a través de los entornos virtuales.
A partir de esta búsqueda, se propone una reflexión —desde la perspectiva de la ludología— sobre las reglas como fundamento común y punto de encuentro entre ambos ámbitos.

---