# heart_recon

parte I modifica la parte donde se trata de llegar a la imagen reconstruída del corazón.
parte II es donde se trata de reconstruír la dirección de las fibras.
mod es la versión con simple_train, un modelo nn de Tabita.
mask0 es la prueba con una máscara vacía que deje las imágenes sin subsampleado, esto para probar qué tal se hacía la reconstrucción. Se hizo en un archivo aparte porque jax no permite redefinir variables.
