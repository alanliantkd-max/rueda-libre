
# Bitácora de desarrollo de software

## Información del proyecto
- Proyecto: Mi primer proyecto
- Desarrollador: Mi nombre
- Fecha de inicio: 20/10/2026

## Día 1 - 20/10/2026

### Objetivo
Aprender los fundamentos de HTML.

### Actividades realizadas
- Investigué la estructura básica de HTML.
- Creé mi primer archivo index.html.
- Aprendí a utilizar las etiquetas de HTML

### Problemas encontrados
Tuve dificultades para crear un enlace correctamente.
No fui capaz de conectar correctamente el editor de texto con github.
### Soluciones
Revisé la sintaxis del atributo href.
Pedir el favor al TL
### Aprendizajes
Aprendí a crear con HTML.

### Próximos pasos
Realizas el segundo proyecto poniendo en practica los conceptos aprendidos.

## Dia 2 - 03/11/2026

### Objetivo
compare la peleta de colores del cliente 

### Actividades realizadas
mezcle el blanco con el verde ruta y me dio 5.31(botones y enlaces)
mezcle el el blanco sobre naranja pedal y me dio 2.21
Mezcle el azul noche con naranja pedal y me dio 7.2 (titulos y encabezados)
Mezcle azul noche con crema y me dio 14.8 (destacados y botones segundarios)
Mezcle gris asfalto con crema y me dio 5.5(texto segundario)
mezcle verde ruta con crema y me dio 4.9(fondo general)
Mezcle naranja pedal con crema y me dio 2.05
Mezcle blanco con azul noche y me dio 15.9(texto segundario) 
### Aprendizaje
comenzar a utilizar el CSS

### Proximo paso 
profundizar en lo aprnedido de CSS
   

## dia 3 - 04/11/2026

### Objetivo
utilizar lo aprendido de CSS y profundizar en que es una fuente y como se crean los vinculos en CSS

### Actividades realizadas
Crear vinculos, con propiedades en CSS

encontre que en la pagina index.html en la etiqueta h2encuentranosh2 esta heredado el espacio entre letra y letra, tambine encontre que no heredo 

### dia 4 9/11/2026

### objetivo
aprender a utilizar e instalar tailwind CSS (CLI) 

### Actividades realizadas 
 * Al revisar el archivo output.css generado por la CLI, noté que las clases que utilicé en mi HTML (como bg-blue-600) sí aparecen compiladas. En cambio, al buscar una clase que no utilicé en mi código (como bg-pink-500), esta no se genera en el archivo CSS final. Esto ocurre porque la CLI de Tailwind escanea los archivos del proyecto y aplica un proceso de limpieza (purge), eliminando todo el código que no se está usando para que la página cargue mucho más rápido."
 -## Reglas del Kit de Componentes

* **Radios de borde:** Se decidió utilizar esquinas redondeadas consistentes (`rounded-lg` y `rounded-2xl`) en todos los componentes —botones, cards, alertas y campos de formulario— para mantener una estética visual uniforme.
* **Espaciado y jerarquía:** Se aplicaron clases de separación estándar (como `gap-4`, `gap-6` y padding uniforme) para asegurar una distancia limpia y ordenada entre los textos, inputs y botones.
* **Paleta de colores y estados:** Se mantuvo una coherencia cromática utilizando tonos azules para los elementos interactivos principales, y alertas con fondos suaves acompañadas de un borde lateral distintivo para indicar información, éxito y advertencia.
* **Accesibilidad:** Todos los elementos interactivos (botones y campos de formulario) comparten el mismo comportamiento de `hover` suave y un anillo de foco visible (`focus:ring-4`) para garantizar una correcta navegación por teclado.


### Aprendizaje
aprendi a hacer estas acciones que estan realizadas arriba 

### Proximo paso
realizar los entregables de la semana tres del dia dos



### Dia 5 - 10/11/2026

### objetivo
realizar otro prototipo.html (crear una nueva pagina) con todas las especificaciones  

### Actividades realizdas 
Cambiar el prototipo.html con estos requisitos
Encabezado (<header>) con logo, enlaces con anclas (#rutas, #como-funciona, #inscripcion) y botón.  
Sección Principal / Hero (<section>) con el título de la campaña.  
Sección de Rutas (<section id="rutas">) con tus 3 cards organizadas en una cuadrícula de 3 columnas (grid grid-cols-1 md:grid-cols-3).   
Sección ¿Cómo funciona? (<section id="como-funciona">) con los 4 pasos en columnas.   Franja de inscripción (<section id="inscripcion">).   Pie de página (<footer>).  

Justificación de Grid vs Flex en la Landing
* **¿Por qué se usó `grid` para las rutas y los pasos?** Se eligió la utilidad `grid` (específicamente `grid-cols-1 md:grid-cols-3` y `lg:grid-cols-4`) porque permite organizar los elementos de manera uniforme tanto en filas como en columnas de forma automática y limpia, adaptándose perfectamente a pantallas grandes y dispositivos móviles sin necesidad de escribir código CSS adicional.
* **¿Cuándo se usó `flex`?** Se utilizó `flex` para elementos en una sola dirección, como la barra de navegación del encabezado, el alineado de los botones y la distribución del pie de página.

### Proximo paso
Realizar el entregable dos de la semana tres dia dos