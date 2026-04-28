# Actividad: Propuesta de Práctica Temática Pequeña (Enfoque en Documentación)

## 1) Título de la Práctica

**Diseña el título de tu práctica temática.**

Tu título debe ser corto, claro y describir el tipo de solución que propones.

Ejemplos de título:
- **Mini Toolkit en ARM64**
- **Asistente de Estudio en Terminal**
- **Reporteador de Información del Sistema**
- **Organizador de Archivos**
- **Juego de Aprendizaje en Línea de Comandos**

> Escribe aquí tu título final: `______________________________`

---

## 2) Descripción General

En esta actividad **no se espera un proyecto grande**. Tu objetivo es **diseñar y documentar** una propuesta de práctica temática pequeña que pueda desarrollarse en poco tiempo y con herramientas básicas.

Debes elegir **un lenguaje principal** para tu propuesta:
- ARM64 Assembly
- C
- Python
- Bash

### Restricción importante por lenguaje
- Si eliges **ARM64 Assembly**, se recomienda que sea para programas **muy pequeños** (por ejemplo: utilidades mínimas de terminal, operaciones simples, lectura de argumentos muy básica).

### Prioridad de la actividad
Antes de escribir mucho código, debes:
1. Definir claramente el problema o necesidad.
2. Justificar por qué tu idea es útil y viable.
3. Planear estructura del repositorio y pruebas.
4. Documentar decisiones técnicas.

> Esta actividad evalúa principalmente **calidad de documentación, planeación y claridad técnica**.

---

## 3) Objetivo de Aprendizaje

Al terminar esta actividad, serás capaz de:
- Proponer una práctica de sistemas pequeña con alcance realista.
- Justificar decisiones técnicas según el lenguaje elegido.
- Diseñar la estructura de un repositorio académico para GitHub Classroom.
- Definir un plan de pruebas básico y verificable.

---

## 4) Alcance y Restricciones del Proyecto

Tu propuesta debe ser de **alcance pequeño**.

### Sí permitido
- Programas de terminal.
- Lectura/escritura de archivos simples.
- Procesamiento básico de texto.
- Scripts de automatización local.
- Lógica modular sencilla.

### No permitido (para esta práctica)
- Frameworks grandes.
- APIs pagadas.
- Bases de datos relacionales o no relacionales.
- Infraestructura en la nube.
- Contenedores (Docker, Kubernetes, etc.).
- Dependencias complejas o difíciles de instalar.

> Piensa en una práctica que pueda desarrollarse con herramientas gratuitas y limitadas de IA (por ejemplo, uso básico de Codex o alternativas con cuotas).

---

## 5) Entregables del Estudiante

Tu repositorio debe incluir **como mínimo**:
- `README.md`
- `docs/propuesta.md`
- `docs/caso_de_uso.md`
- `docs/estructura_repositorio.md`
- `docs/plan_de_pruebas.md`

Carpetas opcionales (si decides incluir prototipo o pruebas):
- `src/`
- `scripts/`
- `tests/`

---

## 6) Estructura Recomendada del Repositorio

Usa esta estructura base como referencia:

```text
nombre-del-proyecto/
├── README.md
├── docs/
│   ├── propuesta.md
│   ├── caso_de_uso.md
│   ├── estructura_repositorio.md
│   └── plan_de_pruebas.md
├── src/
│   └── main.<ext>
├── scripts/
│   └── run.sh
└── tests/
    └── test_plan.md
```

> Puedes ajustar esta estructura si lo justificas en `docs/estructura_repositorio.md`.

---

## 7) Guía de Contenido por Archivo

### `README.md`
Debe incluir:
1. Título del proyecto.
2. Resumen de 5–8 líneas.
3. Lenguaje principal elegido y justificación breve.
4. Instrucciones mínimas para ejecutar (aunque sea prototipo).
5. Estado del proyecto (propuesta, prototipo inicial, etc.).

### `docs/propuesta.md`
Debe incluir:
1. Nombre de la práctica.
2. Problema que resuelve.
3. Público objetivo o usuario principal.
4. Funcionalidades planeadas (lista corta, priorizada).
5. Alcance: qué sí incluye y qué queda fuera.
6. Justificación técnica del lenguaje elegido.
7. Riesgos técnicos (mínimo 2) y mitigaciones.

### `docs/caso_de_uso.md`
Debe incluir:
1. Escenario de uso realista.
2. Actor principal.
3. Entrada esperada.
4. Flujo principal paso a paso.
5. Resultado esperado.
6. Al menos un flujo alterno o caso de error.

### `docs/estructura_repositorio.md`
Debe incluir:
1. Árbol de carpetas propuesto.
2. Propósito de cada carpeta/archivo.
3. Convenciones de nombres (archivos, scripts, funciones).
4. Estrategia básica de modularidad.

### `docs/plan_de_pruebas.md`
Debe incluir:
1. Objetivo de pruebas.
2. Lista de casos de prueba (mínimo 5).
3. Para cada caso: entrada, procedimiento, resultado esperado.
4. Criterios de aceptación mínimos.
5. Limitaciones conocidas de las pruebas.

---

## 8) Plantilla sugerida para `docs/propuesta.md`

Copia y completa:

```markdown
# Propuesta de Proyecto

## 1. Nombre

## 2. Lenguaje principal elegido
- [ ] ARM64 Assembly
- [ ] C
- [ ] Python
- [ ] Bash

## 3. Problema que se busca resolver

## 4. Caso de uso principal

## 5. Funcionalidades planeadas (prioridad alta/media/baja)
- Funcionalidad 1:
- Funcionalidad 2:
- Funcionalidad 3:

## 6. Alcance
### Incluye
-
### No incluye
-

## 7. Justificación técnica

## 8. Riesgos y mitigaciones
- Riesgo 1:
  - Mitigación:
- Riesgo 2:
  - Mitigación:

## 9. Estimación de esfuerzo (breve)

## 10. Criterios de éxito
```

---

## 9) Criterios de Evaluación (Rúbrica sugerida)

Puntaje total: **100 puntos**

1. **Claridad y viabilidad de la propuesta (25 pts)**
   - Problema bien definido.
   - Alcance realista y pequeño.

2. **Calidad de documentación (30 pts)**
   - Redacción técnica clara.
   - Buena estructura en `docs/`.
   - Justificaciones completas.

3. **Diseño del repositorio (20 pts)**
   - Organización coherente.
   - Nombres claros y consistentes.

4. **Plan de pruebas (15 pts)**
   - Casos suficientes y verificables.
   - Criterios de aceptación medibles.

5. **Coherencia global de la propuesta (10 pts)**
   - Alineación entre problema, solución y pruebas.

---

## 10) Recomendaciones de Tema (Proyectos pequeños)

Puedes basarte en alguna de estas ideas:
- Validador de estructura de directorios para tareas.
- Generador de resumen de archivos de texto en terminal.
- Script para organizar archivos por extensión.
- Mini agenda de estudio en archivos planos.
- Herramienta CLI para practicar comandos básicos (quiz local).

---

## 11) Instrucciones de Entrega

1. Crea tu repositorio desde GitHub Classroom.
2. Agrega la estructura mínima solicitada.
3. Completa todos los archivos obligatorios.
4. Realiza al menos un commit por etapa (propuesta, caso de uso, pruebas).
5. Verifica ortografía técnica y consistencia.
6. Entrega dentro de la fecha indicada por el docente.

---

## 12) Checklist de Autoevaluación (Estudiante)

Marca cada punto antes de entregar:

- [ ] Elegí un lenguaje principal y lo justifiqué.
- [ ] Mi proyecto es pequeño y factible.
- [ ] Expliqué claramente el caso de uso.
- [ ] Definí estructura del repositorio con propósito por archivo.
- [ ] Incluí al menos 5 casos de prueba con resultados esperados.
- [ ] Evité dependencias complejas y tecnologías fuera del alcance.
- [ ] Mi documentación es clara, ordenada y consistente.

---

## 13) Nota final para estudiantes

Esta actividad está diseñada para fortalecer tu capacidad de **pensar como ingeniero/a de sistemas antes de programar**: definir problema, justificar decisiones, planear pruebas y comunicar con precisión. Un proyecto pequeño y bien documentado vale más que uno grande e incompleto.
