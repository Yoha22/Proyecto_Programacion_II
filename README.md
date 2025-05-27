# <h1 align="center">GAME_VERSE_FINAL_PROJECT</h1>

<h1>Integrantes:</h1>

- <h4>Jesús Abiata Lopéz Llorente</h4>
- <h4>Juan Ángel Ramos Hernández</h4>
- <h4>Emely María Herrera Álvarez</h4>

## Manual de Usuario:

A continuación, se estará dando una breve explicación del funcionamiento del programa para los usuarios del mismo. Esto se logra apreciar de manera clara y sencilla en las siguientes presentaciones.

### Vista del Login (Inicio).

En la siguiente vista se podrá apreciar lo que sería el login (Sistema de autenticación de usuarios) se debe llenar los campos para iniciar la sesión, en caso de que no tenga un usuario registrado puede dirigirse hasta el apartado de registro, si preciona el texto "Singn in"que se encuentra ubicada el la parte inferior de la pantalla después del botón iniciar sesión ( Login ): ![image](https://github.com/Jesus03view/Proyecto_GAMEVERSE/assets/171627110/dbf0f130-0606-4c26-a1aa-7efbace57f0b)

      
![Vista del Login](https://github.com/Jesus03view/Proyecto_GAMEVERSE/assets/171627110/2f04fffd-02cf-44e7-b232-2b20afc6f2c8)

### Vista de Registro (Crea tu usuario).

En esta vista te encontrás con los campos correspondientes para la creacion de un nuevo usuario para el programa, debes asegurarte de que los datos estén ubicados correctamente y que el dato realmente corresponda a la información solicitada para que no ocurranigún error a la hora de crear el usuario.

![Vista de Registro](https://github.com/Jesus03view/Proyecto_GAMEVERSE/assets/171627110/0c11fa91-c545-4c59-a755-96ba409a8457)

### Vista Principal (Tienda)

Esta es la vista donde el usuario podrá ingresar despues de llenar sus datos de incio, tendrá una variedad de opciones bastante amplias esto relacionado con la compra de video juegos y convivencia con amigos, así como tambien opciones propias de cada usuario como personalizár su entorno con el modo oscuro y añadir a sus amigos jugadores ya registrados en el programa.

![Vista Principal](https://github.com/Jesus03view/Proyecto_GAMEVERSE/assets/171627110/4823dcdf-488e-4e62-8fd7-644f7156c246)

### Apartado de Amigos.

Aquí podrás mirar el estado de tus amigos buscar un amigo por su nombre y agregar nuevos amigos.

![image](https://github.com/Jesus03view/Proyecto_GAMEVERSE/assets/171627110/0d8b4b9a-60d2-4b6a-92b7-643abaaabd4b)

Acá está el espació para agregar nuevos amigos:

![image](https://github.com/Jesus03view/Proyecto_GAMEVERSE/assets/171627110/42345d08-c014-465e-a71a-7dbbdd76365e)


### Apartado de Perfil.

Acá en este apartado tendrás varias opciones, para el entorno visual, para la cuenta y una opción para cerrar la sesión.

![image](https://github.com/Jesus03view/Proyecto_GAMEVERSE/assets/171627110/8f19a407-3c62-415e-9183-9e41ba38576a)

Así se vé el entorno con el modo oscuro:

![image](https://github.com/Jesus03view/Proyecto_GAMEVERSE/assets/171627110/1f3a0df3-c25f-444c-985f-f7879332d5c3)

### Apartado para añadir juegos al carrito o comprarlos directamente.

En este apartado puedes mirar los requisitos funcionales sobre el juego que desea comprar y las diferentes ocpiones para añadir los juegos a la lista de deseos o al carrito.

![image](https://github.com/Jesus03view/Proyecto_GAMEVERSE/assets/171627110/66b632fc-6fe6-49f3-99ab-70085a40f5f8)

### Apartado de pagos.

Acá podrá realizar todas o finlaizar las compras de los juegos que desea adquirir, selecionando su banco preferido eh ingresando los datos correspondientes.

![image](https://github.com/Jesus03view/Proyecto_GAMEVERSE/assets/171627110/2c14a4ef-22ae-46fb-bb2b-38889f5a690f)

## Manual de Desarrollador:

Acontinuación tenemos la explicación o la demostración de de la solucion en el codigo fuente(Contenido para desarrolladores).

<table align="center">
  <tr>
          <h3 align="center">Tabla de Clases</t3>
  </tr>
  <tr>
          <th>Clases</th>
          <th>Descripción</th>
  </tr>
  <tr>
          <td>App.java</td>
          <td>Esta clase se encaraga de tomar el FXML de la pagina que se iniciará cuando se ejecute el programa carga la vista y lanza la aplicación</td>
  </tr>
  <tr>
          <td>ModeloDeDatos.java</td>
          <td>Esta clase implementa el patrón de diseño singleton y gestiona las instancias de los modelos de datos</td>
  </tr>
  <tr>
          <td>ListaDobleUsuario.java</td>
          <td>Esta clase implementa los metodos para almacenar y gestionar usuarios, guarda estos en archivos.txt para la persistencia de los datos</td>
  </tr>  
  <tr>
          <td>PilaStack_Juego.java</td>
          <td>Esta clase plementa tres pilas Stack que gestionan los diferentes archivos.txt y pilas de juegos en la aplicación</td>
  </tr>
  <tr>
          <td>Nodo_Usuario.java</td>
          <td>Esta clase implementa los atributos y metodos necesarios para cargar la información de usuario en la lista usuario</td>
  </tr>
  <tr>
          <td>Nodo_Juego.java</td>
          <td>Esta clase implementa los atributos y metodos necesarios para cargar la información de los juegos en las pilasStack</td>
  </tr>
  <tr>
          <td>Styles.css</td>
          <td>Esta hoja.css implemeta los estlos para la vista principal</td>
  </tr>
  
  <tr>
          <td>Styles_Dark.css</td>
          <td>Esta hoja.css implemeta los estlos para la vista principal</td>
  </tr>
          
</table>

<table align="center"> 
      <tr>
            <h3 align="center">Tabla de Vistas</h3>
      </tr>
      <tr>
            <th>Vista</th>
            <th>Controllador</th>
            <th>Cescripción</th>
      </tr>
      <tr>
            <td>View_GAME_VERSE.fxml</td>
            <td>Controller_View_GAME_VERSE.java</td>
            <td>El .fxml es la vista hecha con javaFx, el contrrolador se encarga de implementar he asignar las acciones de los botones y demás</td>
      </tr>
      <tr>
            <td>View_Login.fxml</td>
            <td>Controller_View_Login.java</td>
            <td>El .fxml es la vista hecha con javaFx, el contrrolador se encarga de implementar los eventos onClick </td>
      </tr>
      <tr>
            <td>View_Sign_in.fxml</td>
            <td>Controller_View_Sing_in.java</td>
            <td>El .fxml es la vista hecha con javaFx, el contrrolador se encarga de implementar los metodos de escritura y lectura de los datos de los usuarios</td>
      </tr>
</table>

## Caps y explicación de métodos

1. Metodos para verificar si el usuario se encuentra contenido en la ista, uno verifica por el correo y el otro por NickName del usuario ya que no sepueden repetir niguno de estos detos en dos cuentas

![image](https://github.com/Jesus03view/Proyecto_GAMEVERSE/assets/171627110/a80ae247-a80d-4325-b9df-4767a8ca1650)

2. Este metodo retorna un observableList, después de llanarlo con todos los usuarios que hay en la listaDobleUsuarios.

![image](https://github.com/Jesus03view/Proyecto_GAMEVERSE/assets/171627110/14c89345-209a-493d-89c2-12e379931059)

3. Este metodo verifiaca que el usuario nuevo no esté registrado, utilizando para esto los primeros métodos mencionados, luego sigue con la creación del usuario si este no existe.

![image](https://github.com/Jesus03view/Proyecto_GAMEVERSE/assets/171627110/0407785f-7337-4a7f-9008-3339cfbb3e7f)

4. Este método llama a el método getCrearUsuario y lo asigna en la lista dependiendo de si la cabecera de la lista es nula o no.

![image](https://github.com/Jesus03view/Proyecto_GAMEVERSE/assets/171627110/c7c4f02d-54db-45da-9dde-2f7cc9c5cd3e)

5. Este método escribe en el archivo.txt de los Usuarios todos los usuarios en la listaU.

![image](https://github.com/Jesus03view/Proyecto_GAMEVERSE/assets/171627110/e3d525ff-8b91-4b76-bd38-a964b6ba78cd)

6. Al contrario del metodo anterio este metodo lo que hace es leer los datos contenidos en el archivo.txt de los Usuarios y los añade a la lista con el metodo addUsuario()

![image](https://github.com/Jesus03view/Proyecto_GAMEVERSE/assets/171627110/8910ac43-222c-46c9-99ff-fe09bc93ab50)

7. Este metod se encarga de llanar la lista de usuarios con los datos obtenidos al leer el archivo.txt de los usuarios por lo cual no contiene niguna restricción

![image](https://github.com/Jesus03view/Proyecto_GAMEVERSE/assets/171627110/70503466-49ea-48d6-b6ce-d7380dcbf780)

8. Metodo para agregar juegos a la pila de Juegos en la biblioteca.

![image](https://github.com/Jesus03view/Proyecto_GAMEVERSE/assets/171627110/91eb54f6-89bf-4825-b1a5-2ac7d0687f13)

9. Este metodo obtiene por el NickName de un usuario todos los juegos de la pila de juegos en la biblioteca que correspondan a este jugador ya que estos se identifican por su dueño 
(Usuario).

![image](https://github.com/Jesus03view/Proyecto_GAMEVERSE/assets/171627110/e0d6a0d9-f567-464b-b287-c503f44f323f)

10. Este metodo es similar al anterio la unica diferencia es de que este metodo solo retorna un juego dado el NickName del Usuario.

![image](https://github.com/Jesus03view/Proyecto_GAMEVERSE/assets/171627110/eadbec4f-4f25-48f2-a32f-79b873886f96)

11. Este metodo elimina de la pila de juegos en la biblioteca a un juego dado el NickName del cliente.

![image](https://github.com/Jesus03view/Proyecto_GAMEVERSE/assets/171627110/2ce301ab-ff58-415b-ad78-d2d1fef296dd)

12. Este metodo es capaz de clonar la pila de los juegos para luego ser asignada o utilizada sin afectar a la pila principal.

![image](https://github.com/Jesus03view/Proyecto_GAMEVERSE/assets/171627110/9d621b78-9740-467d-9d63-f9a781a40338)

### Clase Singleton

Clase que gestiona las estructuras de datos, Esta clase crea una uníca instancía de las pilas y la listaUsuario para que se manejen los mismos datos durante la ejecución y evitar errores (Clase Singleton).

![image](https://github.com/Jesus03view/Proyecto_GAMEVERSE/assets/171627110/ea61c5b3-f256-46b7-b2ab-2bf7951cce92)

### Metodos de la vista del Login

1. Este metod gestiona los eventos de click en los botones para así tomar una decisión.

![image](https://github.com/Jesus03view/Proyecto_GAMEVERSE/assets/171627110/88d67de4-5c2e-4977-be8f-caa206cb1439)

2. Metodo para inciar sesión en el programa, este metodo valida toda la información sobr de los campos de texto.

![image](https://github.com/Jesus03view/Proyecto_GAMEVERSE/assets/171627110/a63fa275-ea2e-4711-b546-c063a1eaad0c)
![image](https://github.com/Jesus03view/Proyecto_GAMEVERSE/assets/171627110/131ee9ba-9adc-460f-a020-841ec343567c)
![image](https://github.com/Jesus03view/Proyecto_GAMEVERSE/assets/171627110/febaea37-fe0f-4613-aed0-76376fc42b2d)
![image](https://github.com/Jesus03view/Proyecto_GAMEVERSE/assets/171627110/ea1198e7-a2df-4adc-8840-d5280afdafa5)

## Prototipo

Puedes ver el prototipo del proyecto en el siguiente enlace: [Prototipo en Figma](https://www.figma.com/design/QcOLM4VnaQjJViVNxaTUtt/Prototype_GAME_VERSE?node-id=0-1&t=8u0L6xB1ygdAVBs2-1)

