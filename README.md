# PC4-Orquestador-de-flujos-basado-en-eventos-Grupo-2

Este repositorio contiene mi contribución en el proyecto grupal correspondiente a la pc4 del curso de Desarrollo de Software.
[Link del repositorio grupal](https://github.com/JunalChowdhuryG/Grupo-2-Practica-Calificada-4/tree/feature-event-engine%2C): 


## Sprint 1:
[Video sprint 1](https://www.youtube.com/watch?v=Z1AAJkgW170)

### Issue 3

Creación de un motor de eventos un motor de eventos que detecte la creacion de archivos y mensajes en Redis para que el sistema pueda orquestar flujos de trabajo basados en eventos

### Issue 5
Creación de scripts para procesar archivos creados y mensajes Redis
y que el sistema ejecute acciones basadas en eventos de manera automatizada

## Sprint 2:
[Video sprint 2](https://www.youtube.com/watch?v=DnACQzOHIfs)

### Issue 10
Integrar el modulo de despliegue Kubernetes en el motor de eventos
para que un evento detectado (e.g., archivo creado) pueda disparar un despliegue en Kubernetes.

### Issue 11
Implementación de un mecanismo para manejar dependencias entre flujos de trabajo
para que un flujo no se ejecute hasta que otro haya completado exitosamente.

## Sprint 3:
[Video sprint 3](https://www.youtube.com/watch?v=dUviqheerLo)

### Issue 13 
Lograr que el flujo k8s_nginx procese eventos en /app/data/k8s sin ser interceptado por process_file
Para que el despliegue Kubernetes se ejecute correctamente y cree los recursos esperados

**Las evidencias se encuentran en la carpeta patches**
 