# pruebaTecnicaPHP
# Proceso de instalación
1.	Para iniciar con el proceso de ejecución del proyecto “Prueba Técnica PHP”, necesitaremos descargar o clonar el proyecto que se encuentra alojado en un repositorio de GitHub de manera pública.
•	Repositorio GitHub: https://github.com/BrianMOYA/pruebaTecnicaPHP

2.	Una vez descargado el proyecto, procedemos a colocarlo dentro de la siguiente ruta de nuestro servidor web. Por mi parte utilice “WampServer”.

•	C:\wamp64\www\, aquí procedemos a copiar el proyecto “pruebaTecnicaPHP”. Por lo cual, la ruta nos quedaría de la siguiente manera: C:\wamp64\www\pruebaTecnicaPHP

 

3.	Inicializamos el servidor WEB “WampServer” y ejecutamos el “PhpMyAdmin” para importar la base de datos del proyecto, una vez se ejecute este, ingresamos nuestras credenciales e iniciamos sesión
 
 

4.	Dentro de “PhpMyAdmin”, nos dirigimos al menú que se encuentra en la parte superior y seleccionamos la opción “Importar”, se abrirá un apartado que nos permitirá seleccionar el archivo “sql” del proyecto y escogemos el archivo “inventario.sql”, una vez seleccionada, nos dirigimos a la parte inferior y buscamos la opción “Importar”
  
 

5.	Al importar la base de datos, la podremos visualizar al lado izquierdo de la plataforma y ahora iniciamos nuestro Localhost para correr el proyecto, dentro de “WampServer” ya podemos observar el proyecto, en este caso, para poderlo ejecutar colocamos en la URL el nombre del proyecto para inicializarlo

6.	Al importar la base de datos, la podremos visualizar al lado izquierdo de la plataforma y ahora iniciamos nuestro Localhost para correr el proyecto 
Credenciales de acceso usuario Administrador

•	Usuario: adminBrian
•	Contraseña: admin
 
Credenciales de acceso usuario Vendedor
•	Usuario: vendHeelen
•	Contraseña: vendedor1
 
NOTA: En caso tal de que el usuario vendedor no deje ingresar por la contraseña, se puede ingresar como usuario administrador y cambiar la contraseña de este usuario

7.	Al ingresar como usuario administrador, podremos visualizar que la página principal muestra las categorías, los clientes y los productos almacenados en el proyecto, además encontramos un menú lateral que se despliega de izquierda a derecha con las diferentes funcionalidades que podremos usar, ya, por último, en la parte inferior se encuentra una estadística con los productos más vendidos y a la derecha los productos recién agregados 
 
 
# 8.	Interfaz Usuarios
En este apartado, podemos añadir un nuevo usuario, cambiar su estado de activado a desactivado, se puede modificar y eliminar sus datos y, por último, podemos realizar una búsqueda de los usuarios que tengamos registrados 
 
          
           
# 9.	Interfaz Categorías
En este apartado, podemos añadir una nueva categoría, editarla y eliminar.
 
  
 

# 10.	 Interfaz Productos
En este apartado, podemos añadir un nuevo producto, buscar un producto, editarlo y eliminarlo, además podemos revisar el stock que este mismo tiene, ya que se identifica por colores, el color verde identifica que el producto tiene un buen stock, el color naranja que tiene poco stock y el color rojo significa que esta próximo agotarse 
 
  
 
 
# 11. Interfaz Clientes
En este apartado, podemos añadir un nuevo cliente, editarlo y eliminarlo.
 
         
# 12. Interfaz Ventas
En este último apartado, podemos visualizar 3 módulos “Administrar Ventas”, “Crear Ventas” y “Reporte de ventas”, en los cuales podemos realizar un proceso de gestión, ya sea para visualizar las ventas realizadas, visualizar las estadísticas de los productos mas vendidos y sus compradores. Por último, podemos crear una venta, en la cual, el stock del producto se ira descontando cada que se venda ese producto.
