# Tienda-HTML-JS-CSS
Tarea sobre un una tienda web, hecha con HTML, css y JavaScript 

1. Explique cada una de las funciones definidas por el usuario en el código JavaScript presentado en el paso 2. 
Se declaro una matriz const llamada catalogo con los atributos de: id, nombre, imagen, precio y descripción.
Despues se generaron de forma dinamica tarjetas html donde se plasmaron los datos de la matriz catalogo. 

const catalogo = [
            { id: 1, Nombre: "Sushi de salmon", imagen: "../img/Producto1.jpg", precio: 120, descripcion: "Un roll vibrante con atún fresco, mango dulce y una salsa especial de la casa que realza los sabores tropicales." },
            { id: 2, Nombre: "Ramen Shoyu", imagen: "../img/Producto2.png", precio: 200, descripcion: "Ramen shoyu con caldo de soya, hongos shiitake, bambú y fideos artesanales, perfecto para reconfortar el alma en un día lluvioso." },
            { id: 3, Nombre: "Niguiri flameado", imagen: "../img/Producto3.png", precio: 140, descripcion: "Nigiri de anguila glaseada con salsa teriyaki casera y un toque de wasabi, una combinación intensa y llena de carácter." },
        ];


2. En el código js, ¿qué tipo de variable es "catalogo"? ¿Como se manipula?
Es una variable matriz de tipo const, esto quiere decir que una vez se le es asignado un valor en la declaración de la variable este no se puede reasignar.
  - push()
  - pop()
  - Cambiar un valor de la matriz
