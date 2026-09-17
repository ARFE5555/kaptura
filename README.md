# Kaptura

Catálogo web de Kaptura — accesorios Apple en Caracas.

**Ver el sitio:** https://arfe5555.github.io/kaptura/

## Qué hay aquí

Un solo archivo, index.html. Todo va dentro: los estilos, el código y las fotos
de los productos (incrustadas en base64). No hay dependencias, no hay build, no
hay carpeta de imágenes. Se abre haciendo doble clic.

Lo único que se carga de afuera son las dos tipografías, desde Google Fonts:
Space Grotesk para la marca y los titulares, DM Sans para los textos.

## Cómo cambiar el catálogo

Abre index.html y baja hasta el bloque que dice **CAMBIA SOLO ESTO**, cerca del
final. Ahí están las dos únicas cosas que hay que tocar.

### TIENDA — los datos del negocio

| Campo | Qué es |
|---|---|
| whatsapp | Número con código de país, sin + ni espacios |
| instagram | El usuario, sin la arroba |
| direccion | Dirección de la oficina para retiros |
| horario | Horario de atención |
| zonas | Zonas que cubre el delivery |
| costoEnvio | Costo del delivery dentro de Caracas |
| mrwFlete | Quién paga el flete de los envíos nacionales |
| mrwTiempo | Tiempo estimado de entrega por MRW |
| moneda | Prefijo del precio |

### PRODUCTOS — el catálogo

Cada producto es un objeto en la lista. Para agregar uno nuevo, copia uno que ya
esté y cambia los valores: nombre, precio (null muestra "Consultar precio"),
foto (una URL o vacío para el marco con la K), pitch, specs (pares de etiqueta y
valor) y variante (una nota opcional al pie de la ficha).

La página se rearma sola con lo que haya en esa lista: las fichas, los botones de
WhatsApp con el mensaje ya escrito y el aviso de lo que falte.

Mientras algún dato siga en blanco o entre corchetes, aparece una franja gris
arriba diciendo qué falta. Desaparece sola al completarlo. Esa franja es para ti:
si la ves publicada, es que algo quedó sin llenar.

## Publicar los cambios

GitHub Pages republica solo cada vez que guardas un cambio en main. Tarda un par
de minutos.

## Marca

| | |
|---|---|
| Negro | #0B0B0D |
| Grafito | #1D1D1F |
| Gris | #6E6E73 |
| Gris claro | #A1A1A6 |
| Plata | #D2D2D7 |
| Blanco | #F5F5F7 |

Tipografías: Space Grotesk y DM Sans, las dos gratis en Google Fonts.

## Aviso

Kaptura es una tienda independiente de accesorios, sin afiliación con Apple Inc.
AirPods y Apple son marcas registradas de Apple Inc. Las características técnicas
publicadas vienen de las fichas oficiales de Apple y pueden cambiar sin aviso.
# Kaptura
