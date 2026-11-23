# Planificación, ejecución y automatización

[← Gestión documental](09-gestion-documental.md) · [Portada](README.md) · [Implementación y seguridad →](11-implementacion-seguridad.md)

> **Habilidad:** convertir resultados en planes controlables.
> **Aplicaciones:** Planner, Copilot Chat y agentes.
> **Control:** diferencie sugerir acciones de ejecutarlas y mantenga aprobaciones humanas.

> [!IMPORTANT]
> Automatice únicamente después de estabilizar el proceso manual, sus fuentes, sus excepciones y su mecanismo de aprobación.

<details open>
<summary><strong>Ver los 10 prompts</strong></summary>

| # | Prompt listo para usar | Implementación |
|---|---|---|
| 1 | “Convierte `[brief]` en un plan con resultados, hitos, tareas, dependencias, roles, fechas propuestas y riesgos. Marca supuestos.” | Valide capacidad y fechas con el equipo. |
| 2 | “Descompón `[objetivo]` en entregables verificables. Define aceptación, tareas, entrada, salida y dependencia. Evita verbos genéricos.” | Transfiera al plan tras revisar. |
| 3 | “Prioriza estas tareas por impacto, urgencia, esfuerzo, riesgo y dependencia. Explica puntuación y sensibilidad. No modifiques el plan.” | Confirme criterios con el propietario. |
| 4 | “Crea un plan de lanzamiento para `[producto/cambio]`: preparación, comunicación, formación, soporte, métricas, contingencia y reversión.” | Revise con áreas implicadas. |
| 5 | “Genera un registro de riesgos con causa, evento, impacto, probabilidad, señal, mitigación y rol propietario. Separa hechos de supuestos.” | Valide probabilidades y responsables. |
| 6 | “Diseña un plan 30-60-90 para `[rol/iniciativa]` con resultados, actividades, métricas, dependencias y revisiones.” | Úselo como borrador acordable. |
| 7 | “Resume el estado de `[plan]`: completado, en curso, bloqueado, atrasado y próximo. Incluye causa, impacto y decisión necesaria.” | Confirme que las tareas estén actualizadas. |
| 8 | “Evalúa si `[proceso]` necesita un agente. Describe usuario, objetivo, fuentes, acciones, permisos, límites, aprobaciones y métricas.” | No cree un agente si basta un prompt. |
| 9 | “Redacta instrucciones para un agente de `[función]`: alcance, fuentes, pasos, formato, rechazo, escalamiento y aprobaciones.” | Pruebe casos válidos y adversos. |
| 10 | “Crea pruebas para `[agente]`: casos normales, datos faltantes, permisos insuficientes, instrucciones maliciosas, fallo de fuente y rechazo.” | No publique sin pruebas y observabilidad. |

</details>

---

[← Gestión documental](09-gestion-documental.md) · [Portada](README.md) · [Siguiente: Implementación y seguridad →](11-implementacion-seguridad.md)
