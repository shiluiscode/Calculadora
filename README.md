# Calculadora
Que hace document.querySelector(".display"); ?
busca y retorna el primer elemento del DOM que tenga la clase display. Esto te permite acceder a ese elemento para manipularlo o modificar sus propiedades mediante JavaScript.
Que hace const buttons = document.querySelectorAll("button"); ?
selecciona todos los elementos <button> presentes en el documento y los guarda en la variable buttons en forma de una NodeList. Esto te permite iterar sobre cada botón y aplicarles cambios o agregarles eventos.
Que hace buttonText = button.textContent; ?
asigna a la variable buttonText el contenido de texto que tiene el elemento button. Es decir, extrae el texto que se muestra dentro del botón, sin incluir etiquetas HTML.
Que hace y como funciona buttons.forEach((button) => { ...} ?
recorre cada elemento del arreglo (o NodeList) buttons. Por cada botón en la colección, ejecuta la función de flecha, permitiéndote acceder y manipular cada botón individualmente. Es una forma concisa de iterar sobre todos los botones y realizar operaciones en cada uno.
Que hace y como funciona button.addEventListener("click", () => { } )
añade un "escuchador" de eventos al elemento button. Esto significa que cada vez que el usuario haga clic en ese botón, se ejecutará la función definida (en este caso, una función flecha vacía). Es una forma de definir interactividad en el elemento, permitiendo que se realicen acciones en respuesta al evento "click".
