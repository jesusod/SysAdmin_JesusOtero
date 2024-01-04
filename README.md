# sysadmin-JesusOtero
Practica modulo sysadmin

Haremos un vagrant up para arrancar las dos maquinas virtuales.

En la primera maquina virtual hemos montado Nginx, MariaDB, PHP y Filebeat.

Iremos al localhost:8081 y ahira nos aparecera ya nuestro Wordpress.

![prueba wordpress](https://github.com/jesusod/SysAdmin_JesusOtero/assets/99189407/95e66e69-d9b5-4fbd-82fd-8035833888e7)

Para la segunda maquina virtual, donde hemos montado Elasticsearch, Kibana y Logstash, tendremos que acceder con vagrant ssh y el nombre de la maquina virtual y entonces resuperar la contraseña de Elastic. 

Lo harremos con sudo cat passwords.txt y nos mostrará en ese archvico la contraseña que introduciremos para ElasticSearch.

Aqui vemos la respuesta del localhost:9200

![prueba elasticsearch](https://github.com/jesusod/SysAdmin_JesusOtero/assets/99189407/e57463ba-3718-4f17-b5e3-ce31832a0cd7)

Y aqui la respuesta accediendo a Elastic en el localhost:5601 para poder ver los logs en Kibana.

![prueba kibana](https://github.com/jesusod/SysAdmin_JesusOtero/assets/99189407/73ced3c0-087d-4b55-b1a1-0f9717261417)




