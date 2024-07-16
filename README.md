<h1 align="center"> Foro Hub </h1>
Foro Hub es una aplicación Java desarrollada con Spring Boot que te permite cargar tópicos (dudas) o dar la respuesta a algún otro tópico. Es una REST API, donde se utiliza el programa Insomnia para poder simular la interacción del usuario en una página web, cargando así la información y después pasando esa información a una base de datos en MySQL.

Tecnologías:

- Java
- Spring Boot
- JPA
- Jackson
- MySQL
- FlyWay
- Spring Security
- JWT Token
- Swagger UI (documentación)
- Insomnia

Funcionalidades:

- Protección con Spring Security, requiriendo así de inicar sesión y obtener tu token para poder realizar las diferentes acciones.
- Agregar tópicos, usuarios o respuestas.
- Mostrar los tópicos con o sin respuestas, los usuarios agregados y también pudiendo buscarlos por su id para una búsqueda dirigida.
- Actualizar los tópicos con respuestas agregadas.
- Eliminar tópicos, usuarios o respuestas.

Objetivo:

Este proyecto fue desarrollado para poner en práctica los conocimientos adquiridos durante el curso de Spring Boot. Me permitió crear una aplicación funcional desde cero, enfrentando desafíos y aprendiendo nuevas técnicas.

Primero debemos de iniciar sesión para poder trabajar

![Screenshot del login](https://github.com/Gasca78/Foro-Hub/blob/main/login_correcto.png)

si algún dato es incorrecto, no iniciaras sesión ni obtendras tu token

![Screenshot del login con error](https://github.com/Gasca78/Foro-Hub/blob/main/login_incorrecto.png)

y en esta sección es donde se debe poner el token en cada acción

![Screenshot de donde poner el token](https://github.com/Gasca78/Foro-Hub/blob/main/poner_token.png)

Después pasamos a registrar un nuevo usuario

![Screenshot del usuario agregado](https://github.com/Gasca78/Foro-Hub/blob/main/agregar_usuario.png)

si no pusiste algún dato o el correo electrónico ya esta registrado, igual se te notificará

![Screenshot del usuario con email repetido](https://github.com/Gasca78/Foro-Hub/blob/main/agregar_usuario_repetido.png)

![Screenshot del usuario sin un dato](https://github.com/Gasca78/Foro-Hub/blob/main/agregar_usuario_falta_dato.png)

Proseguimos a mostrar la lista de usuarios y también una búsqueda dirigida a este último usuario agregado

![Screenshot de la lista de usuarios](https://github.com/Gasca78/Foro-Hub/blob/main/listar_usuarios.png)

![Screenshot del usuario recién agregado](https://github.com/Gasca78/Foro-Hub/blob/main/listar_usuario_id.png)

Eliminamos a este usuario

![Screenshot del usuario recién eliminado](https://github.com/Gasca78/Foro-Hub/blob/main/eliminar_usuario.png)

y podemos ver como es que ya no se encuentra su ID

![Screenshot del usuario recién eliminado](https://github.com/Gasca78/Foro-Hub/blob/main/listar_usuario_inexistente.png)

Ahora veamos cómo se agrega un nuevo tópico

![Screenshot del proceso para agregar un tópico](https://github.com/Gasca78/Foro-Hub/blob/main/agregar_topico.png)

aquí mostramos la lista de tópicos y el tópico solamente

![Screenshot de la lista de topicos](https://github.com/Gasca78/Foro-Hub/blob/main/listar_topicos.png)

![Screenshot de la lista de topicos](https://github.com/Gasca78/Foro-Hub/blob/main/listar_topico_id_sin_respuesta.png)

Así también, podemos hacer una o más respuestas para ese mismo tópico

![Screenshot de una respuesta](https://github.com/Gasca78/Foro-Hub/blob/main/agregar_respuesta.png)

![Screenshot de una segunda respuesta](https://github.com/Gasca78/Foro-Hub/blob/main/agregar_respuesta_2.png)

y sus respectivas actualizaciones al tópico

![Screenshot del tópico actualizado](https://github.com/Gasca78/Foro-Hub/blob/main/actualizar_topico.png)

![Screenshot del tópico actualizado](https://github.com/Gasca78/Foro-Hub/blob/main/actualizar_topico_2.png)

Claro que podemos eliminar las respuestas y también el tópico

![Screenshot de la respuesta eliminada](https://github.com/Gasca78/Foro-Hub/blob/main/eliminar_respuesta.png)

![Screenshot de la respuesta eliminada](https://github.com/Gasca78/Foro-Hub/blob/main/respuesta_eliminada_de_topico.png)

![Screenshot del tópico eliminado](https://github.com/Gasca78/Foro-Hub/blob/main/eliminar_topico.png)

Mostramos como ya no aparece el tópico, ni buscandolo directamente

![Screenshot de la lista de tópicos](https://github.com/Gasca78/Foro-Hub/blob/main/topico_eliminado_no_lista.png)

![Screenshot del tópico no encontrado](https://github.com/Gasca78/Foro-Hub/blob/main/topico_eliminado_no_encontrado.png)

Siendo así los diferentes procesos que se pueden realizar en esta aplicación, aprovecho para mostrar cómo se ve la documentación apoyado por Swagger

![Screenshot de la documentación](https://github.com/Gasca78/Foro-Hub/blob/main/documentacion.png)

![Screenshot de la documentación](https://github.com/Gasca78/Foro-Hub/blob/main/documentacion_2.png)

![Screenshot de la documentación](https://github.com/Gasca78/Foro-Hub/blob/main/documentacion_3.png)

Llegando así al final de la presentación de estre proyecto. ¡Gracias por leerme!

Agradecimientos:

Este proyecto no hubiera sido posible sin la ayuda de los profesores del curso de Spring Boot y la comunidad de Alura Latam. Gracias por su dedicación y por compartir sus conocimientos.
