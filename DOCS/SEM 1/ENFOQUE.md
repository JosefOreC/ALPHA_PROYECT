# Justificación del Enfoque Metodológico de Desarrollo

**Proyecto:** EcoLogística Lima – Optimizador de Rutas Sostenibles para DistriRápido S.A.C.

**Universidad Continental**
Facultad de Ingeniería – Escuela Profesional de Ingeniería de Sistemas e Informática

**Fecha:** 23/08/2026

---

## 1. Introducción

El presente documento tiene como objetivo justificar, de manera técnica y concisa, el enfoque metodológico de desarrollo de software más adecuado para el proyecto "EcoLogística Lima", una plataforma web orientada a la optimización de rutas de reparto de última milla mediante metaheurísticas (VRPTW y Green VRP) para la empresa ficticia DistriRápido S.A.C. Se analiza la conveniencia de aplicar un enfoque tradicional en cascada (Waterfall) frente a un enfoque ágil, considerando las características específicas del proyecto, el contexto académico y las restricciones de tiempo, presupuesto y equipo.

---

## 2. Características Relevantes del Proyecto

El proyecto presenta un nivel de incertidumbre técnica considerable, principalmente en el núcleo algorítmico (elección y ajuste de la metaheurística), así como requerimientos que dependen de retroalimentación progresiva (integración de datos de tráfico, restricciones normativas locales y validación de indicadores de sostenibilidad). Además, la propia consigna del proyecto establece un cronograma dividido en cuatro iteraciones con entregables incrementales a lo largo de catorce semanas, lo cual constituye en sí mismo una estructura iterativa e incremental, no secuencial.

---

## 3. Comparación de Enfoques

| Criterio | Waterfall (Cascada) | Ágil (Scrum/Incremental) |
|---|---|---|
| Requisitos | Deben estar completos y fijos desde el inicio | Se refinan progresivamente en cada iteración |
| Incertidumbre técnica (algoritmo de optimización) | Alto riesgo; errores se detectan tarde | Se valida y ajusta en cada sprint |
| Entregables intermedios | Un solo entregable final | Entregables funcionales por iteración (según cronograma) |
| Adaptación a cambios (tráfico, normativa, datos) | Costosa y limitada | Natural y esperada |
| Equipo estudiantil (aprendizaje continuo) | Poco flexible ante curva de aprendizaje | Permite mejorar en cada ciclo |
| Retroalimentación del docente/cliente | Solo al final del proyecto | En cada iteración (revisión de sprint) |
| Alineación con la consigna | No coincide con la estructura de 4 iteraciones | Coincide directamente con el cronograma sugerido |

---

## 4. Enfoque Recomendado: Ágil (Scrum Adaptado)

Se recomienda adoptar un enfoque **ágil, basado en Scrum adaptado a un contexto académico**, organizando el trabajo en cuatro sprints equivalentes a las cuatro iteraciones ya definidas en la consigna del proyecto (semanas 1-3, 4-7, 8-11 y 12-14). Esta decisión se sustenta en tres razones principales: primero, el componente algorítmico (metaheurística para VRPTW/Green VRP) requiere ciclos cortos de prueba y ajuste que un modelo secuencial no permite sin retrasar todo el proyecto; segundo, varios requerimientos dependen de información que se obtiene progresivamente, como datos reales de tráfico, restricciones normativas y retroalimentación de conductores simulados; tercero, el propio documento de consigna ya define entregables incrementales por iteración, lo cual es estructuralmente incompatible con un modelo en cascada donde el diseño y la implementación no deberían solaparse.

Un enfoque Waterfall exigiría cerrar por completo el análisis de requerimientos y el diseño de la solución antes de iniciar la implementación, lo cual resulta poco realista dado que el desempeño real del algoritmo de optimización (tiempos de respuesta, calidad de las rutas) solo puede validarse mediante prototipos funcionales, no mediante documentación previa. Por ello, el modelo ágil permite detectar y corregir desviaciones de manera temprana, distribuir la carga de trabajo del equipo estudiantil de forma más realista y presentar avances tangibles en cada revisión académica.

---

## 5. Conclusión

En consecuencia, el enfoque más adecuado para el desarrollo de "EcoLogística Lima" es el **modelo ágil (Scrum adaptado en cuatro sprints)**, por su capacidad de gestionar la incertidumbre técnica del algoritmo de optimización, adaptarse a cambios en los datos y requerimientos, y alinearse de forma natural con el cronograma incremental ya establecido en la consigna del proyecto. El modelo en cascada queda descartado por su rigidez y por el alto riesgo de detectar fallas críticas del algoritmo únicamente al final del ciclo de desarrollo.
