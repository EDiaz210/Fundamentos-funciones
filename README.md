Taller: Fundamentos y Funciones en JavaScript
-

Este taller introduce los fundamentos básicos del lenguaje JavaScript a través de la creación y manipulación de variables, objetos, strings, números y estructuras de control. El objetivo es familiarizarse con la sintaxis y las funcionalidades esenciales del lenguaje.

Contenidos del Taller
-
📦 Variables
-
Se definen diferentes variables relacionadas con un producto tecnológico (un teléfono móvil) para ejemplificar los distintos tipos de datos primitivos:

let tipo_producto = "Teléfono"
let nombre_producto = "Galaxy S25"
let marca = "SAMSUNG"
let año_fabrica = 2025
let gb_disponibles = 256
let precio = 779.99

🧱 Objeto
-
Se agrupan las variables dentro de un objeto detalle_producto para demostrar cómo se organiza información relacionada en estructuras más complejas:

let detalle_producto = {
  tipo_producto: "Teléfono",
  nombre_producto: "Galaxy S25",
  marca: "SAMSUNG",
  año_fabrica: 2025,
  gb_disponibles: 256,
  precio: 779.99
}

🔤 Strings
-
Se utilizan diferentes métodos de manipulación de cadenas como length, toUpperCase(), toLowerCase(), charAt() e includes() para analizar el nombre del producto.

console.log(`Producto: ${tipo_producto} - Modelo: ${nombre_producto}`)

🧾 Template Strings
-
Uso de template literals para generar salidas dinámicas de texto:

console.log(`Producto: ${tipo_producto} - Modelo: ${nombre_producto}`)

🔢 Número
-

Se realizan operaciones numéricas como aumento de almacenamiento y cálculo de descuento:
console.log(gb_disponibles + 128)
console.log(precio - (precio * 0.1))

⚖️ Condicionales 
-
Uso de estructuras de control if y el operador ternario para clasificar el producto según su precio:

if (precio > 500) {
  console.log("El producto es de gama alta")
} else {
  console.log("El producto es de gama media o baja")
}

const categoria_precio = precio > 500 ? "Alta gama" : "Media o baja"

💻 Requisitos
-
-Editor de código (por ejemplo, Visual Studio Code)

Navegador web moderno (para correr el código en consola)

Conocimientos básicos de JavaScript



