# Changelog

Historial de cambios de los documentos legales de Qipo.

El formato sigue [Keep a Changelog](https://keepachangelog.com/es-ES/1.1.0/) y el versionado sigue [Semantic Versioning](https://semver.org/lang/es/).

Cada documento legal mantiene su propia versión, indicada en la cabecera del archivo.

---

## [Sin publicar]

### Política de Privacidad — v1.0 (lista para publicación tras implementación de Eliminar cuenta)

- Borrador completo — 17 secciones redactadas
- 8 validaciones técnicas y legales cerradas:
  - Hosting confirmado: Contabo GmbH (Alemania) con infraestructura en EE. UU. región US-East. Policy refleja almacenamiento principal en EE. UU., Contabo agregado como Encargado del Tratamiento en sección 6.1, sección 7 reescrita.
  - DPAs disponibles para los 4 proveedores listados (Groq, Google, RevenueCat, Contabo).
  - URLs de políticas de terceros verificadas y vigentes.
  - Base legal "interés legítimo" mantenida para anti-fraude y bug-fixing (decisión ratificada).
  - Período de gracia para eliminación de cuenta: 30 días antes del hard delete.
  - Retención de logs descrita en términos operativos (sin promesa numérica). Tech debt task creada en TickTick para configurar log rotation en docker-compose.prod.yml.
  - Encriptación en reposo descrita honestamente como "controles de acceso del proveedor de hosting". Tech debt task creada en TickTick para LUKS futuro en VPS.
  - Hash de contraseñas confirmado: bcrypt con 10 salt rounds.
- Pendiente: implementación de la funcionalidad "Eliminar cuenta in-app" (bloqueante de Play Store — ver tarea TickTick "Implementar eliminación de cuenta in-app")
- Pendiente: publicación oficial como v1.0 (no draft) cuando se implemente la eliminación in-app

---

## Próximas publicaciones

- Política de Privacidad v1.0 — antes del lanzamiento de Qipo en Google Play Store
- Términos de Servicio v1.0 — antes del lanzamiento de Qipo en Google Play Store
- Política de Devoluciones v1.0 — antes de activar el Plan Pro (Q1 2027)
