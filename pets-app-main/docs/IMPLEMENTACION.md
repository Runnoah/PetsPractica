## Documentacion del proceso

## Índice
### 1. Descripción general del objetivo.
### 2. Estructura final.
### 3. Separación del fichero application.properties.
### 4. Resumen del Dockerfile y de los ficheros docker-compose.
### 5. Descripción del flujo de trabajo en GitHub.
### 6. Evidencias gráficas de funcionamiento.
### 7. Conclusiones.

#### 1. Descripción general.

En esta práctica estamos usando el proyecto llamado "pets-app" el cual nuestro objetivo es realizar el despliegue de la aplicación usando Docker y Docker Compose, organizando la configuración en perfiles de Spring Boot y gestionando el desarrollo mediante un flujo estructurado en Github.

#### 2. Estructura final.

La estructura final del ejercicio es tal y como está pedida en la práctica, con las carpetas ordenadas y los archivos pedidos creados en sus respectivos lugares.

#### 3. Separación de los ficheros.

En la carpeta: src/main/resources está el application.properties, en la práctica nos pide crear dentro de esa misma carpeta el application-local.properties y el application-neon.properties, se pueden mantener vacios o podemos incluir en ellos propiedades comunes a ambos entornos.

#### 4. Resumen Dockerfile y docker-compose.

Montamos los archivos propios para poder montar nuestros contenedores en Docker, como principal el archivo "Dockerfile" en el que metemos el contenido dado en nuestra tarea y los docker-compose, se hacen dos dado que una parte lo hacemos en local y la otra en neon.

