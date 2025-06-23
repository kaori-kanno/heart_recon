# heart_recon

Archivos con 11 líneas menos:

parte I modifica la parte donde se trata de llegar a la imagen reconstruída del corazón.
parte II es donde se trata de reconstruír la dirección de las fibras.
mod es la versión con simple_train, un modelo nn de Tabita.
mask0 es la prueba con una máscara vacía que deje las imágenes sin subsampleado, esto para probar qué tal se hacía la reconstrucción, pero realmente no es necesario el archivo, ya que los archivos con mask0 también son ejecutables desde parteI y mod. Se hizo en un archivo aparte porque jax no permite redefinir variables y me costó hacer cosas, pero ya no importa.
parte IyII es la parte donde se ejecutan los archivos que tuvieron mejor rendimiento en la parte I y se utilizan para construir la parte II y ver qué sales.

Los archivos parteII son la reconstrucción de las fibras a partir de los archivos parte I, donde se corresponden según el número de líneas.

Los archivos sigma tienen diferentes valores de sigma para la construcción del valor B que se usa en fordward_pass.
