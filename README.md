# Desafío 5 Back End

Voy a ir punto por punto mostrando lo solicitado:

### 1) Vistas y rutas para procesar registro y login.




#### Capturas desde el Navegador

a - SignUp para registrarse. Si va a Login y el mail no se encuentra en la base de datos se redirige a esta vista que es SignUp para registrarse:
![App Screenshot](https://www.entropiadigital.com.ar/IMG/Captura%20de%20pantalla%202024-03-01%20232616.png)

b - Login. Si la contraseña no es válida da aviso. Si ya está logueado el usuario lo redirige directamente a /productos:

![App Screenshot](https://www.entropiadigital.com.ar/IMG/Captura%20de%20pantalla%202024-03-01%20232515.png)


### 2) Una vez realizado el login redirigirse a productos + mensaje de bienvenida.

a - En la vista de productos:

![App Screenshot](https://www.entropiadigital.com.ar/IMG/Captura%20de%20pantalla%202024-03-01%20232717.png)

b - En la base de datos puede verse que hay una sesión activa:

![App Screenshot](https://www.entropiadigital.com.ar/IMG/Captura%20de%20pantalla%202024-03-01%20232738.png)

### 3) Asignar roles de administrador o usuarios.

a - en la consola puede verse que si es Admin hay un campo que dice Admin: true, el resto dice Admin: false:

![App Screenshot](https://www.entropiadigital.com.ar/IMG/Captura%20de%20pantalla%202024-03-01%20232820.png)

### 4) Boton de Logout para finalizar sesión.

a - al apretar el botón logout ya visto en la vista de /productos, la sesión finaliza y ya no la vemos en la base de datos en la colección sessions:

![App Screenshot](https://www.entropiadigital.com.ar/IMG/Captura%20de%20pantalla%202024-03-01%20232852.png)

b - Sin embargo el usuario queda guardado en la colección users:

![App Screenshot](https://www.entropiadigital.com.ar/IMG/Captura%20de%20pantalla%202024-03-01%20232802.png)





