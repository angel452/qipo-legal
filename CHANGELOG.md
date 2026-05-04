# Changelog

Historial de cambios de los documentos legales de Qipo.

El formato sigue [Keep a Changelog](https://keepachangelog.com/es-ES/1.1.0/) y el versionado sigue [Semantic Versioning](https://semver.org/lang/es/).

Cada documento legal mantiene su propia versión, indicada en la cabecera del archivo.

---

## [Sin publicar]

### Política de Privacidad — v1.0 (lista para publicación tras implementación de Eliminar cuenta)

- Borrador completo — 17 secciones redactadas en registro jurídico formal (tratamiento de "Usted", terminología técnico-legal, sin emojis ni énfasis dramático).
- Estructura terminológica unificada: Responsable, Encargado, Titular, Usuario, Aplicación, Cuenta, Datos Personales, Tratamiento.
- Eliminada la sección 3.3 ("Lo que NO recolectamos") por considerar que crea obligación negativa explícita innecesaria desde la perspectiva jurídica peruana, donde el principio rector es declarar lo que se trata.
- 8 validaciones técnicas y legales cerradas:
  - Hosting confirmado: Contabo GmbH (Alemania) con infraestructura en EE. UU. región US-East. Política refleja almacenamiento principal en EE. UU., Contabo identificado como Encargado del Tratamiento en Cláusula 6.1, Cláusula 7 reescrita.
  - Acuerdos de Procesamiento de Datos disponibles para los cuatro Encargados listados (Groq, Google, RevenueCat, Contabo).
  - URLs de políticas de terceros verificadas y vigentes.
  - Base legal "interés legítimo" mantenida para prevención de fraude y mantenimiento operativo (decisión ratificada).
  - Período de gracia para eliminación de Cuenta: treinta (30) días antes de la supresión irreversible.
  - Conservación de registros técnicos descrita en términos operativos. Tarea técnica pendiente para configurar rotación de logs en docker-compose.prod.yml.
  - Protección de Datos Personales en reposo descrita conforme a los controles de acceso del Encargado de hosting. Tarea técnica pendiente para configurar disk encryption (LUKS) en VPS.
  - Algoritmo de hashing de contraseñas confirmado: bcrypt con 10 salt rounds.
- Pendiente: implementación de la funcionalidad "Eliminar Cuenta" desde la Aplicación (requisito de Google Play Store).
- Pendiente: publicación oficial como v1.0 (no borrador) una vez implementada la funcionalidad de eliminación de Cuenta.

---

### Términos de Servicio — v1.0 (en redacción)

- Borrador inicial completo — 19 cláusulas redactadas en registro jurídico formal.
- Cubre: identificación del Proveedor, definiciones, descripción del Servicio, registro y Cuenta, modalidades de uso (Plan Gratuito y Plan Pro), Suscripción al Plan Pro, conducta del Usuario, propiedad intelectual, protección de Datos Personales (referencia a la Política de Privacidad), modificaciones a la Aplicación, suspensión y terminación de la Cuenta, garantías y limitación de responsabilidad, indemnización, caso fortuito y fuerza mayor, modificaciones a los Términos, disposiciones varias, ley aplicable y jurisdicción, comunicaciones, vigencia.
- Cláusulas distintivas para una aplicación de finanzas personales: declaración expresa de que la Aplicación no constituye asesoramiento financiero, contable, tributario ni de inversión (Cláusulas 3.2 y 12.3); prohibición de uso comercial no autorizado y de extracción automatizada de información (Cláusula 7.2).
- Limitación cuantitativa de responsabilidad acotada al monto pagado en los doce (12) meses anteriores, que para Usuarios del Plan Gratuito asciende a cero.
- Pendiente: publicación oficial como v1.0 (no borrador) cuando se publique la Aplicación.

### Política de Devoluciones — v1.0 (redacción anticipada)

- Borrador inicial completo — 10 cláusulas redactadas en registro jurídico formal.
- Aplicabilidad anticipada: la Política aplica únicamente cuando se active el Plan Pro (previsto para el primer trimestre de 2027). Banner explícito al inicio del documento aclarando el carácter anticipado.
- Estructura: identificación del Proveedor, aplicabilidad, política aplicable según canal de pago (con énfasis en Google Play Billing), período de retracto de catorce (14) días, procedimiento de reembolso (vía Google Play recomendada y vía contacto directo subsidiaria), plazo de respuesta y procesamiento, distinción entre cancelación y solicitud de reembolso, modificaciones, comunicaciones, vigencia.
- Pendiente: publicación oficial como v1.0 (no borrador) cuando se active el Plan Pro y al momento de la habilitación de canales de pago adicionales.

---

## Próximas publicaciones

- Política de Privacidad v1.0 — antes del lanzamiento de Qipo en Google Play Store, una vez implementada la funcionalidad de eliminación de Cuenta desde la Aplicación.
- Términos de Servicio v1.0 — antes del lanzamiento de Qipo en Google Play Store.
- Política de Devoluciones v1.0 — antes de activar el Plan Pro (previsto para el primer trimestre de 2027).
