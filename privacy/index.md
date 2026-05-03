---
title: Política de Privacidad — Qipo
---

# Política de Privacidad de Qipo

> ⚠️ **Documento en construcción — DRAFT.**
>
> Esta política aún no está vigente. La versión final será publicada antes del lanzamiento de Qipo en Google Play Store. No representa compromiso legal hasta su publicación oficial como versión 1.0.

**Versión:** 1.0-draft  
**Fecha de redacción:** 3 de mayo de 2026  
**Vigencia:** pendiente de publicación oficial

---

## 1. Introducción

### 1.1 Quiénes somos

Qipo es una aplicación móvil de finanzas personales pensada para ayudarte a registrar y entender tus gastos en menos de 10 segundos. La desarrolla y opera **Angel Josue Loayza Huarachi**, persona natural domiciliada en Perú ("Qipo", "nosotros", "nuestro").

Esta política aplica a la aplicación móvil Qipo distribuida a través de Google Play Store, y a los servicios de backend que dan soporte al funcionamiento de la app.

### 1.2 Qué cubre esta política

Esta política te explica:

- Qué datos personales recolectamos y por qué.
- Cómo los usamos.
- Con quién los compartimos.
- Qué derechos tenés sobre tus datos y cómo ejercerlos.
- Cómo nos podés contactar.

Cumple con la **Ley N.º 29733 — Ley de Protección de Datos Personales** del Perú, su reglamento aprobado por D.S. N.º 003-2013-JUS, y normas conexas.

### 1.3 Aceptación

Al crear una cuenta en Qipo o usar la aplicación, aceptás esta Política de Privacidad. Si no estás de acuerdo, no podemos brindarte el servicio. Podés dejar de usarla en cualquier momento eliminando tu cuenta desde la app (ver [sección 9](#9-eliminación-de-tu-cuenta)).

---

## 2. Definiciones

Para evitar ambigüedad, los siguientes términos en mayúscula tienen el significado indicado en cualquier parte de esta política:

- **Aplicación** o **App**: la aplicación móvil Qipo distribuida a través de Google Play Store y, eventualmente, otras tiendas oficiales.
- **Usuario** o **vos**: persona natural mayor de 18 años que crea una Cuenta y utiliza la Aplicación.
- **Cuenta**: registro asociado a un email único que te permite acceder a la App y a tus datos.
- **Datos Personales**: cualquier información que te identifica o te hace identificable, según el artículo 2.4 de la Ley 29733.
- **Tratamiento**: cualquier operación o procedimiento técnico aplicado a Datos Personales (recolección, registro, almacenamiento, modificación, consulta, uso, transmisión, eliminación, etc.).
- **Encargado del Tratamiento**: persona u organización que trata Datos Personales por encargo nuestro (por ejemplo, un proveedor de infraestructura o un servicio de inteligencia artificial).
- **APDP**: Autoridad Nacional de Protección de Datos Personales del Perú, dependiente del Ministerio de Justicia y Derechos Humanos, organismo encargado de velar por el cumplimiento de la Ley 29733.

---

## 3. Datos que recolectamos

Solo recolectamos los datos estrictamente necesarios para que Qipo funcione. Te los detallamos por origen.

### 3.1 Datos que vos nos das directamente

| Categoría | Datos específicos | Cuándo |
|---|---|---|
| **Datos de cuenta** | Email, nombre, contraseña (siempre almacenada con hash criptográfico, nunca en texto plano) | Al registrarte |
| **Preferencias** | Zona horaria, si querés recibir notificaciones push | Durante el uso |
| **Datos financieros personales** | Transacciones (monto, descripción opcional, fecha), categorías que creás, presupuestos que definís, deudas y préstamos personales que registrás, etiquetas de medios de pago (ej: "Tarjeta BCP", "Efectivo") | Cada vez que usás la app |
| **Texto de comandos por voz** | El texto resultante después de que tu dispositivo transcribe lo que dijiste | Cuando usás la función de registro por voz |

> ⚠️ **Sobre datos financieros**: Qipo NO recolecta números de tarjeta de crédito, datos bancarios, ni accede a tus cuentas reales. Cuando registrás un medio de pago, solo guardamos la **etiqueta** que vos le ponés (ej: "Tarjeta BCP"), no los datos sensibles del instrumento. Si en el futuro suscribís el Plan Pro, los datos de pago se procesan exclusivamente por Google Play Billing — Qipo nunca los ve ni los guarda.

### 3.2 Datos que se generan automáticamente

| Categoría | Datos específicos | Para qué |
|---|---|---|
| **Token de notificaciones push** | Identificador único asignado por Firebase Cloud Messaging a tu instalación de la app | Enviarte notificaciones de presupuestos y alertas |
| **Logs técnicos** | Errores de la app, métricas de performance, identificadores de sesión | Detectar y corregir errores, monitorear estabilidad |

### 3.3 Lo que NO recolectamos

Para que quede explícito, Qipo **no recolecta**:

- ❌ **Audio de tu voz** — la transcripción de voz a texto sucede en tu propio dispositivo (usando el motor de reconocimiento del sistema operativo). El audio nunca sale de tu teléfono.
- ❌ **Ubicación GPS**, ni precisa ni aproximada.
- ❌ Tus **contactos**, **fotos**, **mensajes de SMS**, **mensajería instantánea** ni **calendario**.
- ❌ Tu **historial de navegación web**.
- ❌ La **lista de aplicaciones instaladas** en tu dispositivo.
- ❌ Información de **salud, política, religión, orientación sexual, raza** ni cualquier otra categoría de datos sensibles según el artículo 2.5 de la Ley 29733.
- ❌ **Números de tarjeta de crédito o débito, ni datos bancarios reales** (cuando uses el Plan Pro, esos datos los maneja Google Play Billing directamente, fuera de nuestro alcance).

---

## 4. Cómo usamos tus datos

Cada uso que le damos a tus datos tiene una **finalidad específica** y una **base legal** que lo justifica, conforme al artículo 5 de la Ley 29733.

| Finalidad | Datos usados | Base legal |
|---|---|---|
| Crear y mantener tu cuenta, autenticarte, recuperarla si olvidás la contraseña | Email, hash de contraseña, nombre | Ejecución de la relación contractual |
| Registrarte y mostrarte tus transacciones, presupuestos, deudas, categorías y medios de pago | Datos financieros personales | Ejecución de la relación contractual |
| Procesar tus comandos por voz para generarte una sugerencia de transacción editable | Texto resultante de la transcripción + lista de tus categorías y medios de pago | Consentimiento explícito (al activar la función de voz por primera vez) |
| Enviarte notificaciones de presupuestos, alertas y avisos de la app | Token FCM, contenido del aviso | Consentimiento revocable desde Configuración → Notificaciones |
| Prevenir fraude, abusos y accesos no autorizados a tu cuenta | Email, dirección IP, logs de autenticación | Interés legítimo |
| Detectar y corregir errores, monitorear estabilidad y performance de la app | Logs técnicos, identificadores de sesión | Interés legítimo |
| Cumplir obligaciones legales y responder requerimientos de autoridades competentes | Cualquier dato requerido por la autoridad | Cumplimiento de obligación legal |
| Procesar pagos del Plan Pro y mantener el estado de tu suscripción *(activo cuando se lance el Plan Pro)* | Identificador de compra de Google Play, estado de suscripción | Ejecución de la relación contractual |

**Si revocás tu consentimiento** para cualquier finalidad basada en consentimiento (voz o notificaciones), esa función deja de operar para tu cuenta de inmediato, sin afectar el resto del servicio.

---

## 5. Procesamiento por inteligencia artificial

Qipo usa inteligencia artificial únicamente para **una función opcional**: convertir un comando hablado en una sugerencia de transacción estructurada.

### 5.1 Cómo funciona

1. Vos hablás en la app (ejemplo: *"gasté 25 soles en almuerzo con tarjeta BCP"*).
2. **Tu dispositivo** transcribe el audio a texto usando el motor de reconocimiento del sistema operativo (Android). El audio nunca sale de tu teléfono.
3. Qipo envía a nuestro backend ese **texto** junto con la lista de tus categorías y medios de pago disponibles.
4. Nuestro backend reenvía el texto y las opciones disponibles a un proveedor de inteligencia artificial (ver [sección 6.1](#61-proveedores-de-servicio-encargados-del-tratamiento)) que devuelve una transacción estructurada (monto, descripción, categoría sugerida, medio de pago sugerido).
5. La sugerencia se te muestra en pantalla **siempre editable**. Vos confirmás, modificás o descartás.

### 5.2 Qué se manda al proveedor de IA

- ✅ El **texto transcrito** de tu comando.
- ✅ Los **nombres** de tus categorías y medios de pago (para que pueda sugerir uno apropiado).
- ❌ NUNCA tu email, nombre, contraseña ni datos identificadores.
- ❌ NUNCA tus transacciones históricas ni montos previos.
- ❌ NUNCA el audio original.

### 5.3 Decisiones automatizadas

Conforme al artículo 22 del Reglamento de la Ley 29733 (D.S. N.º 003-2013-JUS), te informamos que:

- El sistema **NO toma ninguna decisión que produzca efectos legales o significativos sobre vos** sin tu intervención.
- La sugerencia generada por inteligencia artificial es **siempre revisada y aceptada por vos** antes de guardarse como transacción.
- Tenés derecho a **no usar esta función**: basta con registrar tus transacciones manualmente. Si nunca activás el comando por voz, ningún dato tuyo es procesado por inteligencia artificial.

### 5.4 Retención por el proveedor de IA

El proveedor de inteligencia artificial puede retener temporalmente las consultas según su propia política de privacidad. Recomendamos revisar la política del proveedor listado en la [sección 6.1](#61-proveedores-de-servicio-encargados-del-tratamiento). Qipo no controla esa retención.

---

## 6. Con quién compartimos tus datos

**No vendemos tus datos.** No los cedemos a terceros con fines comerciales. Solo los compartimos con los proveedores estrictamente necesarios para que Qipo funcione, y solo en los escenarios descritos a continuación.

### 6.1 Proveedores de servicio (Encargados del Tratamiento)

Cada uno trata tus datos **por encargo nuestro**, según nuestras instrucciones y bajo acuerdos contractuales que les obligan a estándares equivalentes a los nuestros.

| Proveedor | País | Datos compartidos | Finalidad |
|---|---|---|---|
| **Groq Inc.** | Estados Unidos | Texto de tu comando por voz + nombres de tus categorías y medios de pago | Generar sugerencia de transacción estructurada (función de voz) |
| **Google LLC — Firebase Cloud Messaging** | Estados Unidos | Token de notificaciones push, contenido del aviso a entregar | Entregar notificaciones a tu dispositivo |
| **Google LLC — Google Play Billing** *(activo cuando suscribas Plan Pro)* | Estados Unidos | Identificador anónimo de compra | Procesar pago de suscripción |
| **RevenueCat Inc.** *(activo cuando suscribas Plan Pro)* | Estados Unidos | Identificador anónimo de suscripción, estado de la suscripción | Gestionar el ciclo de vida de la suscripción cross-platform |

Podés consultar las políticas de privacidad de cada proveedor en sus respectivos sitios web ([Groq](https://groq.com/privacy-policy/), [Google](https://policies.google.com/privacy), [RevenueCat](https://www.revenuecat.com/privacy/)).

Si en el futuro sumamos un nuevo proveedor que reciba tus datos, **actualizamos esta política antes de activarlo** y bumpeamos la versión del documento.

### 6.2 Autoridades competentes

Compartimos datos con autoridades **únicamente** cuando recibimos un **requerimiento legal válido** (orden judicial, fiscalía, Autoridad Nacional de Protección de Datos Personales, SUNAT en el marco de sus competencias). En esos casos:

- Solo entregamos los datos estrictamente solicitados.
- Te notificamos cuando legalmente podemos hacerlo.

### 6.3 Transferencia de la operación

Si en el futuro Qipo es vendido, fusionado o transferido a otra entidad, tus datos pasan al nuevo titular bajo las **mismas condiciones** de esta política. Si el cambio implica modificaciones sustanciales, te notificamos con anticipación y te damos la opción de eliminar tu cuenta antes de que el cambio sea efectivo.

---

## 7. Transferencias internacionales de datos

Tus datos se almacenan principalmente en **Perú** (servidores de hosting del backend de Qipo). Sin embargo, algunos de los proveedores listados en la [sección 6.1](#61-proveedores-de-servicio-encargados-del-tratamiento) operan desde **Estados Unidos**, lo que implica una transferencia internacional de Datos Personales.

Conforme al artículo 15 de la Ley 29733 y al Capítulo III del Título II de su Reglamento:

- Cada transferencia se realiza en el marco de un **Acuerdo de Procesamiento de Datos** firmado con el proveedor, que establece garantías equivalentes a las exigidas por la Ley 29733.
- Los proveedores se comprometen a tratar tus datos **únicamente** para los fines indicados en esta política y bajo nuestras instrucciones.
- Tenés derecho a solicitar copia de las garantías aplicadas escribiéndonos a [hola.qipo.app@gmail.com](mailto:hola.qipo.app@gmail.com).

Si la Autoridad Nacional de Protección de Datos Personales determina en el futuro que algún país destinatario deja de ofrecer garantías adecuadas, te lo notificaremos y evaluaremos migrar el servicio o solicitar tu nuevo consentimiento.

---

## 8. Tus derechos sobre tus datos

Como titular de los Datos Personales que Qipo trata, tenés los siguientes derechos garantizados por los artículos 18 a 24 de la Ley 29733, conocidos como **derechos ARCO+P**.

### 8.1 Derecho de acceso

Podés pedirnos en cualquier momento un **reporte completo** de los datos que tenemos sobre vos, su origen, las finalidades para las que los tratamos, y los terceros con quienes los compartimos.

**Plazo de respuesta:** hasta 20 días hábiles desde tu solicitud.

### 8.2 Derecho de rectificación

Si alguno de tus datos es **incorrecto, incompleto o está desactualizado**, podés pedir su corrección. La mayoría de tus datos los podés rectificar vos directamente desde la app (nombre, email, preferencias, transacciones, etc.).

**Plazo de respuesta:** hasta 10 días hábiles desde tu solicitud.

### 8.3 Derecho de cancelación o eliminación

Podés pedir que **borremos tus datos** cuando:

- Ya no son necesarios para las finalidades originales.
- Retirás tu consentimiento (cuando esa era la base legal).
- Considerás que están siendo tratados de manera contraria a la ley.

La forma más directa de ejercerlo es **eliminar tu cuenta** desde la app (ver [sección 9](#9-eliminación-de-tu-cuenta)).

**Plazo de respuesta:** hasta 10 días hábiles desde tu solicitud.

### 8.4 Derecho de oposición

Podés **oponerte** al tratamiento de tus datos para finalidades específicas, incluso si la base legal lo permitiría. Por ejemplo, podés oponerte a recibir notificaciones push (desactivándolas desde Configuración → Notificaciones).

**Plazo de respuesta:** hasta 10 días hábiles desde tu solicitud.

### 8.5 Derecho de portabilidad

Podés solicitar una **copia de tus datos en un formato estructurado y legible por máquina** (ej: JSON o CSV) para llevarlos a otra app o conservarlos vos mismo. Aplica a los datos que vos generaste (transacciones, categorías, presupuestos, deudas).

**Plazo de respuesta:** hasta 20 días hábiles desde tu solicitud.

### 8.6 Derecho a revocar tu consentimiento

Cuando un tratamiento se basa en tu consentimiento (función de voz, notificaciones), podés **revocarlo en cualquier momento** sin necesidad de justificarlo. La revocación no afecta la legalidad del tratamiento previo a la revocación.

### 8.7 Cómo ejercer estos derechos

Tenés tres caminos:

1. **Desde la app**: la mayoría de los derechos los podés ejercer directamente (rectificar tus datos, eliminar tu cuenta, desactivar notificaciones).
2. **Por email**: enviá tu solicitud a [hola.qipo.app@gmail.com](mailto:hola.qipo.app@gmail.com) indicando el derecho que querés ejercer y adjuntando una **copia de tu DNI** o documento equivalente para verificar tu identidad.
3. **Ante la APDP**: si considerás que no respondimos adecuadamente, podés presentar un reclamo ante la Autoridad Nacional de Protección de Datos Personales (ver [sección 14](#14-reclamos-ante-la-apdp)).

No te cobramos por ejercer estos derechos. Si tu solicitud es manifiestamente infundada o repetitiva, podemos justificar denegarla, explicándote por qué.

---

## 9. Eliminación de tu cuenta

Podés eliminar tu cuenta de Qipo en cualquier momento, sin necesidad de contactarnos.

### 9.1 Cómo hacerlo

Desde la app:

1. Andá a **Perfil** → **Configuración** → **Eliminar cuenta**.
2. Te pediremos confirmar la acción escribiendo una palabra clave (para evitar borrados accidentales).
3. Tu sesión se cierra y todos los tokens locales se borran.

### 9.2 Qué se borra y cuándo

| Categoría | Cuándo se borra |
|---|---|
| Datos de cuenta (email, nombre, contraseña hasheada) | A los 30 días de la solicitud (período de gracia para revertir borrados accidentales) |
| Transacciones, categorías, presupuestos, deudas, medios de pago | A los 30 días de la solicitud |
| Token FCM de notificaciones | Inmediatamente |
| Tokens de sesión (JWT, refresh tokens) | Inmediatamente al cerrar sesión |
| Logs técnicos asociados a tu cuenta | Al expirar el período normal de retención de logs (ver [sección 10](#10-retención-de-datos)) |

Durante los 30 días de gracia, podés reactivar tu cuenta escribiéndonos a [hola.qipo.app@gmail.com](mailto:hola.qipo.app@gmail.com). Pasados los 30 días, el borrado es **irreversible** y los datos no pueden recuperarse.

### 9.3 Qué pasa si tenés Plan Pro activo

Si suscribís el Plan Pro y eliminás tu cuenta:

- Tu suscripción **NO se cancela automáticamente** desde Qipo (Google Play gestiona las suscripciones de manera independiente).
- Te recomendamos **cancelar la suscripción primero** desde Google Play Store → Suscripciones, y después eliminar la cuenta.
- Si eliminás la cuenta sin cancelar, la suscripción seguirá renovándose pero sin servicio activo. Qipo no se hace responsable por cobros generados después de eliminar la cuenta sin cancelar la suscripción.

### 9.4 Datos que conservamos por requerimiento legal

Algunos datos podemos estar obligados a conservar por requerimientos tributarios, contables o legales (por ejemplo, registros de transacciones de pago si suscribiste el Plan Pro, conservados según normas tributarias peruanas). Estos datos se conservan **únicamente** por el plazo legal y **no se usan** para ninguna otra finalidad.

---

## 10. Retención de datos

Conservamos tus Datos Personales solo el tiempo necesario para las finalidades para las que fueron recolectados, conforme al artículo 11 de la Ley 29733.

| Categoría de datos | Plazo de retención |
|---|---|
| Datos de cuenta y datos financieros personales | Mientras tu cuenta esté activa, más 30 días de gracia tras eliminación |
| Token FCM de notificaciones push | Hasta que desactives notificaciones, elimines la app o eliminés tu cuenta |
| Logs técnicos (errores, performance) | Hasta 90 días desde su generación |
| Logs de autenticación (login, cambios de contraseña) | Hasta 12 meses desde su generación |
| Identificadores de pago (Plan Pro) | Plazo legal aplicable según normativa tributaria peruana (típicamente hasta 5 años) |
| Tokens de recuperación de contraseña (OTP) | Máximo 15 minutos desde su generación |
| Tokens de sesión (refresh tokens) | Hasta su expiración natural o revocación por logout / cambio de contraseña |

Pasados los plazos indicados, los datos se eliminan o se anonimizan de manera irreversible.

---

## 11. Seguridad

Aplicamos medidas técnicas y organizativas razonables para proteger tus Datos Personales contra acceso no autorizado, alteración, divulgación o destrucción.

### 11.1 Medidas técnicas

- **Cifrado en tránsito**: toda comunicación entre la app y nuestro backend usa **HTTPS con TLS 1.2 o superior**.
- **Hash de contraseñas**: las contraseñas se almacenan usando algoritmos de hashing criptográfico modernos. **Nunca** guardamos contraseñas en texto plano.
- **Autenticación con tokens**: usamos JWT de duración corta combinados con refresh tokens rotables, lo que limita la ventana de exposición ante un eventual robo de credenciales.
- **OTP de un solo uso**: el código de recuperación de contraseña es válido por máximo 15 minutos y solo se puede usar una vez.
- **Cifrado en reposo**: los datos almacenados en nuestra base de datos están protegidos por las medidas de cifrado provistas por el proveedor de hosting.
- **Backups encriptados**: los respaldos periódicos están cifrados y se conservan por el período mínimo necesario.

### 11.2 Medidas organizativas

- El acceso al backend y a la base de datos está restringido al equipo de desarrollo de Qipo (actualmente, una sola persona: el responsable del tratamiento).
- Cualquier nueva persona que se sume al equipo firma un compromiso de confidencialidad antes de tener acceso a datos.
- Las credenciales de acceso a sistemas se rotan periódicamente.

### 11.3 Limitaciones

Te informamos con honestidad: **ningún sistema es 100% seguro**. A pesar de aplicar medidas razonables, no podemos garantizar de manera absoluta que tus datos estén libres de cualquier riesgo.

### 11.4 En caso de incidente de seguridad

Si detectamos una brecha de seguridad que afecte tus Datos Personales:

- **Te notificamos por email** a la dirección registrada en tu cuenta, en el menor tiempo posible y en un plazo máximo razonable según la naturaleza del incidente.
- **Notificamos a la APDP** dentro de los plazos y en la forma que exige la Ley 29733 y su Reglamento.
- Tomamos las medidas necesarias para contener el incidente y prevenir su recurrencia.

---

## 12. Privacidad de menores de edad

Qipo está dirigido **exclusivamente a personas mayores de 18 años**. La aplicación no está diseñada ni destinada al uso por menores, y no recolectamos ni tratamos conscientemente datos de personas menores de 18 años.

Si descubrimos que se ha creado una cuenta utilizando datos de un menor de 18 años, procederemos a eliminar la cuenta y todos los datos asociados sin demora.

Si sos padre, madre o tutor legal y considerás que un menor a tu cargo creó una cuenta en Qipo, escribinos a [hola.qipo.app@gmail.com](mailto:hola.qipo.app@gmail.com) y la eliminaremos.

---

## 13. Cambios a esta política

Podemos actualizar esta Política de Privacidad cuando lo consideremos necesario, por ejemplo:

- Cuando agreguemos nuevas funcionalidades que impliquen tratar datos de manera diferente.
- Cuando incorporemos o reemplacemos proveedores de servicio.
- Cuando cambien las normas legales aplicables.
- Para corregir errores u oscuridades en la redacción.

### 13.1 Tipos de cambios

- **Cambios materiales** (versión mayor, ej: 1.0 → 2.0): cambios que alteran las finalidades de tratamiento, agregan nuevos terceros que reciben datos, o introducen nuevas categorías de datos recolectados.
- **Cambios no materiales** (versión menor, ej: 1.0 → 1.1): correcciones de redacción, aclaraciones, actualización de URLs o referencias legales sin alterar el sentido.

### 13.2 Cómo te notificamos

- **Cambios materiales**: te avisamos con **al menos 15 días de anticipación** antes de que entren en vigencia, mediante:
  - Notificación in-app la próxima vez que abras Qipo.
  - Email a la dirección registrada en tu cuenta.
  - Publicación de la nueva versión en esta misma URL con la fecha de vigencia indicada.

  Si no estás de acuerdo con los cambios, podés eliminar tu cuenta antes de que entren en vigencia.

- **Cambios no materiales**: se publican directamente con nuevo número de versión en el [CHANGELOG público del repositorio](https://github.com/angel452/qipo-legal/blob/main/CHANGELOG.md).

### 13.3 Versión vigente

La versión actualmente vigente es la indicada al inicio de este documento. Las versiones anteriores quedan archivadas en el historial de Git del repositorio público.

---

## 14. Reclamos ante la APDP

Si considerás que no respondimos adecuadamente a una solicitud relativa a tus derechos, o que estamos tratando tus datos de manera contraria a la Ley 29733, podés presentar un reclamo ante la **Autoridad Nacional de Protección de Datos Personales (APDP)**, dependiente del Ministerio de Justicia y Derechos Humanos del Perú.

| Datos de la APDP |  |
|---|---|
| **Nombre completo** | Autoridad Nacional de Protección de Datos Personales |
| **Organismo del que depende** | Ministerio de Justicia y Derechos Humanos del Perú |
| **Sitio web oficial** | [https://www.gob.pe/anpd](https://www.gob.pe/anpd) |
| **Plataforma de reclamos** | Mesa de partes virtual del MINJUSDH |

Te recomendamos, antes de escalar a la APDP, **escribirnos primero a nosotros** a [hola.qipo.app@gmail.com](mailto:hola.qipo.app@gmail.com) para que podamos resolver tu inquietud directamente. La mayoría de los casos se resuelven sin necesidad de acudir a la autoridad.

---

## 15. Contacto

Para cualquier consulta, solicitud o reclamo relacionado con esta Política de Privacidad o con el tratamiento de tus Datos Personales, podés contactarnos a:

- **Email**: [hola.qipo.app@gmail.com](mailto:hola.qipo.app@gmail.com)
- **Idioma de atención**: español
- **Plazo de primera respuesta**: hasta 5 días hábiles desde la recepción de tu mensaje
- **Plazo de resolución**: según los plazos establecidos en la Ley 29733 para cada derecho (ver [sección 8](#8-tus-derechos-sobre-tus-datos))

---

## 16. Información del responsable del tratamiento

Conforme al artículo 18 de la Ley 29733, te identificamos al responsable del tratamiento de tus Datos Personales:

| Dato |  |
|---|---|
| **Nombre legal** | Angel Josue Loayza Huarachi |
| **Naturaleza** | Persona natural |
| **País** | Perú |
| **Email de contacto** | [hola.qipo.app@gmail.com](mailto:hola.qipo.app@gmail.com) |
| **Aplicación operada** | Qipo (distribuida en Google Play Store) |

El domicilio postal completo del responsable se encuentra registrado en Google Play Console y es accesible para autoridades competentes mediante requerimiento legal. En caso de operar Qipo bajo plan pago en el futuro, el domicilio será publicado conforme a las reglas de transparencia exigidas por la tienda de aplicaciones.

---

## 17. Vigencia y versión

| Versión | Fecha de vigencia | Resumen de cambios |
|---|---|---|
| 1.0-draft | (pendiente de publicación) | Versión inicial — borrador en construcción, no vigente |

El historial completo y detallado de cambios se mantiene en el [CHANGELOG público del repositorio](https://github.com/angel452/qipo-legal/blob/main/CHANGELOG.md).

---

[← Volver a documentos legales](../)
