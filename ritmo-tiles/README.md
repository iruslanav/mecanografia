# 🎵 Ritmo Tiles

Juego de ritmo en el navegador con **dos modos**:

- **🎹 Piano Tiles** — pulsa la columna correcta cuando la ficha llega a la línea, sin saltarte el orden.
- **🎸 Guitar Hero** — acierta la tecla del carril en el momento justo (Perfect / Great / Good), 5 carriles.

Todo funciona **offline y sin archivos externos**: el sonido se genera en tiempo real con la **Web Audio API** (un mini-sintetizador tipo MIDI integrado). Cada acierto reproduce su nota, así que *tú tocas la canción*.

## 🎼 Canciones

Melodías de **dominio público** + **temas originales** (marcados con ★), con distintos niveles de dificultad:

| Canción | Estilo | Dificultad |
|---|---|---|
| Estrellita | Piano | Fácil |
| Himno de la Alegría | Piano | Fácil |
| Canon en Re | Piano | Media |
| Aventura Espacial ★ | Épico/espacial | Media |
| Für Elise | Piano | Difícil |
| Plataformas 8-bit ★ | Chiptune | Difícil |
| Marcha Turca | Piano | Difícil |

> No se incluyen temas con copyright (Mario Bros, Star Wars…). En su lugar hay tracks originales que evocan esos estilos: uno épico-espacial y uno chiptune de plataformas.

## 🎮 Controles

- **Piano Tiles:** teclas `D` `F` `J` `K` (o toca la pantalla).
- **Guitar Hero:** teclas `A` `S` `D` `K` `L` (o toca la pantalla).
- **Pausa:** `Esc` o `P`.

La dificultad depende de la velocidad de caída (BPM) y de la densidad de notas. Se guarda tu **récord** por canción y modo.

## ▶️ Cómo ejecutar

Abre `index.html` en cualquier navegador moderno. No necesita servidor ni instalación.

## 🛠️ Tecnología

HTML + CSS + JavaScript puro, `<canvas>` para el render y Web Audio API para el sonido. Un único archivo, sin dependencias.
