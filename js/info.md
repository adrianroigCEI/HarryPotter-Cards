// Seleccionamos el elemento HTML con id "gloton" y lo guardamos en una constante
// Seleccionamos el elemento HTML con id "points" y lo guardamos en una constante
// Seleccionamos el botón para subir de nivel y lo guardamos en una constante

// Ocultamos el botón de subir nivel al cargar la página

// Creamos una variable para llevar el conteo de puntos, empezando en 0
// Creamos una variable que indica cuántos puntos se necesitan para el siguiente nivel
// Creamos una variable para llevar el conteo del nivel, empezando en 1

// Creamos una función llamada "alimentar" que se ejecutará cuando se haga clic en el botón
    // Verificamos si los puntos son menores al objetivo del siguiente nivel
        // Incrementamos los puntos en 1 (sumamos 1 al valor actual)        
        // Actualizamos el texto visible en el elemento "points" con el nuevo valor de puntos        
        // Mantenemos oculto el botón de subir nivel mientras se alimenta
    // Si los puntos ya alcanzaron el objetivo del siguiente nivel, ejecutamos este código
        // Removemos la clase que muestra la cara triste        
        // Añadimos la clase que muestra la cara feliz        
        // Mostramos el botón para subir de nivel

// Creamos una función llamada "subirNivel" que se ejecutará cuando se haga clic en el botón
    // Incrementamos el nivel en 1 (sumamos 1 al valor actual)    
    // Actualizamos el texto visible en el elemento "points" con el valor actual de puntos    
    // Aumentamos el tamaño de la fuente del elemento "gloton" según los puntos acumulados    
    // Ocultamos nuevamente el botón de subir nivel    
    // Aumentamos en 10 el objetivo de puntos para el siguiente nivel
