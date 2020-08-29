# Peliculas App
Aplicación en Flutter que muestra las películas que se encuentran actualmente en Cine y las películas más populares en un infinite scroll. Dentro de la descripción de cada película se muestran también los actores que intervienen en ella. Para obtener las películas se usa la API de The Movie Database.

<p>
    <img src="https://res.cloudinary.com/dzgd10ssq/image/upload/v1598664289/Apps/yvob258bqu0pocviaxio.gif" / hspace="5"> 
    <img src="https://res.cloudinary.com/dzgd10ssq/image/upload/v1598664286/Apps/wm99ynw01kw8fp8if4hq.gif" / hspace="5"> 
</p>

# Comenzando 🚀

Estas instrucciones te permitirán obtener una copia de la aplicacion para propósitos de desarrollo y pruebas.

## Pre-requisitos 📋
Que plugins necesitas para el funcionamiento de la aplicacion
- [http](https://pub.dev/packages/http#-installing-tab- "http")
- [flutter_swiper](https://pub.dev/packages/flutter_swiper "flutter_swiper")

También necesitas un api key de [The Movie Database](https://www.themoviedb.org/ "The Movie Database"). Una vez tengas generada la api key de TMDB, la agregas en **Peliculas/lib/src/providers/peliculas_provider.dart**

```
class PeliculasProvider {
  String _apikey   = 'aqui va la api key';
  String _url      = 'api.themoviedb.org';
  String _lenguage = 'es-ES';
  ```

# Construido con 🛠️
  - [Flutter](https://flutter.dev/ "flutter")
  - [Android Studio](https://developer.android.com/studio "Android Studio")
  - [The Movie Database](https://www.themoviedb.org/ "The Movie Database")
