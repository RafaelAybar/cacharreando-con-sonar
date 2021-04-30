# Cacharreando con sonar
Este repositorio está destinado a enseñar cómo realizar análisis con SonarQube.

Para ello analizaremos scripts sueltos de Python a ver qué podemos mejorar/pulir de nuestro código

## Instalación de Sonar
- Pasos previos: Creación de los siguientes directorios
    - postgresql_data: Persistiremos los datos del contenedor de postgres en este directorio.
    - sonarqube_conf: Persistiremos la configuración de Sonar en este directorio.
    - sonarqube_data: Persistiremos los datos del contenedor de Sonar en este directorio
    - sonarqube_extensions: Persisitemos en este directorio los plugins usados por SonarQube

- Configuraciones de Sonar y Postgresql:
    - [Configuración de Sonar](docs/sonar.md)
    - [Configuración de Postgres](docs/postgres.md)

Nota: Para solucionar el problema de Elastic de memoria en Linux: [Enlace](https://stackoverflow.com/questions/51445846/elasticsearch-max-virtual-memory-areas-vm-max-map-count-65530-is-too-low-inc)
