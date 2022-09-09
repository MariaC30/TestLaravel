## Test Laravel 

CON EL COMANDO PHP ARTISAN TEST SE EJECUTAN LAS PRUEBAS QUE SE ENCUENTRAN EN LA CARPETA FEATURE Y UNIT EN LA CARPETA CORRECTA, ES DECIR, EN LA CARPETA DEL PROYECTO. 
![](https://github.com/MariaC30/TestLaravel/blob/main/Imagenes/Captura.PNG?raw=true)





AúN No Se Han Realizado Cambios En El Proyecto Y Por Esta RazóN Los Dos Test Nos Salen Pass
![](https://github.com/MariaC30/TestLaravel/blob/main/Imagenes/Captura.PNG%201.PNG?raw=true)

Posteriormente, Con El Comando Php Artisan Make:Test  Usertest Se Crea Un Nuevo Test En La Carpeta Feature Que Se Llama Usertest
![](https://github.com/MariaC30/TestLaravel/blob/main/Imagenes/Captura.PNG3.PNG?raw=true)






Se Vuelven Ejecutar Las Pruebas De Los Test Para Verificar Que El Nuevo Test Creado Funciona Correctamente
![](https://github.com/MariaC30/TestLaravel/blob/main/Imagenes/Captura.PNG4.PNG?raw=true)


Ahora Creamos Test Unitarios Para El Usertest 
![](https://github.com/MariaC30/TestLaravel/blob/main/Imagenes/Captura.PNG5.PNG?raw=true)


Se Ejecutan Las Pruebas De Nuevo Para Ver Que El Test Unitario Salió En Pass

![](https://github.com/MariaC30/TestLaravel/blob/main/Imagenes/Captura.PNG6.PNG?raw=true)



Con El Comando Composer Require/Ui Se Instala La LibreríA De Laravel Necesaria Para Crear User Interfaces
![](https://github.com/MariaC30/TestLaravel/blob/main/Imagenes/Captura.PNG7.PNG?raw=true)


Con El Comando Php Artisan Ui React  - - Auth Se Crea El MóDulo De AutenticacióN Y Registro De Usuarios Que Viene Por Defecto Con Laravel
![](https://github.com/MariaC30/TestLaravel/blob/main/Imagenes/Captura.PNG8.PNG?raw=true)


Con El Comando Npm Install Y El Comando Npm Run Dev Se Inicia El Servidor De Frontend
![](https://github.com/MariaC30/TestLaravel/blob/main/Imagenes/Captura.PNG9.PNG?raw=true)



Se Crea La Base De Datos Necesaria Para Este Proyecto, Se Crea Por Phpmyadmin Con El Nombre Testlaravel
![](https://github.com/MariaC30/TestLaravel/blob/main/Imagenes/Captura.PNG10.PNG?raw=true)



En El Archivo .Env Se Verifica Que La Base De Datos Tiene El Mismo Nombre Que La Que Se Acaba De Crear. 
![](https://github.com/MariaC30/TestLaravel/blob/main/Imagenes/Captura.PNG11.PNG?raw=true)

 Se Ejecuta La MigracióN De La Base De Datos Con El Comando Php Artisan Migrate El Cual Crea Las Tablas
 ![](https://github.com/MariaC30/TestLaravel/blob/main/Imagenes/Captura.PNG12.PNG?raw=true)



Las Tablas Creadas Son Las Siguientes, Y Se Visualizan En El Phpmyadmin
![](https://github.com/MariaC30/TestLaravel/blob/main/Imagenes/Captura.PNG13.PNG?raw=true)


En El Documento Usertest Se Modifica La FuncióN PúBlica De Test_login_form() Y En La Parte De Use Se Modifica A Test\Testcase 
![](https://github.com/MariaC30/TestLaravel/blob/main/Imagenes/Captura.PNG14.PNG?raw=true)

Posteriormente Se Ejecutan Las Pruebas Con El Comando Php Artisan Test. 
![](https://github.com/MariaC30/TestLaravel/blob/main/Imagenes/Captura.PNG15.PNG?raw=true)



Al Ejecutar Las Pruebas Una De Las Pruebas Sale Que El Test Usertest Es Fail
![](https://github.com/MariaC30/TestLaravel/blob/main/Imagenes/Captura.PNG16.PNG?raw=true)

Sl Ejecutar El Php Artisan Serve Sale Un Error Al Darle En Login
![](https://github.com/MariaC30/TestLaravel/blob/main/Imagenes/Captura.PNG17.PNG?raw=true)

Cuando Se Ejecuta El Comando Npm Install Suguiere Una Nueva Version Disponible
![](https://github.com/MariaC30/TestLaravel/blob/main/Imagenes/Captura.PNG18.PNG?raw=true)




Por Lo Que Se Ejecuta El Comando Sugerido  Npm Install -G Npm@8.19.1 
![](https://github.com/MariaC30/TestLaravel/blob/main/Imagenes/Captura.PNG19.PNG?raw=true)


Despues De Este Comando Se Lanza De Nuevo El Comando Npm Run Dev
![](https://github.com/MariaC30/TestLaravel/blob/main/Imagenes/Captura.PNG20.PNG?raw=true)



Ahora El Login Ya Funciona
![](https://github.com/MariaC30/TestLaravel/blob/main/Imagenes/Captura.PNG20.PNG?raw=true)




El Error Que Tuvimos En El Login Se Soluciona Poniendo En La Funcion 500 En Lugar De 200 Ahora Todos Los Test Van En Pass
![](https://github.com/MariaC30/TestLaravel/blob/main/Imagenes/Captura.PNG21.PNG?raw=true)


Luego Se Crea La AplicacióN Para Evitar Que Se Creen Dos Usuarios Con El Mismo Nombre O El Mismo Email
![](https://github.com/MariaC30/TestLaravel/blob/main/Imagenes/Captura.PNG22.PNG?raw=true)


Se Agrega El Use App\Models\User
![](https://github.com/MariaC30/TestLaravel/blob/main/Imagenes/Captura.PNG23.PNG?raw=true)




En Se Hace Otro Test Para Verificar Que La Funcion Pass. Todas Las Pruebas De Los Test Pasan. 
![](https://github.com/MariaC30/TestLaravel/blob/main/Imagenes/Captura.PNG24.PNG?raw=true)


