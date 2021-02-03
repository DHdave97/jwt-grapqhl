# Sistema de login / registro con JWT en GraphQL con MongoDB

En este proyecto se crea un sistema para registro de usuarios usando JWT para conseguir el inicio de sesión y obtener el token  para autenticarse en GraphQL.

## Requerimientos

* Node v10.16.0 o más.
* NPM v6.0.0 o más
* MongoDB instalado y en funcionando.

## Intrucciones de uso

### Clonar el repositorio / descargar.
```git clone https://github.com/DHdave97/jwt-grapqhl```

### Instalar las dependencias de NPM
```npm install```

### Crear el fichero de variables de entorno
Crear el fichero .env dentro del directorio "src"
```
PORT=<numero-puerto>
SECRET=<PALABRA_SECRETA>
DATABASE=mongodb://localhost:27017/<base-de-datos>
```

### Iniciar en debug
```npm run start:dev```