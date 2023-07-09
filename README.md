# Sveltekit y Mantis bug tracker
Asi es, acabas de leer bien, como sera posible que conviva Sveltekit y MBT (Mantis Bug TRacker) al mismo tiempo, pues yo tampoco lo creia posible pero gracias a la documentacion que tiene Sveltekit se puede lograr siguiendo los pasos de la configaracion de SPA (Single-page apps).

# Como lo hice
Pues "sencillo", no es mas que seguir las instrcucciones que te da la pagina de [Mantis](https://www.mantisbt.org/index.php), entonces con la documentacion de [sveltekit](https://kit.svelte.dev/docs/single-page-apps) podemos hacer que estos dos vivan en el mismo lugar.

## Pasos a seguir
1. Ejecutar el comando que nos crea la _build_
2. En un servidor APACHE (ya sea en WAMP server, XAMP server o MAMP server) dentro de la carpeta _www_ podemos pegar dicha _build_
3. Fin :\)