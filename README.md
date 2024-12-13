<h1 align='center'> <img src = 'https://github.com/user-attachments/assets/d2d2a0ee-0b90-41d3-8066-63eac5c6a28f' height='35px'>
 Consumo de API's con Flutter <img src = 'https://github.com/user-attachments/assets/cd296f57-187a-44a9-a84f-05e873f23aba' height='35px'>
</h1>

![492shots_so](https://github.com/user-attachments/assets/1be0b5f3-d7aa-4ed5-8794-a2a43ba85121)



> [!IMPORTANT]
> **Planteamiento del problema**
>
> Este repositorio contiene una aplicación desarrollada en Flutter que consume la API de [PokeAPI](https://pokeapi.co/api/v2/pokemon/) y otra API de [Perritos aleatoriamente](https://random.dog/woof.json). El objetivo principal es generar una aplicación que permita buscar y mostrar información de Pokémons, incluyendo su imagen y sus características. Por otro lado mostrar de forma sencilla imagenes aleatroias de perritos.

🚮 **Descripción para la API de pokemos**
> 🧩<strong>La aplicación se conecta al endpoint:</strong>
>  https://pokeapi.co/api/v2/pokemon?limit=100000&offset=0
> 
>  🧩<strong>permite buscar Pokémons específicos mediante el uso del endpoint:</strong>
>   https://pokeapi.co/api/v2/pokemon/{nombre-del-pokemon}
>
>  🧩<strong>Por ejemplo, al buscar el Pokémon "ditto", el endpoint sería:</strong>
>   https://pokeapi.co/api/v2/pokemon/ditto

🚮 **Descripción de perritos**
> 🧩<strong>La aplicación se conecta al endpoint:</strong>
>  https://random.dog/woof.json
> 
>  🧩<strong>Esta api es sencilla, no es necesario enviar datos ni buscar en endpoints específicos, solo lo consumimos para recibir nuestras imágenes</strong>

🚮 **Características de la Aplicación**
>  🧩<strong>Busqueda de Pokemon:</strong>
>   Ingresar el nombre de un Pokémon para obtener información detallada.
>
>  🧩<strong>Visualización de Detalles:</strong>
>   Mostrar nombre, habilidades, estadísticas, tipos y una imagen del Pokémon.
>
> 🧩<strong>Visualización de perritos:</strong>
>  Mostrar un adorable perrito aleatorio
> 
>  🧩<strong>Interfaz Dinámica:</strong>
>   Diseño interactivo y adaptativo usando Flutter.

🚮 **Creacion de la Aplicación Flutter**
>   clonar el respositorio y navegar al directorio
> 
>   instalar las dependencias con el comando "flutter pun get"
> 
>   ejecutar la aplicacion con "fultter run"
