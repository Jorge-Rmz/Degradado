# Degradado

## Cubo Degradado (Clase CubeDegradado)

#### En las siguientes líneas de código se puede observar la importación de las clases utilizadas. Y la clase main el cual se define el tamaño de la pantalla y otros parámetros para poder dibujar la figura.

![1](https://user-images.githubusercontent.com/71052252/143891497-e905e8ff-480d-4c70-8b27-ffe16b10bc4b.png)

#### En la siguiente imagen vemos la línea de código de lo que hará el programa cuando finalice, con las líneas animator.stop se detendrá la animación y el siguiente código se cerrará la ventana. Y las siguientes líneas nos sirve para centrar la ventana y hacerla visible.

![fIGURA 2](https://user-images.githubusercontent.com/71052252/143891499-ccc3ab13-7dc1-437b-b348-e1762abc58f9.png)

#### En el método init se inicializa la variable gl que nos servirá para dibujar las figuras, y también asignamos las coordenadas en donde se podrá dibujar las figuras.
![fIGURA 3](https://user-images.githubusercontent.com/71052252/143891458-000e3723-efcd-4af1-87b0-afcfcf909816.png)

#### En la clase reshape se tiene el código para determinar el tamaño final de la ventana en donde se mostrara la figura, y la matriz de proyección.
![fIGURA 4](https://user-images.githubusercontent.com/71052252/143891462-7d19d6e3-2507-4d32-b634-0ac0dd49fa2d.png)

#### En la función display es donde está el código, para dibujar la figura en 3D. Lo dibujamos con 6 cuadrados, cada cuadrado será una cara del cubo. Primero dibujaremos el cuadrado que estará en la parte de abajo. Primero se pone el color al lado que se dibujara, después vemos las coordenadas para dibujar cada uno de los vértices, y así seguimos con la siguiente cara.

![fIGURA 5](https://user-images.githubusercontent.com/71052252/143891463-6ba99406-b572-4512-890d-37087c5e5a63.png)

#### Después vemos que qué sucede lo mismo con las siguientes caras, ahora veremos la parte del lado primero pondremos el color de la cara de dibujar, primero se dibujan las primeros vértices y después se pone el color a la segunda parte de cuadrado y así se puede ver el degradado de la figura en 3d. 
![fIGURA 6](https://user-images.githubusercontent.com/71052252/143891464-fcfe1e40-8e4b-4c33-af7e-c5a364fbbb08.png)

# Resultados

#### Al ejecutar el programa se puede observar la figura en 3D con sus diferentes caras degradados.
![fIGURA 7](https://user-images.githubusercontent.com/71052252/143891467-1abbe4f1-7e6f-443c-a2c7-effad978341e.png)

