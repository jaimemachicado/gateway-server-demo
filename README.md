# gateway-server-demo
 
Ejemplo de gateway con spring boot 3.

# Ejecución

Para probarlo se deben tener levantados los siguientes proyectos:
* [Servidor eureka](https://github.com/jaimemachicado/eureka-server-demo)
* [Cliente eureka](https://github.com/jaimemachicado/eureka-client-demo)

Se debe compilar y ejecutar el proyecto y se debería poder comprobar que en el 
[servidor eureka](http://localhost:8761/) se registra el gateway y que si ejecutamos un
GET al endpoint http://localhost:8090/api/v1/hello se recupera el mensaje "Hello from eureka client".