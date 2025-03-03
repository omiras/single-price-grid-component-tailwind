# Ejercicio TailWind

Completa este ejercicio de clase ahora usando la biblioteca CSS Tailwind

## Iteración 1

- Abre el index.html con Live Server 
- Si quieres puedes instalar [este plugin](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss) para que te aparezcan las clases CSS disponibles
- Descomenta el tag _link_ para cargar Tailwind
- Puedes usar los colores del diseño o _jugar_ con los colores que trae Tailwind
- ¿Cómo establezco que el font-family es Karla? Puedes hacerlo con CSS normal o bien usando Tailwind - [ayuda](https://tailwindcss.com/docs/font-family). También se puede añadir en la [directiva @theme](https://tailwindcss.com/docs/adding-custom-styles#customizing-your-theme)
- Implementa primero la versión móvil y no te preocupes por las _media queries_

## Iteración 2

Aplica las media queries necesarias para pasar de móvil a escritorio el componente. - [documentación](https://tailwindcss.com/docs/responsive-design)  

## Iteración BONUS

Usando Tailwind CSS, haz que al pasar el ratón por encima del botón se inviertan sus colores.

## Resumen clases CSS de ejercicios anteriores


```markdown
| **Clase CSS**                          | **Descripción**                                                                                         |
|----------------------------------------|---------------------------------------------------------------------------------------------------------|
| `bg-gray-950`                          | Establece un color de fondo gris muy oscuro (casi negro).                                                |
| `font-[Inter]`                         | Aplica la fuente "Inter".                                                                                 |
| `h-screen`                             | Establece la altura del elemento al 100% de la altura de la pantalla.                                     |
| `grid`                                 | Establece el contenedor como un grid, lo que permite usar el sistema de cuadrícula de CSS.               |
| `place-items-center`                   | Centra los elementos hijos dentro del grid, tanto horizontal como verticalmente.                         |
| `max-w-sm`                             | Establece un ancho máximo pequeño para el contenedor, lo que limita el tamaño del elemento a 24rem.        |
| `flex`                                 | Aplica un modelo de diseño flexible (Flexbox) al contenedor.                                           |
| `flex-col`                             | Organiza los elementos hijos en una columna (en lugar de fila).                                          |
| `text-white`                           | Establece el color del texto a blanco.                                                                  |
| `bg-gray-900`                          | Establece el color de fondo a un gris oscuro (cerca de negro).                                           |
| `text-center`                          | Centra el texto dentro del contenedor.                                                                  |
| `p-4`                                  | Aplica un padding (espaciado interior) de 1rem (16px) a todos los lados del contenedor.                 |
| `m-4`                                  | Aplica un margin (espaciado exterior) de 1rem (16px) a todos los lados del contenedor.                 |
| `flex-col`                             | Organiza los elementos en columna dentro del contenedor.                                                |
| `items-center`                         | Centra los elementos hijos en el eje transversal dentro de un contenedor flex.                           |
| `my-6`                                 | Aplica un margin vertical (arriba y abajo) de 1.5rem (24px).                                            |
| `size-20`                              | Esta clase no existe en Tailwind por defecto. Puede ser un error o una clase personalizada.              |
| `rounded-4xl`                           | Aplica bordes redondeados grandes (1.5rem, 24px) a un elemento.                                          |
| `text-3xl`                             | Establece el tamaño del texto a 1.875rem (30px).                                                        |
| `my-1`                                 | Aplica un margin vertical (arriba y abajo) de 0.25rem (4px).                                           |
| `text-lime-300`                        | Establece el color del texto a un verde lima claro (color en la paleta de Tailwind).                     |
| `text-gray-300`                        | Establece el color del texto a gris claro.                                                              |
| `my-4`                                 | Aplica un margin vertical (arriba y abajo) de 1rem (16px).                                              |
| `space-y-4`                            | Aplica un espacio vertical de 1rem (16px) entre los elementos hijos.                                    |
| `bg-gray-800`                          | Establece el color de fondo a un gris oscuro.                                                           |
| `py-2`                                 | Aplica un padding vertical (arriba y abajo) de 0.5rem (8px).                                            |
| `md:p-2`                               | En pantallas medianas y más grandes, aplica un padding de 0.5rem (8px) a todos los lados.               |
| `rounded-md`                           | Aplica bordes redondeados medianos (0.375rem, 6px) al elemento.                                          |

### Media Queries (Pantallas medianas y más grandes):

| **Clase CSS**                          | **Descripción**                                                                                         |
|----------------------------------------|---------------------------------------------------------------------------------------------------------|
| `md:flex-row`                          | En pantallas medianas (≥768px), organiza los elementos hijos en una fila (por defecto es columna).       |
| `md:max-w-full`                        | En pantallas medianas y más grandes, establece un ancho máximo del 100% del contenedor.                |
| `md:gap-4`                             | En pantallas medianas y más grandes, aplica un gap de 1rem (16px) entre los elementos hijos.            |
| `md:p-8`                               | En pantallas medianas y más grandes, aplica un padding de 2rem (32px) a todos los lados del contenedor.  |
| `md:items-center`                      | En pantallas medianas y más grandes, centra los elementos hijos en el eje transversal del flex.         |
| `md:p-2`                               | En pantallas medianas y más grandes, aplica un padding de 0.5rem (8px) a todos los lados.               |
```

Puedes copiar y pegar este código en tu archivo Markdown. Si necesitas algo más, ¡avísame!