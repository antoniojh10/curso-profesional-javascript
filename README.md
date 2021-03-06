# Proyecto del Curso Profesional Javascript

> De Platzi

El proyecto de crear un reproductor de video para el Curso Profesional de Javascript de [Platzi.com](http://platzi.com "Platzi.com"), como parte de la carrera de desarrollador React.

Además, aproveché para realizar el curso de Git y Github Profesional y practicar algunas cosas con los archivos de este proyecto.

# Contenido

## APIS Dom

Se explica y se pone en práctica muchas de las funcionalidades del API del DOM, tales como:

- **Fetch**: hacer peticiones (y abortarlas si éstas tardan mucho).
- **VisibilityChange**: detectar cuando la pestaña de la app es la pestaña actual del navegador o no (y poder hacer cosas a partir de esta condición, como pausar el video al cambiar de pestaña y darle play al volver a la pestaña).
- **IntersectionObserver**: poder detectar si un objeto específico del DOM se ve en la pantalla, así como el porcentaje de cuanto se ve y poder hacer operaciones a partir de ahí (como pausa el video cuando se vea menos del 25% de este).
- **ServiceWorker**: herramienta de algunos navegadores modernos que permite guardar peticiones en cache y utilizarlas sin conexión a partir de este cache.

## TypeScript

Es una versión tipada de JavaScript, se aprende sobre sus tipos básicos y las ventajas de hacer uso de este lenguaje, también se convierte el proyecto a este lenguaje como práctica.

- Te permite definir variables privadas o estáticas.
- Te permite especificar qué tipo de argumento debe ser enviado a una función, así como el tipo del output.

## Patrones de Diseño

Son una solución para un problema dentro de un contexto, esta situación debe ser recurrente, se debe evitar su aplicación a menudo ya que agrega un nivel de complejidad al código (que siempre se debe tratar de mantener lo más simple posible).

Dentro del curso de explican las categorías de los patrones de diseño (Creacionales, Estructurales y de Comportamiento) y se aplica uno de cada categoría (Singleton, Decorator y Observser, respectivamente).

# Conclusiones

Para terminar, durante el proyecto se crea un Plugin de Ads que aparecen cada 30 segundos de reproducción del video, y desaparecen 10 segundos despues.

También se dividió el proyecto entre el MediaPlayer y el website donde se implementa para poder publicar el MediaPlayer como un módulo de NPM e implementarlo en el website.

# Instalación del Módulo

```
npm install @antoniojh10/platzimediaplayer
```
