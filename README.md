# qipo-legal

Documentos legales de Qipo, aplicación móvil de finanzas personales.

Este repositorio se publica como sitio estático mediante GitHub Pages en:
`https://angel452.github.io/qipo-legal/`

## Estructura

| Archivo | URL pública | Estado |
|---|---|---|
| `privacy/index.md` | `/privacy/` | Borrador en redacción |
| `terms/index.md` | `/terms/` | Pendiente |
| `refund/index.md` | `/refund/` | Pendiente |
| `index.md` | `/` | Landing |
| `CHANGELOG.md` | — | Historial de versiones de cada documento |

## Cómo hacer cambios

1. Editá el archivo `.md` correspondiente.
2. Bumpeá la versión y la fecha de vigencia en la cabecera del documento.
3. Anotá el cambio en `CHANGELOG.md`.
4. Commit con mensaje convencional (`docs(privacy): ...`).
5. Push a `main`. GitHub Pages republica en ~1 minuto.

## Reglas

- Cualquier cambio en la **Política de Privacidad** debe estar reflejado **antes** del cambio efectivo en la app o el backend. Nunca al revés.
- Cualquier cambio que implique nuevos terceros, nuevas categorías de datos o nuevos usos requiere bumpeo de versión mayor (ej: 1.0 → 2.0) y notificación a usuarios.
- Cambios de redacción que no alteran el sentido bumpean versión menor (ej: 1.0 → 1.1).
