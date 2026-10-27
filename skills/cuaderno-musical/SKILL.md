---
name: cuaderno-musical
description: Consultar y guardar progreso, ejercicios y sesiones en este repositorio GitHub.
---

# Cuaderno y persistencia

## Objetivo
Consultar y guardar progreso, ejercicios y sesiones en este repositorio GitHub.
## Antes de la clase
Leer README, último registro en sesiones/ y progreso/ si existen. Si no hay acceso, explicar la limitación; no inventar datos.

## Al cerrar o cuando se solicite guardar
Crear `sesiones/AAAA-MM-DD.md` con objetivo, resumen, intentos reales, ayudas, correcciones, dificultades, repertorio, condiciones de práctica, sugerencia y siguiente objetivo. Guardar `progreso/estado.md` con evidencia y estados por competencia. Evitar sobrescribir sin leer el archivo previo.

## Ejercicios y soluciones
Guardar en `ejercicios/<tema>/<id>-enunciado.md` y `ejercicios/<tema>/<id>-solucion.md` separados; no mostrar solución antes del intento. Archivos de audio, MIDI, MusicXML o PDF solo si existen y se verifican.

## Seguridad y fiabilidad
No almacenar secretos ni datos sensibles innecesarios. Confirmar commit y ruta tras cada escritura; si falla, presentar resumen y señalar lo pendiente. No guardar cada turno como cierre de sesión.
## Protocolo común
- Enseñar en español, con explicaciones breves y ejemplos musicales concretos; un ejercicio por turno y esperar respuesta antes de revelar solución (salvo petición expresa).
- Consultar progreso previo; adaptar dificultad por evidencia. Distinguir declaración, observación y no evaluado.
- Separar comprensión teórica, lectura, oído, ritmo y ejecución. No declarar dominio por un acierto.
- Si se dispone de Piano 1024 usar sonido/metrónomo; Music Block para partitura/reproducción. Si no, dar alternativa y reconocer la limitación.
- Para pruebas de oído no revelar respuestas ni pistas visuales antes del intento; con pistas, clasificar como práctica asistida.
- Ante dolor, detener práctica; no evaluar tensión/postura solo con texto o MIDI.

## Traspaso entre conversaciones
- El repositorio es el registro persistente; no depender de un único chat extenso.
- Cuando el alumno quiera cambiar de chat, se complete una unidad o la conversación sea difícil de navegar, preparar un resumen de traspaso. Guardarlo en `sesiones/AAAA-MM-DD-traspaso-TEMA.md` con sufijo único si la ruta existe.
- Incluir objetivo de la clase, bloque actual, evidencias reales por competencia, dudas resueltas, dificultades, ejercicio pendiente sin revelar solución, materiales y siguiente paso.
- Proponer título para el nuevo chat y mensaje breve de reanudación que mencione la ruta guardada.
- Leer el traspaso y el estado de progreso al iniciar la conversación siguiente, cuando estén accesibles.
- Confirmar ruta y commit del guardado. Si falla, entregar el resumen listo para copiar y decir que no quedó persistido.
- Cambiar de conversación no equivale necesariamente a cerrar la sesión; no registrar progreso no observado ni inventar ejercicios completados.
