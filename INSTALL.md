

# requisitos 
 versión de node 16.16.0 ,db mysql 
 
# front end 
paso 1 -> git clone "https://github.com/williams-max/proyecto_examen.git"
paso 2-> una vez ubicado en carpeta(frontend_exa) del proyecto ejecute npm install or npm install –force
paso 3-> seguidamente el comando npm start 
Nota: tiene que levantar primero el backend antes del front end

# backend base de datos configurada por defecto con conexion remota
paso 1 -> git clone  "https://github.com/williams-max/proyecto_examen.git" si aun lo clono
paso 2-> una vez ubicado en carpeta(backend_exa) del proyecto ejecute npm install or npm install –force
paso 3-> genera la base de datos , el script estar ubicado en la raiz del proyecto backend 0 
puede acceder a la base de datos que configure para este proyectpo ingresando en la siguiente direcion https://phpmyadmin.alwaysdata.com/  credenciales
  user: 'chevy_free',
  password: 'adivinala',

paso 4-> cambie sus credenciales de a sube de datos ubicación del arribo config/db.config
paso 5-> seguidamente el comando npm start 

# Diseño de base de datos
ser creo una tabla usuarios para el registro y otras tabla movies, al cual se le añadio un campo
adicional idusario pagar tener la referencia de la pelicula guardada(agregada a favoritos)
