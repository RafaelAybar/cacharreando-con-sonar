# Ejemplos de configuración de Sonarqube

## Ejemplo del fichero sonar.properties
Debemos crear en el directorio **sonarqube_conf** un archivo llamado sonar.propierties que contenga una estructura parecida:
```
sonar.jdbc.url=jdbc:postgresql://db/sonar
sonar.jdbc.username=rafa
sonar.search.javaAdditionalOpts=-Dbootstrap.system_call_filter=false
sonar.jdbc.password=CambiameInmediatamente
```