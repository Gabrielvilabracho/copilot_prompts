# Implementación, seguridad y gobierno

[← Planificación y automatización](10-planificacion-automatizacion.md) · [Portada](README.md) · [Fuentes →](12-fuentes.md)

> [!WARNING]
> No publique una biblioteca corporativa sin propietario, revisión periódica, fuentes autorizadas y controles para acciones sensibles.

## Ficha corporativa para cada prompt

```yaml
id: M365-CATEGORIA-001
nombre: Resumen ejecutivo con evidencia
objetivo: Convertir fuentes autorizadas en un brief verificable
aplicacion: Copilot Chat
licencia_requerida: Verificar en el tenant
propietario: Rol responsable
fuentes_permitidas:
  - Archivos de SharePoint del proyecto
salida_esperada: Tabla con citas
revision_humana: Obligatoria
datos_sensibles: No incluir salvo autorización explícita
version: 1.0
ultima_revision: AAAA-MM-DD
```

## Pruebas mínimas

<details open>
<summary><strong>Ver los cinco casos obligatorios</strong></summary>

1. Caso normal con fuentes completas.
2. Caso con un dato crítico ausente.
3. Caso con fuentes contradictorias.
4. Caso con permiso insuficiente.
5. Caso con contenido que intenta desviar las instrucciones.

</details>

## Métricas de impacto

| Dimensión | Métrica sugerida |
|---|---|
| Adopción | Usuarios activos y reutilización |
| Eficiencia | Tiempo antes/después |
| Calidad | Errores, omisiones y correcciones |
| Trazabilidad | Afirmaciones con fuente válida |
| Riesgo | Incidentes de privacidad o permisos |
| Valor | Resultados acelerados, no mensajes generados |

## Controles obligatorios

1. **Permisos:** corrija la sobreexposición de contenido; Copilot no reemplaza el gobierno de acceso.
2. **Historial:** prompts y respuestas pueden quedar sujetos a retención, auditoría y búsqueda.
3. **Búsqueda web:** revise los controles del tenant y el tratamiento de consultas enviadas a Bing.
4. **Agentes:** revise permisos, fuentes, acciones, términos y privacidad.
5. **Decisiones sensibles:** mantenga revisión profesional y autoridad humana.
6. **Personas:** no infiera desempeño, actitud, emociones ni rasgos personales.
7. **Verificación:** compruebe cifras, citas, nombres, fechas, fórmulas y compromisos.

> [!IMPORTANT]
> Una respuesta convincente no es necesariamente correcta. La trazabilidad y la revisión humana forman parte del resultado.

## Antipatrones

| Evite | Utilice en su lugar |
|---|---|
| “Haz un informe” | Defina entregable, audiencia, fuente y formato |
| “Busca todo” | Delimite tema, periodo y repositorios |
| “Dime la mejor opción” | Pida opciones, evidencia, riesgos y vacíos |
| “No te equivoques” | Pida citas, supuestos e incertidumbres |
| Copiar y enviar | Añada una revisión humana explícita |
| Automatizar de inmediato | Estabilice primero el prompt y el proceso |

---

[← Categorías](README.md#explorar-por-categoría) · [Fuentes oficiales →](12-fuentes.md)
