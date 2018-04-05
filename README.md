# angularFirebaseLogin

sin version -> se puede acceder a la pagina de formulario haciendo o no login con google.

v1 -> hace login solo con google cuando se va a formulario (y es necesario). 

v2 -> hace login con google y twitter. Tiene pantalla de login y casi hecho al completo lo de las rutas details.
        Falta:
            -Arreglar las rutas a details. (Tras hacerlo con id, aplicarlo a categorias).
            -Hacer el login con el correo solo.
            -Hacer que desaparezca el boton logout si no estas en sesion.
            -Meter la api de google.
            -Arreglar enlace a slack.(Estaria guay volver a meter chatbot).
            -Poner precios en la base de datos.
            -Modificar las reglas en la base de datos para poder escribir en contactos sin ser usuario registrado.
            -Ponerlo bonito.
            
v2.1 ->reconoce el enrutamiento detail por id, pero da fallo en el get. Se hace visible la necesidad de poner el campo id al insertar rutas y que este id sea generado de forma automatica (o encontrar la forma de llamar al id de firebase).    

v2.2. ->pequeños arreglos en el login por correo y email (logea pero no lleva a formulario). Logout desaparecido.

v2.3. ->arreglado login por correo y email. Intentando isLogin y detail por key
