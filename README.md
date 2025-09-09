# Generador de Material Educativo con Fast Prompting

Curso: IA — Generación de Prompts  
Autor: Camilo Gómez  

## Introducción
El problema que busqué resolver es que muchos profes no tienen tiempo para crear material didáctico atractivo y adaptado. La idea del proyecto es usar Fast Prompting para generar cuestionarios, resúmenes, explicaciones e imágenes educativas de forma rápida con IA.  

## Objetivos
- Probar técnicas de Fast Prompting  
- Hacer una POC en Jupyter Notebook  
- Optimizar llamadas a la API  
- Comparar prompts básicos con optimizados  

## Herramientas
- Python con Jupyter Notebook  
- API de Gemini (`gemini-1.5-flash` y `gemini-1.5-pro`)  
- Librerías: google-generativeai, dotenv  

## Implementación
En la notebook `entrega2_gomez.ipynb` armé funciones para:  
- Generar quizzes en JSON  
- Crear resúmenes cortos  
- Explicar temas paso a paso  
- Hacer prompts para imágenes  

Ejemplo de uso:
```python
print(generate(quiz_prompt("Fotosíntesis")))
print(generate(summary_prompt("Revolución Francesa")))
