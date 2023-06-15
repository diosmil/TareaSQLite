# TareaSQLite

Mi aplicación fue desarrollada utilizando Android Studio y aprovecha la potencia de SQLite para gestionar una base de datos local. La funcionalidad de SQLite se implementó a través del uso de la clase SQLiteOpenHelper, la cual me permitió crear y administrar la base de datos de manera eficiente.

Para comenzar, diseñé la interfaz de usuario utilizando XML en Android Studio. Utilicé componentes como ListView para mostrar una lista interactiva de elementos, ImageView para mostrar imágenes, botones para realizar acciones y campos de texto para ingresar y mostrar datos.

[GESTOR_DE_NOTA_SQLITE.zip](https://github.com/diosmil/TareaSQLite/files/11764030/GESTOR_DE_NOTA_SQLITE.zip)
Luego, creé la base de datos utilizando la clase SQLiteOpenHelper. Esta clase me permitió definir el esquema de la base de datos, incluyendo la estructura de las tablas y las columnas que necesitaba para almacenar los datos relevantes de mi aplicación. También proporcionó métodos para crear, actualizar y manipular la base de datos de manera eficiente.

Definí el esquema de mi base de datos en la clase SQLiteOpenHelper, donde pude especificar los nombres de las tablas, los nombres de las columnas y los tipos de datos correspondientes. También creé clases modelo (POJO) para representar cada tabla de mi base de datos. Estas clases modelo definieron los campos y métodos necesarios para acceder y manipular los datos almacenados en las tablas.

Una vez que mi base de datos estaba configurada, pude realizar operaciones de CRUD (Create, Read, Update, Delete) en ella. Utilizando los métodos proporcionados por SQLiteOpenHelper, pude insertar nuevos registros en la base de datos, leer datos para mostrar en el ListView, actualizar registros existentes y eliminar registros no deseados.

La interacción entre la base de datos SQLite y la interfaz de usuario fue fundamental en mi aplicación. Por ejemplo, cuando el usuario hacía clic en el botón "Guardar", recopilé los datos ingresados en los campos de texto correspondientes. Luego, utilicé los métodos de inserción provistos por SQLiteOpenHelper para crear un nuevo registro en la base de datos. Además, actualicé la interfaz de usuario para mostrar los cambios reflejados en la base de datos, asegurándome de que los nuevos datos se reflejaran correctamente en la pantalla.

Para mostrar los datos almacenados en la base de datos, utilicé un adaptador personalizado en conjunto con el ListView. Este adaptador se encargó de vincular los datos de la base de datos con las vistas correspondientes en el ListView, lo que permitió mostrar una lista de elementos de manera eficiente y coherente.
