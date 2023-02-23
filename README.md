# Websockets

Permiten una comunicacion bidireccional entre el cliente y el servidor, lo que a su vez genera un flujo continuo en el intercambio de datos entre ambas partes.

## Patrones de comunicacion

- Cliente al servidor
- Servidor al cliente
- Servidor a multiples clientes (Transmision / Broadcasting)

La comunicacion mediante websockets es persistente, lo que evita una sobrecarga en la generacion de encabezados resultante cuando se realizan multiples peticiones en el ciclo peticion-respuesta entre el cliente y el servidor.
El establecimiento de la comunicacion entre el cliente y el servidor durante la primera peticion se realiza a traves del protocolo HTTPS, posteriormente el resto de conexiones se realizan mediante el protocolo wss://.