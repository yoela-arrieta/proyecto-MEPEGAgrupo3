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
- **[Burbuja]** → simboliza una atmosfera o un entorno seguro donde la salud, los derechos y bienestar de cada peludito están completamente resguardados. 
- **[Pets]** → rinde homenaje a los compañeros incondicionales de nuestra comunidad, reconociendo su valor emocional y garantizando que reciban una atención oportuna, digna y de calidad 
- Juntos, comunican cercanía, compromiso ético y efectivo hacia nuestros peluditos, recalcando nuestra responsabilidad de garantizar un procesamiento transparente y claro.

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


