# Guía de contribución FUNCIENCIAS

## Flujo base

1. Trabajar en una rama corta y descriptiva: `feat/...`, `fix/...`, `docs/...`, `ci/...`.
2. Abrir pull request hacia `main`.
3. Incluir evidencia de verificación en el PR.
4. No hacer merge si el build o la revisión básica fallan.

## Convención de commits

Usar Conventional Commits:

```txt
feat: nueva funcionalidad
fix: corrección de bug
docs: documentación
ci: workflows/configuración CI
chore: mantenimiento
perf: rendimiento
```

## Seguridad

Nunca commitear:

- Tokens o claves API.
- Archivos `.env`.
- Credenciales de Firebase/GitHub/servicios externos.
- Datos personales no autorizados.

## Separación por repositorio

- `*-product-specifications`: estrategia y definición de producto.
- `*-product-spec`: especificación funcional/técnica construible.
- `*-product-code`: implementación, releases y despliegue.
- `web-site-funciencias`: sitio institucional.
