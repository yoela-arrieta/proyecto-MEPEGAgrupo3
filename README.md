# 🐾 (burbuja pets)

![Logo](images/logo.png)

**Universidad de Antioquia — Facultad de Ingeniería**
**Departamento de Ingeniería Industrial**
**Curso: Algoritmia y Programación 2026-2**
**Profesor:** Victor Hugo Mercado Ramos

---

## 📋 Tabla de Contenido

1. [Integrantes](#1--integrantes)
2. [Vínculos Académicos y Descripción](#2--vínculos-académicos-y-descripción)
3. [Nombre del Proyecto y Detalles](#3--nombre-del-proyecto-y-detalles)
4. [Licencia del Software](#4--licencia-del-software)
5. [Reporte de Visión](#5--reporte-de-visión)
6. [Especificación de Requisitos](#6--especificación-de-requisitos)
7. [Plan de Proyecto](#7--plan-de-proyecto)

---

## 1. 👥 Integrantes

| # | Nombre completo | Cédula | Correo institucional | Rol |
|---|-----------------|--------|----------------------|-----|
| 1 | erika hernandez galvan | 1014244005 | erika.hernandezg@udea.edu.co | Líder / Desarrollador |
| 2 | yanidi yoela arrieta requeme | 1001159651 | yoela.arrieta@udea.edu.co | Desarrollador Backend |
| 3 | darci vanessa londoño ortiz | 1001617038 | dvanessa.londono@udea.edu.co | QA / Validaciones |
| 4 | lorena isabel orrego sierra | 1007942416 | lorena.orrego@udea.edu.co | Documentación |

---

## 2. 🎓 Vínculos Académicos y Descripción

Todos los integrantes pertenecemos al programa de **Ingeniería Industrial** de la Universidad de Antioquia.

### erika hernandez galvan — Líder del proyecto
- **Programa:** Ingeniería Industrial
- **Habilidades:** [ingresar habilidades].
- **Fortalezas:**[ingresar fortalezas].

### yanidi yoela arrieta requeme — Desarrollador Backend
- **Programa:** Ingeniería Industrial
- **Habilidades:** [ingresar habilidades]..
- **Fortalezas:** [ingresar fortalezas].

### darci vannesa londoño ortiz — QA / Validaciones
- **Programa:** Ingeniería Industrial
- **Habilidades:** [ingresar habilidades].
- **Fortalezas:**[ingresar fortalezas].

### lorena isabel orrego sierra — Documentación
- **Programa:** Ingeniería Industrial
- **Habilidades:**[ingresar habilidades].
- **Fortalezas:**[ingresar fortalezas].

---

## 3. 🏷️ Nombre del Proyecto y Detalles

### Nombre
**burbuja pets**

### Eslogan
*"[agregar eslogan]"*

### Logo
![Logo](images/logo.png)

### Descripción breve
**burbuja pets** es un sistema de consola desarrollado en Python que permite gestionar las Peticiones, Quejas, Reclamos y Sugerencias (PQRS) relacionadas con la atención veterinaria de perros y gatos en los campus de la Universidad de Antioquia, en apoyo al grupo estudiantil MEPEGA.

### ¿Por qué este nombre?
- **[Burbuja]** → hace referencia a un entorno seguro donde la salud, los derechos y bienestar de nuestros peluditos están completamente resguardados.
- **[Pets]** → rinde homenaje a los compañeros incondicionales, reconociendo su valor emocional y garantizando que reciban una atención oportuna, integral  y de calidad. 
- Juntos, comunican cercanía, protección y cuidado integral que recalca nuestro compromiso con la trasparencia y claridad en los procedimientos dados para beneficiar a nuestros peluditos.

----

## 4. 📜 Licencia del Software

Este proyecto se distribuye bajo la licencia:

### **Creative Commons Atribución-NoComercial-CompartirIgual 4.0 Internacional (CC BY-NC-SA 4.0)**

**Resumen de la licencia:**

| Icono | Permiso | Descripción |
|-------|---------|-------------|
| ✅ | Compartir | Copiar y redistribuir el material en cualquier medio o formato. |
| ✅ | Adaptar | Remezclar, transformar y construir a partir del material. |
| ⚠️ | Atribución | Debes dar crédito al autor original. |
| ⚠️ | NoComercial | No puedes usar el material con fines comerciales. |
| ⚠️ | CompartirIgual | Si transformas el material, debes distribuirlo bajo la misma licencia. |

🔗 **Enlace oficial:** https://creativecommons.org/licenses/by-nc-sa/4.0/

### Cómo citar este proyecto:
> erika hernadez,yanidi yoela arrieta,darci vannesa londoño,lorena isabel orrego . (2026). burbuja pets: Gestor de PQRS para la atención veterinaria de MEPEGA. Universidad de Antioquia. Licencia CC BY-NC-SA 4.0.

### Justificación de la licencia

Se eligió **CC BY-NC-SA 4.0** por las siguientes razones:

**Justificación legal:**
- Es una licencia reconocida internacionalmente (Creative Commons).
- Protege la autoría del equipo mediante la cláusula **BY** (Atribución).
- Prohíbe el uso comercial (**NC**), coherente con el carácter académico y sin ánimo de lucro del proyecto MEPEGA.
- Obliga a compartir las mejoras bajo la misma licencia (**SA**), fomentando el software libre.

**Justificación técnica:**
- Es compatible con proyectos académicos y de código abierto.
- No impone restricciones incompatibles con el uso educativo.
- Permite la reutilización por parte de otros estudiantes de la UdeA.

**Alternativas descartadas:**
- **MIT / Apache 2.0:** permiten uso comercial, lo cual no es deseable.
- **GPL v3:** es para software puro, no para documentación y contenido mixto.
- **CC0:** elimina la atribución, exponiendo el proyecto al plagio.

----

## 5. 🎯 Reporte de Visión

### 5.1 Descripción general del software

**burbuja pets** es una aplicación de consola desarrollada en **Python** que automatiza la gestión de PQRS (Peticiones, Quejas, Reclamos y Sugerencias) recibidas por el grupo estudiantil **MEPEGA** para la atención de perros y gatos en los campus de la Universidad de Antioquia.

Actualmente, MEPEGA registra las PQRS de forma manual (papel y lápiz), lo cual genera:
- Pérdida de información.
- Duplicidad de radicados.
- Dificultad para hacer seguimiento.
- Ausencia de estadísticas.

**burbuja pets** soluciona estos problemas digitalizando el proceso, validando los datos, generando radicados en formato ASCII y produciendo estadísticas exportables a Power BI.

### 5.2 Objetivos

#### Objetivo general
Desarrollar un sistema de consola en Python que permita gestionar de forma eficiente las PQRS de MEPEGA, garantizando la integridad de los datos, la trazabilidad de cada radicado y la generación de estadísticas.

#### Objetivos específicos
1. Implementar un módulo de autenticación con control de intentos.
2. Validar todos los campos de las PQRS según reglas estrictas.
3. Almacenar los registros en 4 archivos planos independientes por tipo de solicitud.
4. Generar comprobantes de radicado en formato ASCII de 120 caracteres.
5. Permitir la consulta y actualización del estado de las PQRS.
6. Calcular 6 estadísticas clave para la toma de decisiones.
7. Exportar los datos para su visualización en Power BI.

### 5.3 Beneficios

#### Para MEPEGA
- ✅ Reducción del 90% del tiempo de radicación.
- ✅ Eliminación de radicados duplicados.
- ✅ Trazabilidad completa del ciclo de vida de cada PQRS.
- ✅ Alertas automáticas de vencimiento.

#### Para los solicitantes
- ✅ Radicado inmediato con formato profesional.
- ✅ Seguimiento claro del estado de su solicitud.

#### Para la Universidad
- ✅ Estadísticas para la toma de decisiones sobre bienestar animal.
- ✅ Base para futuras integraciones con otros sistemas.

### 5.4 Alcance

El sistema **incluye**:
- Autenticación y control de sesión.
- Registro, consulta y actualización de PQRS.
- Generación de radicados ASCII.
- Estadísticas y exportación a Power BI.

---

---

## 6. 📋 Especificación de Requisitos

### 6.1 Requisitos Funcionales (RF)

| ID | Nombre | Descripción | Prioridad |
|----|--------|-------------|-----------|
| RF-01 | Autenticación | El sistema debe permitir el ingreso con usuario y contraseña validados contra `usuarios.txt`. | Alta |
| RF-02 | Control de intentos | Tras 3 intentos fallidos, la cuenta se bloquea 30 segundos. | Alta |
| RF-03 | Registrar PQRS | El sistema debe permitir registrar PQRS con todos los campos validados. | Alta |
| RF-04 | Validar datos del solicitante | Validar nombre, documento, teléfono, correo y dirección según reglas. | Alta |
| RF-05 | Validar información PQRS | Validar tipo, fecha, canal, asunto y descripción. | Alta |
| RF-06 | Generar ID auto-incremental | Cada tipo de PQRS tendrá su propio contador independiente. | Alta |
| RF-07 | Calcular fecha máxima de respuesta | Fecha de radicación + **15 días calendario** (ajustado). | Alta |
| RF-08 | Estado inicial | Toda PQRS se registra con estado "Registrada". | Alta |
| RF-09 | Flujo de estados | Registrada → En proceso → Solucionada. | Media |
| RF-10 | Imprimir radicado ASCII | Generar comprobante .txt de 120 caracteres por línea. | Alta |
| RF-11 | Gestionar 4 archivos planos | Peticion.txt, Queja.txt, Reclamo.txt, Sugerencia.txt. | Alta |
| RF-12 | Consultar PQRS | Listar registros por tipo de solicitud. | Media |
| RF-13 | Actualizar estado | Cambiar el estado de una PQRS respetando el flujo. | Media |
| RF-14 | Estadísticas | Calcular promedio de días + 5 estadísticas adicionales. | Alta |
| RF-15 | Asignar usuario registrador | Vincular automáticamente el usuario autenticado. | Media |
| RF-16 | Exportar a Power BI | Los archivos planos deben ser legibles por Power BI. | Media |

### 6.1.1 Regla especial: Consecutivo independiente por archivo

Cada tipo de PQRS tiene su **propio contador de ID auto-incremental**, independiente de los demás:

| Archivo | Consecutivo | Ejemplo |
|---------|-------------|---------|
| `Peticion.txt` | 1, 2, 3, 4... | Petición #1, Petición #2 |
| `Queja.txt` | 1, 2, 3, 4... | Queja #1, Queja #2 |
| `Reclamo.txt` | 1, 2, 3, 4... | Reclamo #1, Reclamo #2 |
| `Sugerencia.txt` | 1, 2, 3, 4... | Sugerencia #1, Sugerencia #2 |

**Importante:** No se puede repetir un ID dentro del mismo archivo, pero sí puede existir el mismo número en archivos distintos (Petición #1 y Queja #1 son válidos).

**Implementación:** La función `obtener_siguiente_id()` en `src/archivos.py` lee el último ID del archivo correspondiente y le suma 1.

### 6.2 Requisitos No Funcionales (RNF)

| ID | Nombre | Descripción |
|----|--------|-------------|
| RNF-01 | Lenguaje | Desarrollado en Python 3.8+. |
| RNF-02 | Modularización | Código separado en `validaciones.py`, `archivos.py`, `reportes.py`. |
| RNF-03 | Portabilidad | Debe ejecutarse en Windows, Linux y macOS. |
| RNF-04 | Usabilidad | Interfaz de consola clara, con menús numerados. |
| RNF-05 | Rendimiento | Debe procesar 1000 registros sin demoras perceptibles. |
| RNF-06 | Persistencia | Uso de archivos planos (sin base de datos). |
| RNF-07 | Seguridad | Contraseñas almacenadas en archivo local. |
| RNF-08 | Mantenibilidad | Código comentado y con nombres descriptivos. |
| RNF-09 | Versionado | Uso de Git y GitHub con commits descriptivos. |
| RNF-10 | Documentación | README, manual de usuario y actas. |
| RNF-11 | Formato de radicado | Exactamente 120 caracteres de ancho. |
| RNF-12 | Cumplimiento de plazo | Fecha máxima = +15 días (ajustado por el equipo). |

### 6.3 Matriz de trazabilidad

| Requisito | Módulo | Archivo |
|-----------|--------|---------|
| RF-01, RF-02 | Login | `src/login.py` |
| RF-03 a RF-10 | Registro | `src/main.py` |
| RF-04, RF-05 | Validaciones | `src/validaciones.py` |
| RF-11 | Archivos | `src/archivos.py` |
| RF-12, RF-13 | Consulta/Actualización | `src/main.py` |
| RF-14 | Estadísticas | `src/reportes.py` |

---

## 7. 📅 Plan de Proyecto

### 7.1 Metodología

El proyecto se desarrolla con un enfoque **ágil tipo Scrum**: el docente actúa como *Product Owner* y el equipo trabaja en cuatro fases con reuniones semanales de seguimiento.

| Fase | Periodo | Qué se hace |
|----|--------|-------------|
| 1. Inicio | 16/09 – 23/09 | Análisis del caso, actas, repositorio y requisitos |
| 2. Entrega 1 | 22/09 – 30/09 | Puntos 1 a 7, login y estructura de archivos |
| 3. Desarrollo | 02/10 – 10/11 | Validaciones, registro, radicado, consulta, estados, estadísticas y Power BI |
| 4. Cierre | 04/11 – 18/11 | Pruebas, manual de usuario y entrega final |

### 7.2 Actividades

Cada actividad de desarrollo se relaciona con los requisitos del punto 6 (columna *Requisitos*), para saber qué parte del sistema construye.

| ID | Actividad | Responsable | Requisitos (punto 6) | Inicio | Fin | Horas |
|----|-----------|-------------|----------------------|--------|-----|-------|
| A01 | Lectura del enunciado y análisis del caso MEPEGA | Todo el equipo | — | 16/09 | 17/09 | 4 |
| A02 | Conformación del equipo y actas (entendimiento, colaboración, responsabilidad) | Todo el equipo | — | 17/09 | 19/09 | 6 |
| A03 | Crear repositorio GitHub y estructura src/ docs/ images/ data/ | Erika | RNF-09 | 19/09 | 20/09 | 3 |
| A04 | Entrevista con el PO (docente) y levantamiento de requisitos | Todo el equipo | — | 21/09 | 23/09 | 6 |
| A05 | README: integrantes y vínculos académicos (puntos 1 y 2) | Erika | — | 22/09 | 24/09 | 5 |
| A06 | Nombre (Burbuja Pets), logo y tipografía (punto 3) | Yanidi | — | 22/09 | 26/09 | 10 |
| A07 | Definir la licencia del software (punto 4) | Lorena | — | 24/09 | 24/09 | 3 |
| A08 | Reporte de visión (punto 5) | Lorena | — | 23/09 | 26/09 | 6 |
| A09 | Especificación de requisitos (punto 6) | Darci y Erika | RF-01 a RF-16 | 23/09 | 28/09 | 10 |
| A10 | Plan de proyecto: actividades, Gantt y presupuesto (punto 7) | Darci | — | 25/09 | 29/09 | 6 |
| A11 | Módulo de login CLI y captura del usuario registrador | Erika | RF-01, RF-02, RF-15 | 22/09 | 29/09 | 12 |
| A12 | Estructura de archivos planos, lectura de BD origen y ID consecutivo | Yanidi | RF-06, RF-11 | 24/09 | 29/09 | 8 |
| A13 | Armar el PDF final (puntos 1 a 7) y el .zip de la entrega | Lorena | — | 29/09 | 30/09 | 7 |
| A14 | Funciones de validación de datos | Darci | RF-04, RF-05 | 02/10 | 09/10 | 12 |
| A15 | Registrar PQRS y escritura en los 4 archivos planos | Erika y Yanidi | RF-03, RF-07, RF-08 | 05/10 | 16/10 | 20 |
| A16 | Imprimir radicado TXT de 120 caracteres | Yanidi | RF-10 | 13/10 | 20/10 | 10 |
| A17 | Consultar PQRS | Erika | RF-12 | 19/10 | 23/10 | 6 |
| A18 | Registrar cambio de estado de la PQRS | Yanidi y Lorena | RF-09, RF-13 | 21/10 | 28/10 | 8 |
| A19 | Estadísticas y exportación de resultados | Darci | RF-14 | 26/10 | 03/11 | 4 |
| A20 | Dashboard e informe en Power BI (mínimo 3 páginas) | Darci y Lorena | RF-16 | 29/10 | 10/11 | 20 |
| A21 | Pruebas integrales y corrección de errores | Todo el equipo | RNF-03, RNF-05, RNF-11 | 04/11 | 11/11 | 16 |
| A22 | Manual de usuario (docs/) y plan de versionado | Lorena | RNF-10 | 06/11 | 12/11 | 12 |
| A23 | Entrega final (una semana antes de la sustentación) | Erika | — | 11/11 | 11/11 | 6 |
| | **Total** | | | | | **200** |

### 7.3 Cronograma (Diagrama de Gantt)

![Diagrama de Gantt](images/gantt_proyecto.png)

**Hitos:**

| Hito | Descripción | Fecha |
|----|-------------|-------|
| H1 | Entrega 1 (puntos 1 a 7) en la plataforma | 30/09/2026 |
| H2 | Sustentación de la Entrega 1 | 01/10/2026 |
| H3 | Programa completo entregado para revisión | 11/11/2026 |
| H4 | Entrega 2 y sustentación final (semana 16) | 18/11/2026 |

### 7.4 Presupuesto

El presupuesto no se paga en dinero sino en **tiempo de práctica de formación**, valorado a **1 SMLV** de práctica profesional.

| Concepto | Valor | Cálculo |
|----|--------|-------------|
| SMLV 2026 | $1.750.905 | Decreto de salario mínimo 2026 |
| Horas laborales al mes | 210 | Jornada de 42 h/semana (Ley 2101 de 2021) |
| Valor hora | $8.337,64 | $1.750.905 ÷ 210 |
| Horas del equipo | 200 | 4 integrantes × 50 horas |
| **Costo total** | **$1.667.529** | 200 h × $8.337,64 ≈ 0,95 SMLV |

**Distribución por fase:**

| Fase | Horas | Costo | % |
|----|--------|-------------|----|
| 1. Inicio | 19 | $158.415 | 9,5 % |
| 2. Entrega 1 | 67 | $558.622 | 33,5 % |
| 3. Desarrollo | 80 | $667.011 | 40,0 % |
| 4. Cierre | 34 | $283.480 | 17,0 % |
| **Total** | **200** | **$1.667.529** | **100 %** |

**Recursos sin costo:** Python 3 y VS Code (software libre), GitHub (cuenta UdeA), Power BI Desktop (gratuito), computadores e internet de las integrantes.


