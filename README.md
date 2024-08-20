## Cliente Gateway
El Gateway es el punto de comunicacion entre nuestro cliente y nuestro servicios.
Es el encargado de recibir las peticiones, enviarlas a los servicios correspondientes y devolver la respuesta al cliente.




## Nats
´´´´´
docker run -d --name nats-server -p 4222:4222 -p 8222:8222 nats

´´´´