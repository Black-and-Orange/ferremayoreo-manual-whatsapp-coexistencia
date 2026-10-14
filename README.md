# Manual: conectar números de WhatsApp Business a HubSpot (coexistencia)

**Ferremayoreo Elizondo** · Preparado por Black & Orange · Versión 1.0 · octubre de 2026

Esta guía acompaña paso a paso la conexión de los WhatsApp Business de los vendedores a HubSpot con **coexistencia**: el número sigue funcionando en el celular de siempre y, al mismo tiempo, las conversaciones aparecen en HubSpot.

> [!NOTE]
> Este manual es para los **números de los vendedores**. El número central (811 600 1459) ya está conectado de otra forma (API de Meta) y no se toca con estos pasos.

## Contenido

1. [Antes de empezar](#1-antes-de-empezar)
2. [Quién participa](#2-quién-participa)
3. [Dar los permisos](#3-dar-los-permisos)
4. [Crear la bandeja del vendedor](#4-crear-la-bandeja-del-vendedor)
5. [Conectar el número](#5-conectar-el-número)
6. [Asignar las conversaciones al vendedor](#6-asignar-las-conversaciones-al-vendedor)
7. [Probar que funciona](#7-probar-que-funciona)
8. [Reglas de uso para el vendedor](#8-reglas-de-uso-para-el-vendedor)
9. [Problemas comunes](#9-problemas-comunes)
10. [Cómo desconectar un número](#10-cómo-desconectar-un-número)
11. [Checklist por número](#11-checklist-por-número)

---

## 1. Antes de empezar

Si estos puntos están listos, cada número se conecta en pocos minutos y el historial termina de llegar solo, en segundo plano.

| ✔ | Requisito | Cómo saberlo |
|---|---|---|
| ☐ | **Plan de HubSpot** Marketing Hub Professional o superior | Ferremayoreo ya lo cumple |
| ☐ | El número usa la **app WhatsApp Business** (no WhatsApp normal) | El ícono de la app tiene una "B" |
| ☐ | La app está **actualizada** | En la tienda de apps no aparece "Actualizar" |
| ☐ | El número **no está conectado a otra plataforma** de mensajería | Si lo estaba, se desconecta primero y se esperan 10 a 15 minutos |
| ☐ | Hay una persona con **Súper administrador en HubSpot** | Ver [sección 3](#3-dar-los-permisos) |
| ☐ | Esa misma persona (u otra a su lado) tiene **control total del portafolio de Meta** "Ferre Mayoreo" | Ver [sección 3](#3-dar-los-permisos) |
| ☐ | El **celular del vendedor está a la mano**, con internet | Se escanea un código QR con él |
| ☐ | La **bandeja del vendedor ya está creada** | Ver [sección 4](#4-crear-la-bandeja-del-vendedor) |
| ☐ | Ya se revisó si hay **chats que no deben subir** a HubSpot | Se borran del celular **antes** de conectar |

> [!TIP]
> Conviene hacer la conexión desde una computadora, con la sesión de HubSpot abierta y el celular del vendedor al lado.

---

## 2. Quién participa

| Persona | Qué hace | ¿Necesita acceso a Meta? |
|---|---|---|
| **Súper administrador de HubSpot** | Crea la bandeja, hace la conexión y configura la asignación | Sí, control total del portafolio (o alguien a su lado que lo tenga) |
| **Administrador de Meta** | Inicia sesión en la ventana de Meta durante la conexión | Sí |
| **Vendedor** | Presta su celular para escanear el QR y confirmar | **No.** Le basta su WhatsApp Business y su usuario de HubSpot |

En Ferremayoreo, normalmente esto lo coordinan Joaquín y Adrián (Sistemas).

---

## 3. Dar los permisos

Solo hace falta si la persona que va a conectar todavía no tiene alguno de los dos permisos.

### 3.1 Control total en el portafolio de Meta

1. Para empezar, entras a [business.facebook.com](https://business.facebook.com) con una cuenta que ya tenga control total del portafolio **Ferre Mayoreo**.
2. Abres **Configuración** (el engrane) y, en el menú de la izquierda, das clic en **Personas**.
3. Das clic en **Invitar personas** (arriba a la derecha).
4. Escribes el correo de la persona. Debe ser el mismo correo de su cuenta de Facebook.
5. En los permisos del portafolio eliges **Control total** y das clic en **Siguiente** hasta **Invitar**.
6. La persona recibe un correo y **acepta la invitación**. Hasta que la acepte, no tiene acceso.

> [!IMPORTANT]
> Si no ves la opción **Personas** en el menú, tu cuenta no tiene control total del portafolio. En ese caso, la invitación la hace alguien que sí lo tenga.

### 3.2 Súper administrador en HubSpot

1. En HubSpot das clic en el **engrane de Configuración** (arriba a la derecha).
2. En el menú de la izquierda entras a **Usuarios y equipos**.
3. Das clic en el nombre del usuario y abres la pestaña **Permisos**.
4. Activas la opción de **Súper administrador** y guardas.

> [!NOTE]
> Súper administrador es un **permiso**, no una licencia: no cambia el tipo de asiento del usuario. Si se prefiere, se puede dar solo para el día de la conexión y quitarlo después.

---

## 4. Crear la bandeja del vendedor

Cada vendedor tiene **su propia bandeja**, para que vea solo sus conversaciones y sus chats queden privados. Se crea **antes** de conectar el número; si no, al conectar solo aparece la bandeja general, donde no conviene dejarlo porque se mezcla con todo lo demás.

1. En HubSpot das clic en el **engrane de Configuración**.
2. En el menú de la izquierda entras a **Bandeja de entrada** (puede aparecer dentro de *Bandeja de entrada y centro de ayuda*).
3. Das clic en **Acciones** → **Crear bandeja de entrada**.
4. Le pones de nombre el **nombre y apellido del vendedor**, para encontrarla fácil.
5. En **quién tiene acceso** eliges **usuarios específicos**: el vendedor y quien lo supervisa. Conviene **no** dar acceso a todo el equipo de ventas.
6. Cuando te pida conectar un canal, eliges **conectar un canal más tarde**.

> [!NOTE]
> Los Súper administradores ven todas las bandejas aunque no estén en la lista de acceso. Pero **solo pueden escribir** en una bandeja si son miembros de ella.

---

## 5. Conectar el número

> [!WARNING]
> Durante la conexión, Meta puede ofrecer dos caminos. El correcto es **conectar la app de WhatsApp Business que ya existe** (coexistencia). Si en algún momento te pide **registrar el número con un código por SMS o llamada**, conviene detenerse ahí: esa es otra ruta (API) que saca el número de la app del celular.

1. En HubSpot das clic en el **engrane de Configuración** y, al final del menú de la izquierda, entras a **WhatsApp**.
2. Das clic en **Conectar número de WhatsApp** (arriba a la derecha) y luego en **Continuar con WhatsApp**. Se abre una **ventana emergente de Meta**; si el navegador la bloquea, la permites.
3. En esa ventana inicias sesión con la **cuenta de Facebook que tiene control total** del portafolio y das clic en **Continuar**.
4. En **Añade tu número de teléfono de WhatsApp** eliges la lada de México (**+52**), escribes el número del vendedor y das clic en **Siguiente**.
5. Meta reconoce que el número ya tiene WhatsApp Business. Eliges la opción de **conectar la app existente** y, en **Verifica los datos de tu cuenta**, revisas que sean correctos y das clic en **Siguiente**.
6. En **Cartera empresarial** (el portafolio) eliges **Ferre Mayoreo** y das clic en **Siguiente**.
7. Aparece un **código QR** en la pantalla. En el celular del vendedor abres **WhatsApp Business** y lo escaneas. Si la app no lo abre sola, lo encuentras en **Ajustes → Cuenta → Plataforma para empresas**.
8. En el celular aparece la pregunta de **compartir el historial** de chats. Recomendamos aceptarlo (ver la nota de abajo). Das clic en **Confirmar**; puede tardar unos 45 segundos.
9. En la computadora revisas el **nombre de la cuenta** (solo se cambia desde la app) y eliges la **zona horaria** de México que corresponda.
10. Escribes el **código de verificación** que llega (al celular o al correo, según el caso).
11. Das clic en **Finalizar** y después en **Conectar a la bandeja de entrada**.
12. En el panel de la derecha eliges **Elegir una bandeja existente**, seleccionas la **bandeja del vendedor** y das clic en **Guardar**.

> [!IMPORTANT]
> **Traer o no el historial es una decisión que no se puede cambiar después.** Si no se trae, la única forma de traerlo es desconectar y repetir todo. Lo que llega:
> - Hasta **6 meses** de conversaciones individuales, **solo en texto**.
> - Las fotos, audios y videos antiguos aparecen como un aviso, no como archivo.
> - Los **grupos no se comparten**.

Las pantallas pueden variar un poco de orden, porque Meta las actualiza seguido. Lo importante es reconocer cada paso: número → app existente → portafolio → QR → historial → zona horaria → código → bandeja.

---

## 6. Asignar las conversaciones al vendedor

Este paso es **el que más se olvida**. El historial llega sin dueño y, si no se asigna, HubSpot manda un aviso de "conversación sin asignar" **por cada chat** a todo el equipo.

1. Entras a la **bandeja del vendedor**.
2. Abres **Configuración de canales** → **WhatsApp** → el número recién conectado.
3. En **Asignación** eliges **usuarios o equipos específicos** y seleccionas al **vendedor**.
4. **Desactivas** la opción **asignar solo a usuarios activos** (así ninguna conversación se queda sin dueño cuando el vendedor no está conectado).
5. Si aparece la opción de **carga equilibrada**, la dejas desactivada: es un solo vendedor.
6. Das clic en **Guardar**.

> [!NOTE]
> Solo se puede asignar a alguien que **tenga acceso a la bandeja**. Si el vendedor no aparece en la lista, revisas la pestaña **Acceso** de la bandeja.

---

## 7. Probar que funciona

1. Desde otro celular, mandas un mensaje al número del vendedor.
2. Revisas que llegue **al celular del vendedor y a su bandeja en HubSpot**.
3. El vendedor responde **desde su celular** y revisas que la respuesta también aparezca en HubSpot.
4. Abres la conversación en HubSpot y revisas que quedó **asignada al vendedor** y ligada al contacto correcto.

Si todo aparece en los dos lados, el número quedó listo. ✅

---

## 8. Reglas de uso para el vendedor

Para compartir con cada vendedor el día que se conecta su número.

### Lo que no cambia

- Sigue usando **su celular (o WhatsApp Web) como siempre**. No hay app nueva que aprender.
- Sus clientes **no notan nada**: mismo número, misma conversación.
- Aunque borre un chat en su celular, la conversación **queda guardada en HubSpot**.

### Lo que sí hay que cuidar

| Regla | Por qué |
|---|---|
| **Abrir WhatsApp Business al menos una vez cada 14 días** | Si el celular pasa dos semanas sin abrir la app, Meta corta la conexión y hay que volver a conectar el número |
| **Iniciar las conversaciones desde el celular** | Escribir desde el celular **no consume plantillas ni créditos**. Si se inicia desde HubSpot con la ventana de 24 horas cerrada, se gasta una plantilla (con costo) |
| **Ventana de 24 horas** | Cuando el cliente escribe, hay 24 horas para responder libremente. Pasado ese tiempo, desde HubSpot solo se puede escribir con una plantilla aprobada por Meta |
| **Acordar quién responde** | Si el vendedor contesta desde el celular y otra persona desde HubSpot, el cliente recibe **dos respuestas**. Esto se resuelve con un acuerdo interno, no con la herramienta |
| **Notas de voz desde el celular** | Desde HubSpot se ven y se escuchan, pero se envían desde el celular |
| **Teléfonos de los contactos con +52** | Así HubSpot liga solo la conversación con el contacto correcto |
| **WhatsApp Web** | Si el vendedor lo usa, puede que tenga que volver a vincularlo después de la conexión |

### Lo que se queda solo en el celular

- **Grupos**, **estados**, **listas de difusión**, **catálogo** y **llamadas** de voz o video.

### Funciones de WhatsApp que se apagan en chats individuales

Son reglas de Meta, no de HubSpot:

- Mensajes temporales (los que se borran solos).
- Mensajes de "ver una vez".
- Ubicación en tiempo real.
- Editar o eliminar un mensaje ya enviado.

---

## 9. Problemas comunes

| Lo que pasa | Lo más probable | Cómo se resuelve |
|---|---|---|
| No aparece el portafolio **Ferre Mayoreo** en la lista | La cuenta de Facebook con la que se inició sesión no tiene control total del portafolio | Iniciar sesión con otra cuenta o pedir el permiso ([sección 3.1](#31-control-total-en-el-portafolio-de-meta)) |
| Dice que el número **ya está conectado** a otra plataforma | El número sigue ligado a otra herramienta | Desconectarlo de ahí, esperar **10 a 15 minutos** y volver a intentar |
| El celular **no escanea el QR** o no muestra la opción | App desactualizada, o es WhatsApp normal y no Business | Actualizar WhatsApp Business y buscar en **Ajustes → Cuenta → Plataforma para empresas** |
| Pide **registrar el número por SMS o llamada** | Se eligió la ruta de API en lugar de la app existente | Cerrar la ventana sin terminar y repetir desde el paso 1, eligiendo **conectar la app existente** |
| Llegan **muchos avisos** de "conversación sin asignar" | Faltó configurar la asignación | Hacer la [sección 6](#6-asignar-las-conversaciones-al-vendedor) |
| El vendedor **no ve su bandeja** o no puede responder | No está en la lista de acceso de la bandeja | Bandeja → pestaña **Acceso** → agregarlo |
| La conversación **no se liga** a un contacto que sí existe | El teléfono del contacto no tiene el formato **+52** | Corregir el teléfono en el contacto o asociar la conversación a mano desde la bandeja |
| La conexión **se cayó** sola | La app pasó más de 14 días sin abrirse | Abrir la app y volver a conectar el número (sección 5) |
| No se puede cambiar la **foto o la descripción** desde HubSpot o Meta | En coexistencia el perfil pertenece a la app | Cambiarlo desde **WhatsApp Business** en el celular |

Si algo no se resuelve con esta tabla, lo revisamos juntos con el equipo de Black & Orange.

---

## 10. Cómo desconectar un número

Por ejemplo, si un vendedor deja la empresa o el celular cambia de uso. **Lo que ya llegó a HubSpot se queda guardado**; solo dejan de sincronizar las conversaciones nuevas.

**Desde el celular (la forma más directa):**

1. Abres **WhatsApp Business** → **Ajustes** → **Cuenta** → **Plataforma para empresas**.
2. Eliges HubSpot y lo **desconectas**.

**Desde HubSpot:**

1. Das clic en el **engrane de Configuración** → **Bandeja de entrada** (dentro de *Bandeja de entrada y centro de ayuda*).
2. Si hay varias bandejas, eliges la del vendedor en el menú de vista.
3. Pasas el cursor sobre el canal de WhatsApp, das clic en **Eliminar** y confirmas.

> [!TIP]
> Si el número se va a conectar de nuevo (por ejemplo, para un vendedor nuevo con ese mismo celular), conviene esperar **10 a 15 minutos** después de desconectarlo.

---

## 11. Checklist por número

Para palomear cada número conectado. Se puede imprimir o copiar a una hoja de cálculo.

| Vendedor | Bandeja creada | App Business actualizada | Conectado | Historial | Asignación | Prueba ida y vuelta | Fecha | Quién conectó |
|---|---|---|---|---|---|---|---|---|
| | ☐ | ☐ | ☐ | ☐ Sí ☐ No | ☐ | ☐ | | |
| | ☐ | ☐ | ☐ | ☐ Sí ☐ No | ☐ | ☐ | | |
| | ☐ | ☐ | ☐ | ☐ Sí ☐ No | ☐ | ☐ | | |
| | ☐ | ☐ | ☐ | ☐ Sí ☐ No | ☐ | ☐ | | |
| | ☐ | ☐ | ☐ | ☐ Sí ☐ No | ☐ | ☐ | | |
| | ☐ | ☐ | ☐ | ☐ Sí ☐ No | ☐ | ☐ | | |
| | ☐ | ☐ | ☐ | ☐ Sí ☐ No | ☐ | ☐ | | |
| | ☐ | ☐ | ☐ | ☐ Sí ☐ No | ☐ | ☐ | | |
| | ☐ | ☐ | ☐ | ☐ Sí ☐ No | ☐ | ☐ | | |

---

## Para leer más

- [Conectar un número de WhatsApp a HubSpot con coexistencia](https://knowledge.hubspot.com/es/inbox/connect-a-whatsapp-number-to-hubspot-using-coexistence) — artículo oficial de HubSpot (la versión en inglés es la más actualizada).
- [Conectar WhatsApp a la bandeja de entrada de conversaciones](https://knowledge.hubspot.com/inbox/connect-whatsapp-to-the-conversations-inbox) — artículo oficial de HubSpot.

*Las pantallas de HubSpot y de Meta cambian con frecuencia. Si algún nombre de botón no coincide, la idea de cada paso se mantiene igual.*
