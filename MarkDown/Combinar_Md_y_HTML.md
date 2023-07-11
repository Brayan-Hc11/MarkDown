# Combinación entre MarkDown y HTML
iniciamos mostrando un titulo de HTML en un archivo de MarkDown.

para hacer esto usaremos la etiqueta semantica (h1) que proviene de HTML y quiere decir titulo principal o titulo primario.

***
<h1> Codígo HTML </h1>

<p>
como podemos ver obtendremos el mismo resultado al usar un (h1) de HTML que al usar (#) de MarkDown
</p>

~~~
<h1> Codígo HTML </h1>

<p> Como podemos ver obtendremos el mismo resultado al usar un (h1) de HTML que al usar (#) de MarkDown. 
Al igual que usar la etiqueta semantica (p) para poder escribir parrafos en MarkDown.</p>

~~~

***
<h2>Insertar imagenes en MarkDown con HTML</h2>

Para poder insertar una imagen en MarkDown usaremos las etiquetas de utilidad de Md "![texto alternativo](url de la imagen y extención.)".

El texto alternarivo nos permite saber de que trata el contenido de la imagen al pasar el cursos por encima del icono de imagen si esta no llega a cargar o a ser visualizada.

Estas etiquetas no nos permiten manipular las dimenciones de la imagen, por ende tendremos que apoyarnos en las etiquetas de HTML.

***imagen con las etiqeutas de utilidad de Md***

![Imagen random](image-1.png)

***imagen con las etiqeutas de utilidad de HTML***

<img src="image-2.png" width="150px"  height="80px" />

*nota:* HTML y Md no es recomendable mezclarlos a no ser de que sea necesario para mostrar el contenido multimedia tanto imagenes como videos

