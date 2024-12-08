# API de Tinaco Inteligente

Este proyecto es una API para controlar y monitorear un tinaco inteligente. La API permite obtener y almacenar datos de varios sensores, así como visualizar estos datos en una interfaz web.

## Estructura del Proyecto

## Instalación

1. Clona el repositorio:
    ```sh
    git clone <URL_DEL_REPOSITORIO>
    cd <NOMBRE_DEL_REPOSITORIO>
    ```

2. Instala las dependencias:
    ```sh
    npm install
    ```

3. Crea un archivo `.env` en la raíz del proyecto con las siguientes variables de entorno:
    ```env
    DB_HOST=<tu_host_de_base_de_datos>
    DB_PORT=<tu_puerto_de_base_de_datos>
    DB_USER=<tu_usuario_de_base_de_datos>
    DB_PASS=<tu_contraseña_de_base_de_datos>
    DB_NAME=<tu_nombre_de_base_de_datos>
    CA_CERT=<tu_certificado_CA>
    SERVER_PORT=3000
    ```

## Uso

1. Inicia el servidor:
    ```sh
    npm start
    ```

2. Abre tu navegador y navega a `http://localhost:3000` para ver la interfaz web.

## Endpoints

### Tabla 1
- `GET /iot/api/getValoresTabla1` - Obtener valores de la tabla 1
- `POST /iot/api/insertarValoresTabla1` - Insertar valores en la tabla 1
- `GET /iot/api/getLastIDt1` - Obtener el último ID de la tabla 1
- `GET /iot/api/getButonId` - Obtener el ID y botón de la tabla 1

### Tabla 2
- `GET /iot/api/getValoresTabla2` - Obtener valores de la tabla 2
- `POST /iot/api/insertarValoresTabla2` - Insertar valores en la tabla 2
- `GET /iot/api/getLastIDt2` - Obtener el último ID de la tabla 2
- `GET /iot/api/getLastFotoRes` - Obtener la última fotoresistencia de la tabla 2
- `GET /iot/api/getlastDist` - Obtener la última distancia de la tabla 2
- `GET /iot/api/getAllDist` - Obtener todas las distancias de la tabla 2

### Tabla 3
- `GET /iot/api/getValoresTabla3` - Obtener valores de la tabla 3
- `POST /iot/api/insertarValoresTabla3` - Insertar valores en la tabla 3
- `GET /iot/api/getlastTDS` - Obtener el último TDS de la tabla 3
- `GET /iot/api/getallTempe` - Obtener todas las temperaturas de la tabla 3

### Tabla 5
- `GET /iot/api/getValoresTabla5` - Obtener valores de la tabla 5
- `GET /iot/api/getlastFotovalT5` - Obtener el último fotoval de la tabla 5
- `GET /iot/api/getlastFotovalId` - Obtener el último ID de fotoval de la tabla 5
- `POST /iot/api/insertFotoValT5` - Insertar fotoval en la tabla 5

### Tabla Final
- `GET /iot/api/getValoresTablaF` - Obtener valores de la tabla final
- `POST /iot/api/insertarValoresTablaF` - Insertar valores en la tabla final
- `GET /iot/api/getValoresByDate` - Obtener valores por fecha en la tabla final

## Despliegue

Este proyecto está configurado para ser desplegado en Vercel. El archivo `vercel.json` contiene la configuración necesaria.

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o envía un pull request.

Este proyecto esta funcionando actualmente en vercel. https://tinaco.vercel.app/DataView.html
