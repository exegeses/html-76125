# Notas clase 2

## Atributos
> Los atributos son modificadores de un elemento

<elemento atributo="valor">contenido</elemento>

> Podemos tener más de un atributo si fuese necesario

<elemento atributo="valor" atributo2="valor2">
    contenido
</elemento>

> Para insertar un vínculo en HTML 
> utilizamos el elemento "a"

<a href="url" target="_blank">
    Texto
</a>

> El atributo Target sutiliza para abrir un enlace en una nueva pestaña


> No todos los atributos aplican a todos los elementos
> Es nuestra tarea aprender cuáles son los atributos que van a funcionar en cada elemento



## Imágenes

> sitios para descargar imágenes


    íconos
        https://www.flaticon.com/
        https://www.iconfinder.com/
        https://www.svgrepo.com/


    fotografías
        https://unsplash.com/es
        https://www.pexels.com/es-es/

> Sitios para generar imágenes con IA

    https://davinci.ai/app
    https://www.blinkshot.io/
    https://app.leonardo.ai/




> Formatos de imagen para la web
> En la web tenemos varios formatos de imagen que podemos insertar estos son

> Imágenes pixelares = Tienen una cantidad de pixeles que definen la imagen

    png  (íconos, pueden ser transparentes)
    gif  (íconos, pueden ser transparentes)
    jpg  (fotografías, no pueden ser transparentes)
    jpeg  (fotografías, no pueden ser transparentes)

> Imágenes veectoriales = Están formadas mediante cálculos aritméticos y coordenadas que definen una imagen

    svg

> Imágenes contenedores. Pueden tener dentro Imágenes pixeles y también imágenes vectoriales

    webp  

### Accesibilidad
> Cuando insertamos una imagen podemos configurar el atributo
> "alt". Este atributo fue creado para poder contarles a ciertos visitantes con una discapacidad visual de qué se trata la imagen


### Combinando elementos

> ¿Cómo harías si quisieras insertar el logo de una empresa y que este sea un enlace a la página de esa empresa?
> Deberíamos anidar una imagen dentro de un enlace

<a href="url">
   <img src="ruta">
</a>

## Estructura de un documento html

> Cuando nosotros creamos una página HTML, siempre tenemos que tener cierta estructura en ese documento.
> En el caso en que no tengamos esta estructura base este documento va a estar mal formado
> Si un documento está mal formado tendrá una penalización a nivel posicionamiento (SEO && SEM)

    <!DOCTYPE html>
    <html>
        <head>
            Elementos no visuales
        </head>
        <body>
            Elementos visuales  
            Los elementos visuales son los que se van a ver dentro de la página
        </body>
    </html>