# Sistema editorial Markdown

[← Volver al repositorio](../README.md)

Este sistema mantiene una apariencia profesional y consistente en GitHub, visores Markdown e intranets compatibles, sin depender de CSS personalizado.

## Principios

| Principio | Aplicación |
|---|---|
| Jerarquía visible | Un solo `H1`, secciones `H2` y fichas `H3` |
| Lectura progresiva | Resumen primero; detalle técnico después |
| Reconocimiento | Tablas, etiquetas y plantillas en lugar de párrafos densos |
| Acción clara | Cada página indica qué hacer, qué revisar y adónde continuar |
| Seguridad visible | Riesgos y aprobaciones aparecen junto al contenido aplicable |

## Componentes

### Aviso informativo

```markdown
> [!NOTE]
> Información de contexto que ayuda a interpretar la página.
```

### Recomendación

```markdown
> [!TIP]
> Acción concreta que mejora el resultado.
```

### Control obligatorio

```markdown
> [!WARNING]
> Riesgo o revisión humana que no debe omitirse.
```

### Prompt copiable

````markdown
```text
[Prompt listo para utilizar]
```
````

### Detalle desplegable

```html
<details>
<summary><strong>Ver implementación</strong></summary>

Contenido secundario.

</details>
```

### Navegación local

```markdown
[← Anterior](...) · [↑ Inicio](...) · [Siguiente →](...)
```

## Reglas visuales

- Utilice negrita para etiquetas breves, no para párrafos completos.
- Reserve los bloques de código para contenido que el lector debe copiar.
- Limite las tablas a información comparable.
- Use avisos con moderación: uno o dos por sección importante.
- Mantenga iconos y colores en badges, no en cada título.
- No dependa de HTML complejo: algunas intranets lo eliminan.
- Nunca oculte una advertencia crítica dentro de un bloque plegado.
