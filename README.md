# Infrastructure

## Requerimientos

Para poder levantar el proyecto hacer falta tener instalado docker y docker-compose. Ademas es necesario tener las credenciales del archivo .env

```
sudo pacman -S docker
pip install docker-compose
```
## Pasos para levantar el projecto


1. Crear una carpeta para el projecto y ingresar en ella.
```
mkdir app
cd app
```

2. Clonar los repositorios.  
```
git clone https://github.com/Trippi-ar/infrastructure.git
git clone https://github.com/Trippi-ar/publications.git
git clone https://github.com/Trippi-ar/frontend.git
```  

3. Entrar a la carpeta de infrastructure
``` 
cd infrastrcture  
```  

4. Crear un archivo .env con las credenciales. (Solicitar a @joaquinreyero)

```
nano .env
```

5. Hacer un docker-compose
```
docker-compose build --no-cache
```

6. Levantarlo
```
docker-compose up 
```  

7. Para acceder ingresar a las respectivas urls.

```
localhost:8001/docs

localhost:8003/docs

```
