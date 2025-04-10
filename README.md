# Creación de Escenarios con Docker Compose

La práctica consiste en la creación de escenarios utilizando **Docker Compose**, donde se desplegaron dos entornos:

- **Parte 1**: Implementación de **WordPress** junto con **MariaDB**.
- **Parte 2**: Implementación de **Redmine** junto con **PostgreSQL**.

En ambas partes se utilizaron contenedores Docker, con los archivos de configuración **docker-compose.yml** y las variables de entorno necesarias para cada uno de los servicios.

## Parte 1: WordPress + MariaDB

WordPress es un sistema de gestión de contenido (CMS) que requiere una base de datos como MariaDB para su funcionamiento. En esta práctica se configuraron ambos servicios utilizando Docker Compose.

- **Variables de entorno necesarias para MariaDB**:
  - `MARIADB_ROOT_PASSWORD`
  - `MARIADB_DATABASE`
  - `MARIADB_USER`
  - `MARIADB_PASSWORD`

## Parte 2: Redmine + PostgreSQL

Redmine es una aplicación web para la gestión de proyectos, y en esta parte se configuró junto con PostgreSQL, el sistema de gestión de bases de datos. La configuración incluyó la creación de un volumen para la persistencia de los datos y la conexión entre los contenedores.

- **Variables de entorno necesarias para PostgreSQL**:
  - `POSTGRES_PASSWORD`
  - `POSTGRES_USER`
  - `POSTGRES_DB`

**Fecha**: 2025-04



