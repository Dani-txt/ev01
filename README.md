# ev01
# Respuesta del punto 2 (GitFlow o Trunk-Based)
- Creamos diferentes branch (main, develop, feature/daniel y hotfix/daniel) por lo que es GitFlow.

-Esta metodología de trabajo ayuda a que los equipos con gran cantidad de colaboradores puedan organizarse  y manejen diferentes versiones(hotfix)

#Naming ramas
- Main --> Producción

- develop --> Integración de nuevas funcionalidades

- feature/* --> desarrollo de nuevas funcionalidades

- hotfix/* --> correciones rápidas

#Convenciones de commits

- feat: agrega nueva funcionalidad

- fix: corrige errores

- docs: cambios en documentación

- test pruebas unitarias

#Flujos merge

- Se ingresa a la branch feature

- Realizar cambios y commit

- desde feature se realiza el pullrequest hacia develop

- revisión de cambios

- en caso de errores o correicones criticas utilizar hotfix

- hotfix debe ser integrado a main y develop

#Estrategias de revision

- No realizar push directos en main

- todo cambio en produccion debe ser mediante pullrequest

- verificar funcionamiento del codigo antes de ir a produccion

# GitHub Actions

- Se creó un yml que automatiza un proceso de verificación cuando se hacen push en develop y pull request en main. 