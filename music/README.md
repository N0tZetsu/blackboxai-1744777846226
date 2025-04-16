# Carpeta de Música

Esta carpeta es donde debes colocar los archivos de audio que se reproducirán durante la pantalla de carga.

## Formato de Archivos
- Formato requerido: MP3
- Calidad recomendada: 320kbps
- Duración: Sin límite específico, pero considera el tiempo promedio de carga
- Tamaño recomendado: Menos de 10MB por archivo para optimizar los tiempos de carga

## Cómo Agregar Música
1. Nombra tus archivos de música de manera descriptiva (ejemplo: `cancion1.mp3`, `cancion2.mp3`)
2. Asegúrate que los nombres coincidan con los configurados en `config.lua`
3. Verifica que las canciones estén en formato MP3 y optimizadas

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
- Usa archivos MP3 de buena calidad pero optimizados
- Asegúrate de tener los derechos o permisos necesarios para usar la música
- Mantén un volumen consistente entre todas las canciones
- Considera usar música que represente bien el estilo de tu servidor

## Importante
Asegúrate de que cada canción tenga su correspondiente:
1. Archivo de video en la carpeta `/video`
2. URL de portada del álbum configurada en `config.lua`
3. Información correcta de título y artista en la configuración
