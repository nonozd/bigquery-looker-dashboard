# Proyecto de BigQuery + Looker Studio

## Descripción
Este proyecto conecta una base de datos PostgreSQL en Google Cloud SQL con BigQuery
y visualiza los datos en un dashboard en Looker Studio.

## Pasos realizados
1. Creación de instancia PostgreSQL en Cloud SQL.
2. Configuración de transferencia de datos hacia BigQuery.
3. Creación de un conjunto de datos en BigQuery.
4. Construcción de un dashboard en Looker Studio con KPIs:
   - Total de estudiantes
   - Total de inscripciones
   - Total de cursos ofrecidos

## Evidencias
- [Capturas del dashboard][pruebas.docx](https://github.com/user-attachments/files/22630245/pruebas.docx)
  
- [BIGQUERY]<img width="1196" height="715" alt="image" src="https://github.com/user-attachments/assets/e7e8855f-c7b6-42bd-a7e6-6c27e0f61efe" />

- [Link al dashboard en Looker Studio](https://lookerstudio.google.com/reporting/13fdfd4e-4b5f-4eaf-bd39-b79d89af8338)

- PREGUNTA CREATIVA
  
Pensé en meterle algo de IA al sistema: se podría usar Vertex AI para entrenar un modelo que aprenda de los datos de inscripciones y calificaciones y que luego prediga qué estudiantes 
son más propensos a dejar el curso. Así, los profes o podrían recibir alertas y hacer algo antes de que pase

Otra idea sería un chatbot con Dialogflow conectado al sistema para que los estudiantes pregunten cosas rápidas 
como “¿en qué curso estoy inscrito?” o “¿cuándo empieza mi clase?” sin tener que entrar al sistema completo


## Autores
Felix Ordoñez - Elsa Salvatierra
