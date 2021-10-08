# NCT-2021-srs
SRS ejercicio markdown
**Sistema:** Incripciones ITAM
**Description and Priority:** Medium priority. Feature que incluya el plan de estudios con el que el alumno está registrado. Muestra la seriación de las materias, las materias que ya fueron cursadas y las materias que se recomienda llevar en el semestre en el que se encuentra.  
-Benefit: 8 
-Penalty: ? 
-Cost: 7 (espacio en base de datos) 
-Risk: 3 
**Stimulus / Response Sequences:** 
-El inicio del semestre/día de la inscripción 
-Si el usuario acreditó una materia, el sistema lo registra y actualiza la lista de materias que el alumno ha acreditado y la lista de materias que puede llevar ahora. 
-Si el alumno desea conocer las materias que puede llevar o que ya llevó, el sistema le despliega la lista correspondiente. 
**Functional Requirements:**
-REQ-1: Mostrar serialización de materias.  
-REQ-2: Mostrar las materias que ya fueron cursadas. 
-REQ-3: Mostrar las materias que se recomienda llevar por semestre.  
-REQ-4: Mostrar la razón por la que no se permite a un alumno llevar la materia.  
