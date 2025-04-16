# Carpeta de Videos

Esta carpeta es donde debes colocar los videoclips que se mostrarán de fondo durante la pantalla de carga.

## Formato de Archivos
- Formato recomendado: MP4
- Resolución recomendada: 1920x1080
- Duración: Se recomienda que coincida con la duración de la canción
- Codec recomendado: H.264

## Cómo Agregar Videos
1. Nombra tus archivos de video de manera descriptiva (ejemplo: `video1.mp4`, `video2.mp4`)
2. Asegúrate que los nombres coincidan con los configurados en `config.lua`
3. Los videos deben estar optimizados para web para evitar tiempos de carga largos

## Ejemplo de Configuración en config.lua
```lua
Config.MediaList = {
    {
        title = "Nombre de la Canción",
        artist = "Nombre del Artista",
        music = "music/cancion1.mp3",
        video = "video/video1.mp4",
        cover = "URL_de_la_portada"
    }
}
```

## Recomendaciones
- Usa videos con buena calidad pero optimizados para web
- Evita videos muy pesados que puedan ralentizar la carga
- Asegúrate que el video tenga una transición suave al repetirse
- Considera usar videos con un efecto de desenfoque o abstractos para no distraer demasiado
