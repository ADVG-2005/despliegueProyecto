Pasos para desplegar el proyecto de Agrosoft creado por el grupo 1.
REQUISITOS:  
1. Tener docker en su pc
2. Tener docker-compose.

PASOS:
1. Clonar este repositorio en su ordenador: "https://github.com/ADVG-2005/despliegueProyecto.git"
2. Entrar a la carpeta clonada. "cd despliegueProyecto"
3. Abrir una cmd y ejecutar el siguiente comando: "docker-compose up -d --build"
4. esto ejecutara el build, creara y correra los contenedores
5. Ingresar con su IP local al navegador seguido de los siguientes puertos:
frontend: 5173
backend : 8000
