# Examen_AD
1. primero hay que correr el servidor local para poder almacenar nuestro datos traidos de la API de twitter. Para poder tomar estos datos es necesaria la utilizacion de los tokens proporcionados por twitter
Nota. Es importante utilizar las librerias de couchdb

2. Web_scraping se realiza utiizando la libreria de BeautifulSoup la cual nos permite extraer codigo html, posteriormente se deve utilizar las librerias de pymongo e importar el MongoCliente, que nos permite manejar el servidor local

3. Para poder hacer cosecha de posts, debemos usar la libreria facebook_craper que nos proporciona el metodo get_posts y debemos levantar el servidor local de mongo compass

4.

5. Esto debemos realizarlo levantando ambos servidores locales, tanto de mongo como de couch y se deben utilizar las librerias pymongo y couchdb, cuando ya lo tengamos se debera hacer lectura de una base de datos de un servidor y escritura hacia la base de datos del otro servidor

6. Este proceso es similiar al anterior con la diferncia que la lectura y escritura se lo hace en sentido contrario

7. El servidor local de couchdb debe estar levantado, tambien el servidor de mongo atlas, con la diferencia de que la ruta del servidor de atlas, cambia ya que no estaremos trabajando de manera local.

8. La libreria de mongodb, nos permite realizar este conexión con la diferencia que las direcciones de destino deben cambiar, ademas a cada una de estas direcciones se le debe asignar un cliente diferente. El comcepto sigue siendo el mismo leer de un base de datos y escribirlo en la otra

9 y 10. en este jercicio lo que se hizo fue crear un objeto vacio, que posteriormente en la lectura de la base de datos de mongoAtlas se escribiria en este objeto.
Nota: para realizar este ejercicio, se hizo uso de la libreria pandas para poder utilizar su metodo DataFrame
