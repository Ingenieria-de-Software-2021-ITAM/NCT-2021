# 1 Introduction

## 1.1 Purpose

## 1.2 Document Conventions

## 1.3 Intended Audience and Reading Suggestions
Este documento está destinado a los desarrolladores y escritores de documentación que trabajarán en los diferentes requerimentos para el sistema de inscripciones.

## 1.4 Product Scope
El proyecto desarrollado es un sistema de inscripciones para los alumnos del ITAM. 

## 1.5 References

# 2. Overall Description

## 2.1 Product Perspective
Este proyecto se desarrolló en clase de Ingeniería de Software y agrega funcionalidades al sistema existente de inscriciones del ITAM.

## 2.2 Product Functions
Las principales funciones de este sistema es:
- Dar clases de alta.
- Dar clases de baja.
- Mostrar el plan de estudio de los alumno y la lista de materias que puede llevar el siguiente semestre.

## 2.3 User Classes and Characteristics

## 2.4 Operating Environment

## 2.5 Design and Implementation Constraints

## 2.6 User Documentation

### **Sistema:** Incripciones ITAM
### **Description and Priority:** Medium priority. 
Feature que incluya el plan de estudios con el que el alumno está registrado. Muestra la seriación de las materias, las materias que ya fueron cursadas y las materias que se recomienda llevar en el semestre en el que se encuentra.  
- Benefit: 8 
- Penalty: ? 
- Cost: 7 (espacio en base de datos) 
- Risk: 3 
### **Stimulus / Response Sequences:** 
- El inicio del semestre/día de la inscripción 
- Si el usuario acreditó una materia, el sistema lo registra y actualiza la lista de materias que el alumno ha acreditado y la lista de materias que puede llevar ahora. 
- Si el alumno desea conocer las materias que puede llevar o que ya llevó, el sistema le despliega la lista correspondiente. 
### **Functional Requirements:**
- REQ-1: Mostrar serialización de materias.  
- REQ-2: Mostrar las materias que ya fueron cursadas. 
- REQ-3: Mostrar las materias que se recomienda llevar por semestre.  
- REQ-4: Mostrar la razón por la que no se permite a un alumno llevar la materia. 
