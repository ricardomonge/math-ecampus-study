# Descripción de los datos del estudio

Este repositorio contiene dos bases de datos anonimizadas y el cuestionario de encuesta aplicados en el marco de un estudio sobre un **taller asincrónico de nivelación en matemática** dirigido a estudiantes adultos que ingresan a programas online de ingeniería en modalidad de continuidad de estudios.

---

## 1. `dataset_grades_anonymized.csv`

Este archivo contiene información cuantitativa de desempeño académico de **374 estudiantes** inscritos en el taller. Las variables incluidas son:

- **sexo**: Género declarado del participante (`masculino`, `femenino`).  
- **edad**: Edad en años cumplidos.  
- **avance_malla**: Porcentaje de avance curricular en la malla de continuidad de estudios.  
- **nota_final**: Calificación final en la primera asignatura de matemática de la malla (Cálculo Superior).  
- **condicion_final**: Condición de aprobación en dicha asignatura (`Aprobado`, `Reprobado`).  
- **pre_test**: Puntaje en prueba diagnóstica inicial (escala 0–40 puntos).  
- **post_test**: Puntaje en prueba diagnóstica final (escala 0–40 puntos).  

---

## 2. `dataset_survey_anonymized_v2.csv`

Este archivo corresponde a las respuestas de la **encuesta de cierre del taller** aplicada a los participantes. Incluye:

- **p01** a **p64**: Ítems de satisfacción, percepción y autoevaluación de aprendizaje, respondidos en escala Likert de 1 a 5 (1 = Deficiente / Muy en desacuerdo, 5 = Excelente / Totalmente de acuerdo) o como texto abierto.  
- **p02 (NPS)**: Pregunta de recomendación del taller tipo Net Promoter Score (NPS), que fue omitida en este estudio.  
- **p12, p13, p22, p28, p36, p64**: Respuestas abiertas que recogen percepciones cualitativas sobre aspectos positivos, sugerencias de mejora, experiencia con tutoría y apoyo técnico y consejos a futuros estudiantes.  

---

## 3. Cuestionario de encuesta

El instrumento original (*Encuesta de Cierre del Taller*) consideró las siguientes secciones principales:

1. **Evaluación general del taller** (p01).  
2. **Recomendación del taller (NPS)** (p02, omitida en el dataset).  
3. **Efectividad del taller en dimensiones clave**: calidad, relevancia, aplicabilidad, accesibilidad, estructura, enseñanza, plataforma, aprendizaje interactivo, comunicación y apoyo (p03–p11).  
4. **Contribución de materiales y recursos**: cuestionarios diagnósticos, cápsulas de aprendizaje, materiales PDF, foro, soporte técnico (p14–p21).  
5. **Percepción de la tutoría y apoyo docente** (p23–p27).
6. **Evaluación del equipo de soporte** (p29-p35).
7. **Confianza en resultados de aprendizaje asociados a contenidos de álgebra, cálculo e integrales** (p37-p55).  
8. **Carga, dificultad y duración del taller en comparación con expectativas** (p56-p57).  
9. **Comparación con experiencias previas de aprendizaje en línea** (p58-p59).  
10. **Impacto percibido en la trayectoria académica** (p60-p63). 

---

## 4. Notas metodológicas

- Los datos fueron **anonimizados** antes de su publicación, eliminando identificadores personales y excluyendo la pregunta NPS.  
- Las escalas de pre y post test (0–40) permiten evaluar cambio inmediato en desempeño matemático.  
- Los datos de encuesta integran tanto **respuestas cerradas** (escala Likert) como **respuestas abiertas**, lo que habilita análisis mixtos.  

---
