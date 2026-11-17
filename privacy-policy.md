# Política de Privacidad — FormaX

**Última actualización:** 17 de noviembre de 2026

Esta Política de Privacidad describe cómo **José C. Frías** ("nosotros", "el
desarrollador") recopila, usa y protege tu información cuando utilizas la aplicación móvil
**FormaX** (la "App"). Al crear una cuenta y usar la App, aceptas las prácticas descritas aquí.

Para cualquier consulta sobre privacidad puedes escribirnos a: **jcfrias96@gmail.com**.

---

## 1. Información que recopilamos

Recopilamos únicamente los datos necesarios para que la App funcione. **No usamos publicidad,
no vendemos tus datos y no integramos rastreadores de terceros con fines publicitarios.**

### a) Datos de cuenta
- **Nombre** y **dirección de correo electrónico** (para registro, inicio de sesión y verificación
  de la cuenta).
- Estado de tu suscripción y datos relacionados con el uso de la App (fechas de generación de
  planes, número de planes generados, periodo de prueba).

### b) Datos de salud y actividad física (sensibles)
Estos datos los introduces tú voluntariamente y los usamos para personalizar tus planes:
- **Peso actual y objetivo, altura y edad.**
- **Sexo** (hombre o mujer). Se te pide al crear la cuenta y se usa para ajustar el plan de
  entrenamiento y las necesidades calóricas, que difieren de forma relevante.
- **Índice de Masa Corporal (IMC)** calculado a partir de tu peso y altura.
- **Meta de entrenamiento, nivel y disponibilidad** (cuántos y qué días de la semana entrenas,
  equipamiento y **tiempo por sesión**, es decir, cuántos minutos tienes para cada entrenamiento).
- **Enfoque muscular**, si lo eliges: los grupos que quieres priorizar (pecho, espalda, piernas,
  glúteos, hombros, brazos, abdomen) y con cuánta intensidad.
- **Registros de entrenamiento** (ejercicios, series, repeticiones, peso usado, fechas) y los
  **cambios que hagas a tu rutina** (ejercicios movidos, añadidos o quitados).
- **Registros de sueño** y **registros de peso corporal** a lo largo del tiempo.
- **Registros de hábitos** que decidas anotar: vasos de agua del día y comidas de tu plan que
  marques como comidas ("Comí esto"). Se guardan solo para mostrarte tu día y tu progreso.
- **Exámenes médicos opcionales** que decidas ingresar: glucosa, colesterol total, HDL, LDL,
  triglicéridos, presión arterial y hemoglobina. **Todos son opcionales**: si dejas un campo en
  blanco, no se guarda ni se envía a ningún sitio.
- **Cuestionario de salud** antes de crear tu plan: si te aplica alguna de estas situaciones —
  problema del corazón o presión alta diagnosticada, dolor en el pecho o mareos al hacer ejercicio,
  lesión o dolor articular, medicamentos para una condición crónica o (solo mujeres) embarazo o
  parto reciente—, o "ninguna de estas". Se usa solo para que el plan sea más prudente.
- **Otra dificultad o condición**, si decides escribirla (por ejemplo, una hernia, asma o una
  operación), para que tu rutina y tu dieta se adapten a ella.
- **Alergias o alimentos que no comes**, si decides escribirlos, para que tu dieta no los incluya.
- **Alimentos disponibles**: los alimentos que desmarques de la lista porque no los tienes a tu
  alcance, para que tu dieta (y el cambio de un platillo) use solo lo que sí tienes.

### b.1) Datos de Health Connect (opcional)
Si decides conectar **Health Connect** (la app de Android que reúne los datos de tu reloj o tu
teléfono, por ejemplo de Samsung Health), FormaX lee **solo** dos datos, y solo con tu permiso:
- **Tus pasos de hoy.** Se muestran en la pantalla de Inicio junto a tu meta de pasos. **No se
  guardan ni salen de tu teléfono.**
- **La duración de tu sueño de anoche.** Se usa para llenar el registro de sueño; se guarda en tu
  cuenta **solo si tú pulsas «Guardar»**, igual que un registro manual, y sirve para calcular la
  progresión de carga.

FormaX **nunca escribe ni modifica** datos en Health Connect. Estos datos **no se envían a la IA**,
no se venden, no se comparten con terceros y no se usan para publicidad ni para entrenar modelos de
IA. El uso que hace FormaX de los datos de Health Connect cumple la Política de permisos de Health
Connect, incluidos sus requisitos de uso limitado. Puedes quitar el permiso cuando quieras desde
Health Connect o desde FormaX → Perfil → Ajustes (la rueda) → Privacidad.

> FormaX **no** se conecta a tu historial médico. Salvo lo de Health Connect que autorices, todos
> los datos de salud los introduces manualmente.

### c) Datos técnicos y de pago
- Identificadores de la transacción de **Google Play Billing** cuando contratas una suscripción.
  El pago lo procesa **Google**; nosotros **no** recibimos ni almacenamos los datos de tu tarjeta.
- Un **token de notificaciones** (Firebase Cloud Messaging), para avisarte cuando resolvamos o
  respondamos un reporte o sugerencia que nos enviaste.
- Si nos envías un **comentario o reporte**, además de tu mensaje, tu nombre y tu correo guardamos
  el **modelo de tu teléfono**, su **versión de Android**, la **versión de la App** y el idioma del
  sistema, para poder reproducir el problema. Si te **respondemos**, la respuesta se guarda junto a
  tu comentario y solo tú (y el administrador) puedes verla, en *Comentarios → Mis comentarios*.

### d) Fotos de comida (escaneo con IA — función premium)
Si usas la función **Escanear comida** (disponible durante el periodo de prueba y con suscripción
activa), puedes **tomar una foto con la cámara o elegir una imagen de tu galería**. Esa imagen se
reduce de tamaño y se envía a nuestro proveedor de IA (**Anthropic**, modelo Claude), a través de
nuestro servidor intermediario, para estimar sus calorías y macronutrientes y darte un veredicto
según tu meta.

> **La foto NO se almacena.** No la guardamos en nuestros servidores ni en nuestra base de datos, y
> Anthropic **no la utiliza para entrenar sus modelos**. La imagen se procesa en el momento
> únicamente para generar el análisis, que se te muestra en pantalla.

### e) Datos de diagnóstico y uso

Para saber si la App falla y cómo se usa, empleamos dos servicios de Google Firebase:

- **Firebase Crashlytics** (informes de fallos): si la App se cierra inesperadamente, recibimos un
  informe técnico con el punto del código donde ocurrió, el **modelo de dispositivo**, la **versión
  de Android** y el momento del fallo. Nos permite corregir errores que no podemos reproducir.
- **Firebase Analytics** (estadísticas de uso): registramos **acciones anónimas** dentro de la App
  —por ejemplo, que se completó un registro, que se generó un plan o que se abrió la pantalla de
  suscripción— junto con un **identificador aleatorio de la instalación**, el modelo de dispositivo
  y el **país aproximado** (deducido de la dirección IP).

> Estos datos **no incluyen tu nombre, tu correo, tus exámenes médicos ni tus fotos de comida**, y
> **no se usan para publicidad**: los utilizamos únicamente para corregir fallos y mejorar la App.

No recopilamos tu ubicación ni tu lista de contactos, y **no accedemos al micrófono**. Solo usamos la
cámara o la galería cuando tú lo eliges para escanear una comida (ver apartado d).

---

## 2. Cómo usamos tu información

Usamos los datos exclusivamente para:
- Crear y autenticar tu cuenta y verificar tu correo electrónico.
- **Generar planes de entrenamiento y dieta personalizados con inteligencia artificial.**
- **Analizar las fotos de comida que decidas escanear** para estimar calorías y macros y darte un
  veredicto según tu meta (función premium; la foto no se almacena — ver apartado 1.d).
- Calcular la progresión de carga, el IMC y las recomendaciones de sueño.
- Mostrarte tus pasos del día y llenar tu registro de sueño, si conectas Health Connect.
- Mostrarte tu progreso e historial dentro de la App.
- Gestionar tu periodo de prueba, tu cuota gratuita y tu suscripción.
- Enviarte recordatorios locales (si los activas).
- Atender los comentarios o reportes que nos envíes, responderte y avisarte cuando los resolvamos.

### Procesamiento por inteligencia artificial
Para generar tus planes, enviamos a nuestro proveedor de IA (**Anthropic**, modelo Claude) los datos
necesarios para personalizar el plan: tu meta, nivel, disponibilidad, peso/altura, edad, sexo, IMC y,
**si los proporcionas**, tu enfoque muscular, tus exámenes médicos, tus respuestas al cuestionario
de salud, la otra dificultad que escribas, tus alergias o alimentos que no comes, tu tiempo por sesión
y los alimentos que marcaste como no disponibles. Estos datos viajan a través de nuestro servidor intermediario (un *Cloudflare
Worker*) que añade la autenticación y reenvía la solicitud. **No se utilizan para entrenar modelos
de IA** y se procesan solo para producir tu plan.

Si usas la función de **escaneo de comida**, también enviamos a Anthropic la **foto** que elijas,
exclusivamente para analizarla en ese momento. **La foto no se almacena** y tampoco se usa para
entrenar modelos (ver apartado 1.d).

> Los planes generados son orientativos y **no constituyen consejo, diagnóstico ni tratamiento
> médico**. Consulta a un profesional de la salud antes de iniciar cualquier programa de ejercicio
> o nutrición, especialmente si tienes condiciones médicas.

---

## 3. Con quién compartimos tu información (encargados del tratamiento)

No vendemos tus datos. Los compartimos únicamente con los proveedores que hacen funcionar la App:

| Proveedor | Finalidad | Datos implicados |
|---|---|---|
| **Google Firebase** (Authentication, Cloud Firestore, Cloud Messaging) | Cuenta, base de datos y notificaciones | Cuenta, datos de salud y actividad |
| **Google Firebase** (Crashlytics, Analytics) | Informes de fallos y estadísticas de uso | Diagnóstico técnico y acciones anónimas dentro de la App (ver apartado 1.e) |
| **Anthropic** (API de Claude) | Generación de planes con IA y análisis de fotos de comida | Datos del plan y exámenes (si los das); **fotos de comida** que escanees (no se almacenan) |
| **Cloudflare** | Servidor intermediario que enruta las solicitudes a la IA | Tránsito de la solicitud |
| **Google Play (Billing)** | Procesamiento de suscripciones | Datos de la transacción |
| **Pexels** | Búsqueda de fotos de comida ilustrativas | Solo el texto de búsqueda en inglés; **ningún dato personal** |

Cada proveedor trata los datos conforme a sus propias políticas de privacidad y seguridad.

---

## 4. Dónde se almacenan tus datos

Tus datos se almacenan en la infraestructura de **Google Firebase** (proyecto alojado en servidores
de Google, región *us-central1*). La transmisión está cifrada (HTTPS/TLS). El acceso a tus datos
está restringido por reglas de seguridad: tú (con tu cuenta autenticada) puedes leer y escribir tu
propia información, y ningún otro usuario puede verla.

**Acceso del administrador.** El responsable de FormaX (la única cuenta de administrador) puede
consultar los datos de tu cuenta —perfil, planes, registros, cupo de uso y fechas de la cuenta—
**exclusivamente** para dar soporte, atender tus comentarios o reportes, prevenir abusos y
gestionar la cuenta. Desde el panel de administración también puede ampliar tu periodo de prueba,
asignarte una **contraseña temporal** (por ejemplo, si la pides porque no recuerdas la tuya; al
entrar con ella la App te pedirá crear una nueva), **bloquear** una cuenta que incumpla los
Términos o **eliminarla**. Ese acceso no se usa para publicidad ni se comparte con terceros.

---

## 5. Conservación y eliminación de datos

Conservamos tus datos mientras tu cuenta esté activa. Puedes:
- **Editar** tus datos de peso, exámenes y preferencias dentro de la App en cualquier momento.
- **Eliminar tu cuenta directamente desde la App** (Perfil → Ajustes, la rueda → "Eliminar mi cuenta"): esto borra de
  forma permanente tu cuenta de acceso y **todos tus datos** de nuestra base de datos.
- Alternativamente, **solicitar la eliminación** escribiendo a **jcfrias96@gmail.com** desde el
  correo asociado a tu cuenta. Procesaremos la solicitud en un plazo razonable y eliminaremos tu
  información de nuestra base de datos.

**Lo único que conservamos al eliminar tu cuenta**, para evitar que se abuse del período gratuito
borrando la cuenta y volviendo a crearla: un **código cifrado derivado de tu correo** (no es tu
correo ni permite recuperarlo) junto con el **número de planes gratuitos que usaste** y la **fecha en
que empezó tu prueba**. No contiene tu nombre, tus medidas, tus planes ni ningún otro dato.

Los pasos detallados, qué se elimina y qué se conserva están en
[Eliminar tu cuenta](https://jcfrias96-eng.github.io/formax-privacy/eliminar-cuenta.html).

---

## 6. Tus derechos

Según tu lugar de residencia, puedes tener derecho a **acceder**, **rectificar**, **eliminar** o
**exportar** tus datos personales, así como a **oponerte** o **limitar** su tratamiento. Para
ejercer cualquiera de estos derechos, escríbenos a **jcfrias96@gmail.com**. Si resides en la Unión
Europea o en una jurisdicción con normativa equivalente, también puedes presentar una reclamación
ante la autoridad de protección de datos correspondiente.

---

## 7. Seguridad

Aplicamos medidas técnicas razonables para proteger tu información: cifrado en tránsito (HTTPS),
autenticación de cuenta, reglas de acceso por usuario en la base de datos y claves de servicio
gestionadas fuera de la aplicación. Ningún sistema es 100 % infalible, pero trabajamos para
proteger tus datos frente a accesos no autorizados.

---

## 8. Menores de edad

FormaX **no está dirigida a menores de 18 años** y no recopilamos a sabiendas datos de menores. Si
crees que un menor nos ha proporcionado datos, contáctanos y los eliminaremos.

---

## 9. Cambios en esta política

Podemos actualizar esta Política de Privacidad ocasionalmente. Publicaremos la versión vigente en
**https://jcfrias96-eng.github.io/formax-privacy/** y actualizaremos la fecha de "Última actualización". Si los cambios son
significativos, te lo notificaremos dentro de la App o por correo.

---

## 10. Contacto

Responsable del tratamiento: **José C. Frías**
Jurisdicción aplicable: **República Dominicana**
Correo de contacto: **jcfrias96@gmail.com**

---

*FormaX — Aplicación de fitness con inteligencia artificial.*
