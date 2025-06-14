# ScreemMatchCurso1Java
# Screenmatch - Proyecto Java de Series

**Screenmatch** es una aplicación desarrollada en Java que permite buscar, analizar y procesar series de televisión utilizando datos provenientes de una API externa. El proyecto fue desarrollado como parte del curso _"Java Web: crea aplicaciones utilizando Spring Boot"_ y tiene como objetivo aplicar buenas prácticas de desarrollo con Java moderno.

## 🚀 Tecnologías y herramientas utilizadas

- **Java 17**
- **Spring Boot**
- **Lambdas y Streams**
- **Jackson (para deserialización JSON)**
- **API REST**
- **Maven**

## 🎯 Funcionalidades principales

- Consulta de series desde una API externa.
- Deserialización de datos JSON con la biblioteca Jackson.
- Filtrado, ordenamiento y análisis de datos usando lambdas y streams.
- Cálculo de estadísticas personalizadas sobre las series.
- Estructura modular y limpia basada en principios SOLID.

## 📚 Lo que aprendí

Este proyecto fue una excelente oportunidad para profundizar en:

✅ El uso del **framework Spring Boot** en aplicaciones Java.  
✅ **Deserialización de datos** desde una API externa usando Jackson.  
✅ El poder de las **expresiones lambda** para escribir código más conciso y expresivo.  
✅ Cómo **manipular colecciones** de datos usando la API de **Streams**.  
✅ La implementación de **estadísticas personalizadas**, como promedio de puntuaciones, duración media, entre otros.

## 🛠️ Estructura del proyecto

screenmatch/
├── .idea/
├── .mvn/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/aluracursos/screenmatch/
│   │   │       ├── model/
│   │   │       │   ├── DatosEpisodio.java
│   │   │       │   ├── DatosSerie.java
│   │   │       │   ├── DatosTemporadas.java
│   │   │       │   └── Episodio.java
│   │   │       ├── principal/
│   │   │       │   ├── EjemploStreams.java
│   │   │       │   └── Principal.java
│   │   │       ├── service/
│   │   │       │   ├── ConsumoAPI.java
│   │   │       │   ├── ConvierteDatos.java
│   │   │       │   └── IConvierteDatos.java
│   │   │       └── ScreenmatchApplication.java
│   │   └── resources/
│   └── test/
├── target/
├── .gitattributes
├── .gitignore
├── HELP.md
├── mvnw
├── mvnw.cmd
├── pom.xml

Descripción de carpetas y clases
model/: Contiene las clases que representan los datos del dominio como series, temporadas y episodios.

principal/: Clases principales para ejecutar el programa y realizar pruebas con Streams.

service/: Lógica de negocio, consumo de API y conversión de datos JSON.

ScreenmatchApplication.java: Clase principal con @SpringBootApplication, punto de entrada del proyecto.

