# Cartelera

App personal para iPhone con las series y películas que quiero ver y las que ya vi. Busca en toda la base de TMDB y muestra en qué plataformas de streaming está cada título en Chile (suscripción, gratis, arriendo o compra).

## Instalar en el iPhone

1. Abre https://pablocarvallo.github.io/cartelera/ en Safari.
2. Toca **Compartir → Agregar a inicio**.

## Primera vez: conectar TMDB

La búsqueda y las plataformas vienen de [The Movie Database (TMDB)](https://www.themoviedb.org), que entrega una clave gratuita de uso personal.

1. Crea una cuenta en themoviedb.org.
2. Ve a **Configuración → API** y solicita una clave de tipo personal.
3. Copia el **Token de acceso de lectura de la API** y pégalo en la app, en **Ajustes**.

La clave queda guardada solo en el teléfono.

## Cómo funciona

- **Quiero ver**: tu lista pendiente, con los logos de las plataformas donde está cada título. Puedes filtrar por película o serie y por plataforma. Las plataformas se revisan solas cada 3 días.
- **Vistos**: lo que ya viste, ordenado por mes, con la fecha y una nota de 1 a 5 estrellas.
- **Buscar**: busca series y películas; con el botón **+** las agregas directo a Quiero ver.

## Importar el historial de Netflix

En **Ajustes → Historial de Netflix** (o desde Vistos, cuando está vacío) puedes importar el archivo de tu actividad de Netflix:

1. En Safari, entra a netflix.com/viewingactivity con tu perfil, baja hasta el final y toca **Descargar todo**.
2. En la app, toca **Importar archivo de Netflix** y elige `NetflixViewingHistory.csv` (queda en Archivos → Descargas).

La app agrupa los episodios en su serie, busca cada título en TMDB y lo deja en Vistos con la fecha de la última vez que lo viste y la cantidad de episodios. También acepta `ViewingActivity.csv` de la solicitud de datos personales de Netflix (permite elegir el perfil). Los títulos que no se puedan identificar quedan en una lista para elegirlos a mano. El archivo se lee en el teléfono y no se sube a ningún lado.

Las listas se guardan solo en el dispositivo. En **Ajustes → Respaldo** puedes exportarlas a un archivo e importarlas en otro teléfono.

Cartelera usa la API de TMDB, pero no está respaldada ni certificada por TMDB. La disponibilidad en plataformas proviene de JustWatch.
