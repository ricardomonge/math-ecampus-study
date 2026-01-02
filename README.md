# Repositorio de datos y análisis para el estudio: “Nivelación matemática asincrónica para estudiantes adultos de continuidad de estudios de ingeniería en modalidad online”

## Descripción  
Este repositorio contiene los datos anonimizados y los scripts de análisis utilizados en un estudio que evaluó un taller asincrónico de nivelación matemática en estudiantes adultos de un programa de Ingeniería Civil Industrial en modalidad online.  

Los datos fueron anonimizados para resguardar la confidencialidad de los participantes y se comparten con fines de transparencia y reproducibilidad científica.

---

## Estructura del repositorio
- `dataset_grades_anonymized.csv`  
  Puntajes de pretest y postest de los estudiantes que participaron en el taller.  

- `dataset_survey_anonymized_v2.csv`  
  Respuestas anonimizadas de la encuesta de percepción estudiantil (ítems tipo Likert y respuestas abiertas).  

- `data_analysis_scores.ipynb`  
  Notebook en Python con el análisis de los puntajes (descriptivos, Wilcoxon, Cliff’s delta, visualizaciones).

- `dataset_readme.md`  
  Documentación de los datasets: variables, cuestionario asociado y notas metodológicas.  

- `data_analysis_survey.ipynb`  
  Notebook en Python con el análisis de la encuesta (descriptivos, confiabilidad, análisis de texto con embeddings y clustering).  

---

## Metodología (resumen)
- **Diseño**: cuasiexperimental de un solo grupo con medidas pre y post.  
- **Participantes**: 238 estudiantes adultos (tasa de finalización = 63,6%).  
- **Instrumentos**:  
  - Pretest y postest de matemáticas (40 ítems de opción múltiple).  
  - Encuesta de percepción (Likert + preguntas abiertas).  
- **Análisis**:  
  - Wilcoxon y Cliff’s delta (δ) con IC95% bootstrap.  
  - Alfa de Cronbach para confiabilidad.  
  - Procesamiento de lenguaje natural (embeddings + clustering exploratorio).  

---

## Ética y datos
- Todos los datos fueron **anonimizados** antes de su publicación.  
- La participación fue **voluntaria** y con consentimiento informado.  
- El estudio se realizó conforme a los principios del **Belmont Report (1979)**.  

---

## Reproducibilidad
Para ejecutar los análisis:  
1. Clonar este repositorio.  
2. Abrir los notebooks en Jupyter o VSCode.  

Ejemplo:  
```bash
git clone https://github.com/ricardomonge/math-ecampus-study.git
cd math-ecampus-study
jupyter notebook
```
---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Referencia del estudio

Si utilizas estos datos o scripts, por favor cita:

Monge-Rogel, R. (2025). Nivelación matemática asincrónica para estudiantes adultos de continuidad de estudios de ingeniería en modalidad online.

## Contacto

Autor: Ricardo Monge-Rogel,
Instituto de Matemática, Física y Estadística,
Universidad de Las Américas, 
📧 rmonge@udla.cl
