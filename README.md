# Tarea 03: Metaheurísticas de Trayectoria

## Integrantes del equipo:

- **Ángeles Sánchez Aldo Javier 320286144**
- **Jurado Guadalupe Aldo Emilio 320025255**

## Requisitos

Este proyecto usa maven. <br>
**Instalación desde terminal:**

### En fedora:

```bash
sudo dnf install maven
```

### En ubuntu:

```bash
sudo apt install maven
```

Adicionalmente ya se debe tener java con su **jdk**.
De no tenerlo, en fedora se instala de la siguiente forma:

```bash
sudo dnf install java-devel

```

## Compilar y Ejecutar

Para compilar de forma limpia:

```bash
mvn clean install
```

Para ejecutar el programa (después de compilar):

```bash
java -jar target/ejecuta.jar
```

## Limpieza

Adicionalmente para limpiar los archivos generados por la compilación:

```bash
mvn clean
```

## Comentarios

# Sobre la interfaz 

El programa cuenta con una pequeña interfaz de texto para ir seleccionando
las distintas opciones para la ejecución de los algoritmos.
Los parámetros se pasan después de la ejecución.
