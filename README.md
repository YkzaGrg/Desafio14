# Desafio14
Repositorio para Desafio 14 Devops BootCamp

Crear un cluster utilizando una herramienta a elección (microk8s, minikube,
kind, Docker desktop + kubernetes, etc.).  
Crear e implementar archivos de manifiesto: deployment + services utilizando
como aplicación, la imagen construida del desafío 13 - PIPELINES.   
Los archivos de manifiesto se deben encargar de construir y levantar los pods,
servicios, volumes, secrets, etc. 
  
KUBERNETES 
1. Crear un cluster correctamente para tener un ambiente de trabajo,
puede llamarse “DEV”. 
 
2. Utilizar la imagen ya construida en el desafío anterior para convertir en
recursos de kubernetes. 
Los mismos deben ser deployments + recursos adicionales, como, por
ejemplo, secrets, volumes, configmaps, services, etc. 
La configuración del deployment debe tener al menos 3 pods y permitir
que siempre que exista una nueva versión, se debe crear 1 pod del
nuevo replicaset antes de eliminar un pod del replicaset anterior, esto
garantiza que una vez que el pod de la nueva versión esté funcionando,
se remueva un pod de la versión anterior.
 
3. Se debe exponer la aplicación y poder acceder a ella mediante un
navegador. 
  
GITHUB  
1. Publicar todos los archivos creados en su repositorio personal. 
