1. ¿Qué propiedad del widget Scaffold se utiliza comúnmente para colocar una barra de navegación superior que contiene un título y botones de acción?

la propiedad appBar, ahí se pone un AppBar con el title y los botones en actions

2. ¿Cuál es el propósito principal de la propiedad elevation en el widget Card de Flutter?

sirve para darle sombra a la tarjeta, entre mas grande el numero mas sombra tiene y mas se resalta del fondo

3. ¿Qué widget utilizarías para recortar de forma limpia los bordes de una imagen rectangular (como Image.asset) de manera que adquiera esquinas redondeadas exactas?

el ClipRRect con borderRadius, asi la imagen queda con las esquinas redondeadas

4. Si deseas utilizar imágenes locales (Image.asset) en tu interfaz, ¿qué paso previo y obligatorio debes realizar en la estructura del proyecto para que la imagen se cargue sin errores?

hay que crear una carpeta para las imagenes (como assets/images), meter ahi las imagenes y declarar la ruta en el pubspec.yaml en la parte de assets, despues se hace flutter pub get

5. ¿Cómo puedes modificar de manera directa el tamaño y el color de un widget Icon?

con las propiedades size y color, por ejemplo Icon(Icons.favorite, size: 30, color: Colors.red)

6. ¿Cuál es la diferencia clave entre usar InkWell y GestureDetector para gestionar toques en Flutter?

el InkWell muestra el efecto visual cuando lo tocas (la ondita) y el GestureDetector solo detecta el toque pero no se ve ningun efecto

7. En un widget Row, ¿qué propiedad se encarga específicamente de alinear y distribuir los widgets hijos a lo largo de su eje principal (el eje horizontal)?

mainAxisAlignment, con opciones como center, spaceBetween o spaceEvenly

8. Si dentro de un Row añades textos muy largos que provocan un error de desbordamiento gráfico horizontal (RenderFlex overflow), ¿qué widget puedes utilizar para obligar al texto a ajustarse y ocupar únicamente el espacio libre restante?

el widget Expanded, hace que el texto use solo el espacio que sobra en el Row y se acomode

9. ¿Cuál es la forma más común y directa de enviar datos (por ejemplo, el objeto con la información detallada) al navegar hacia una nueva pantalla utilizando Navigator?

mandandolos por el constructor de la otra pantalla cuando usas Navigator.push, por ejemplo DetalleScreen(pelicula: pelicula)

10. ¿Cómo se puede obtener de forma asíncrona el valor o resultado que una segunda pantalla devuelve al cerrarse mediante una llamada a Navigator.pop(context, resultado)?

con async y await, porque el Navigator.push devuelve un Future, entonces se pone final resultado = await Navigator.push(...) y ahi llega lo que mando la otra pantalla con el pop

<img width="739" height="1600" alt="image" src="https://github.com/user-attachments/assets/89d3c19e-5ff2-4786-9f78-90936d53168c" />
 <img width="739" height="1600" alt="image" src="https://github.com/user-attachments/assets/fbdcba26-2426-471d-850c-c96a8db4059d" />
 <img width="739" height="1600" alt="image" src="https://github.com/user-attachments/assets/ffa92e74-b2ba-426b-ae55-ee13591f7d5b" />
<img width="739" height="1600" alt="image" src="https://github.com/user-attachments/assets/09e37759-eb10-465a-ad44-5aafd7316a5c" />
<img width="739" height="1600" alt="image" src="https://github.com/user-attachments/assets/719f07d1-619d-4422-b409-8cb085bbe3f5" />
<img width="739" height="1600" alt="image" src="https://github.com/user-attachments/assets/d44fa52e-8002-49c2-a569-ab4f10da8f92" />
<img width="739" height="1600" alt="image" src="https://github.com/user-attachments/assets/adffed40-c87c-41c3-977e-49cb76ff7d2a" />
<img width="739" height="1600" alt="image" src="https://github.com/user-attachments/assets/fd22137b-1c24-4293-adeb-1d3825ea0081" />
<img width="739" height="1600" alt="image" src="https://github.com/user-attachments/assets/a28f8f3e-944c-443d-b395-d2fa27f7e16c" />
<img width="739" height="1600" alt="image" src="https://github.com/user-attachments/assets/c8dcc93c-93c6-488d-9ae3-68cdf1119706" />
<img width="739" height="1600" alt="image" src="https://github.com/user-attachments/assets/56361441-0960-4cb1-8659-d7b2ca1a12a8" />





