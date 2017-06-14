# Actividad 024 - Bootstrap y SASS

- Para poder realizar este actividad debes haber realizado los cursos previos junto con los videos online correspondientes a la experiencia 12.

## Ejercicio 1:

- Descargar el SASS de Bootstrap.

- Desde el archivo descargado, dentro de *assets/stylesheets* extraer los archivos *_bootstrap.scss*,  *_bootstrap-sprockets.scss* y la carpeta *bootstrap* que contiene los componentes del framework.

- Crear un nuevo proyecto en Rails 5.1

- Inicializar Git.

- Crear un **controller pages** con las vistas *home* y *about*.

- Integrar los archivos de *Bootstrap* en la carpeta *vendor* del proyecto.

- Dentro del proyecto de rails, cambiar el formato de *application.css* para que soporte SASS. Luego cargar *Bootstrap* utilizando **@import**.

- Agregar los archivos cargados en *vendor* al **asset path**.

- En el archivo *_variables.scss* de Bootstrap, modificar la grilla para que se implemente con **10 columnas**.

- Comprobar que los pasos anteriores se llevaron a cabo de manera correcta y que la grilla está implementada con 10 columnas.

- Hacer un commit.

- Crear un *scaffold* de **Product** con los campos **name** y **price.** ( => migración )

- Añadir un **navbar fixed** al layout.

    - El navbar debe contener los links a las vistas de *home*, *about* y al *index* de products.

- Crear un **nuevo layout**.

- Añadir un **navbar fixed** al nuevo layout (con un color distinto al anterior)

    - Este navbar debe contener un link al *home*.

- Implementar el primer layout en las vistas correspondientes al controller *pages*.

- Implementar el nuevo layout en las vistas correspondientes al controller *products*.

- **En ambos layouts el *yield* debe estar dentro de un div con clase *container***.

- Implementar una clase bajo un **namespace** que permita asignar un **background-color** distinto al *container* de cada landing. 

- En las vistas *home*, *about* e *index de products*, implementar contenido que utilice la grilla de 10 columnas creada al inicio.

- Hacer commit, y push a tu repositorio de GitHub.
