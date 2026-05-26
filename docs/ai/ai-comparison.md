# Comparativa entre ChatGPT y Claude

## Objetivo

En este documento se comparan distintos asistentes de inteligencia artificial aplicados al desarrollo de software.

---

# Explicaciones técnicas

## Concepto: Closures

### ChatGPT
Explicó el concepto de closures utilizando ejemplos sencillos y fáciles de entender. Mostró cómo una función interna puede acceder a variables externas incluso después de ejecutarse.

### Claude
Claude ofreció una explicación más teórica y detallada, explicando el scope léxico y el funcionamiento interno de JavaScript.

### Conclusión
ChatGPT fue más claro para principiantes mientras que Claude fue más técnico.

---

## Concepto: Event Loop

### ChatGPT
Mostró ejemplos usando setTimeout y explicó la cola de eventos paso a paso.

### Claude
Explicó mejor la arquitectura interna del motor JavaScript y la relación entre call stack y callback queue.

### Conclusión
Claude fue más profundo técnicamente.

---

# Detección de errores

## Código con error

```js
function suma(a, b) {
  return a - b;
}ChatGPT

Detectó rápidamente que el operador era incorrecto.

Claude

Detectó el mismo error y además explicó posibles consecuencias en producción.
Resultado ChatGPT
function filtrarCompletadas(tareas) {
  return tareas.filter(t => t.completada);
}
Resultado Claude
function filtrarCompletadas(tareas) {
  return tareas.filter((tarea) => tarea.completada === true);
}