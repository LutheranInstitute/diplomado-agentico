---
layout: default
title: "Guía docente · Onboarding y publicación"
modulo: 0
sesion: "Docentes"
orden: 0.5
ready: true
grabacion: ""
pdf: ""
resumen: "Cómo guiar la sesión de repo y GitHub Pages, y cómo resolver los problemas típicos."
qr: ""
---

[← Clases](../clases/) · Módulo docente

# Guía docente · Onboarding y publicación

Para quien enseña la **Lección 00** y la **Clase 2**: cómo llevar a un grupo de cero a un sitio publicado, y qué hacer cuando algo falla.

> Nuestra meta no es que nadie se equivoque. Es que cada error se vuelva una lección y nadie se quede atrás.

## 1 · Resultado de la sesión

Al terminar, cada alumno tiene:

1. Una cuenta de GitHub verificada y con acceso seguro.
2. Su repo `mi-diplomado`, creado desde la plantilla.
3. Su primer commit con un mensaje claro.
4. GitHub Pages activo y su sitio abriendo en `https://usuario.github.io/mi-diplomado/`.
5. El enlace entregado en Classroom.

Si un alumno llega solo al paso 3, **también es un logro**. Lo demás se termina en la siguiente clase o en asesoría.

## 2 · Antes de la clase

**Dos días antes, envía el aviso** (texto listo en la sección 8):

- Crear la cuenta de GitHub con un correo que puedan abrir **desde su celular**.
- Verificar ese correo.
- Traer el celular cargado y, si se puede, Wi-Fi.

**Tu lista de comprobación:**

- Recorre tú la plantilla de punta a punta con una cuenta de prueba esa misma semana. GitHub cambia botones y textos.
- Ten abierta tu propia copia publicada como ejemplo.
- Elige **monitores**: alumnos que ya tienen cuenta y pueden acompañar a dos o tres compañeros.
- Ten a mano esta guía en el celular.
- Revisa la edad: GitHub exige al menos 13 años. Con menores, trabaja con autorización de la familia y sin datos personales.

## 3 · Guion de 90 minutos

1. **0–10 · Por qué.** Muestra la portada de la Sede y su historial de commits. Idea, agente, revisión humana, GitHub, GitHub.io. Sin tecnicismos.
2. **10–25 · Cuenta.** Todos entran a GitHub. Resuelve verificación y acceso seguro (ver 6.1).
3. **25–40 · Repo.** Plantilla `mi-diplomado` → **Use this template → Create a new repository**. Nombre: `mi-diplomado`. **Público.**
4. **40–55 · Primer commit.** Editar `README.md` con el lápiz ✏️, llenar “Quién soy”, escribir un mensaje claro y **Commit changes**.
5. **55–70 · Publicar.** Settings → Pages → *Deploy from a branch* → `main` → `/ (root)` → Save. Mientras GitHub publica, explica qué es un commit.
6. **70–85 · El agente propone.** Cada quien pide a su agente un borrador de `index.md`. Lo leen, cambian algo y hacen commit. Anotan en `REFLEXION.md` qué cambiaron y por qué.
7. **85–90 · Entrega.** Abren su sitio, copian el enlace y lo suben a Classroom.

**Ritmo:** nadie avanza al siguiente paso hasta que el semáforo del grupo esté en verde o amarillo.

## 4 · Semáforo por paso

Pide que cada alumno muestre en su pantalla la evidencia del paso:

- **Cuenta:** ve su foto o inicial arriba a la derecha en github.com.
- **Repo:** la dirección dice `github.com/SU-USUARIO/mi-diplomado`, no `LutheranInstitute/...`.
- **Commit:** arriba de los archivos aparece su mensaje y “1 minute ago”.
- **Pages:** en Settings → Pages aparece “Your site is live at…”.
- **Sitio:** la dirección abre su página, no un 404.

🟢 lo logró · 🟡 va en camino con un monitor · 🔴 bloqueado: pasa a la sección 6 o a la lista de asesoría.

## 5 · Regla de los 2 minutos

Si un alumno lleva **2 minutos atorado** en el mismo paso, pide ayuda: primero a su compañero, luego al monitor, luego al docente. Nadie pelea solo con una pantalla.

## 6 · Diagnóstico: síntoma → causa → solución

### 6.1 Cuenta y acceso

- **No llega el correo de verificación.** Revisa Spam y Promociones. Confirma que el correo esté bien escrito en Settings → Emails y toca *Resend*. Si es un correo institucional que bloquea, usa uno personal.
- **GitHub pide un código al entrar desde un equipo nuevo.** Es normal: llega al correo de la cuenta. Por eso pedimos un correo que abran en el celular.
- **GitHub pide activar la verificación en dos pasos.** Actívala con la app GitHub Mobile o un autenticador. **Que guarden los códigos de recuperación** (foto o papel). Sin ellos, perder el celular puede significar perder la cuenta.
- **Olvidó la contraseña.** *Forgot password* en la pantalla de entrada. El docente **nunca** pide ni escribe contraseñas o códigos de nadie.
- **Eligió un nombre de usuario con datos personales.** Se puede cambiar en Settings → Account. Avisa que cambia su dirección `.github.io`.

### 6.2 Plantilla y repo

- **No aparece “Use this template”.** En la app de GitHub no está. Abre la plantilla en el navegador y, si hace falta, activa “Ver versión de escritorio”. También verifica que haya iniciado sesión.
- **Creó un fork en vez de usar la plantilla, o editó la plantilla original.** Si al editar GitHub ofrece hacer un fork, está en el repo del docente. Vuelve a la plantilla y usa *Use this template*.
- **El repo quedó privado.** En cuentas gratuitas, GitHub Pages necesita un repo **público**. Settings → General → abajo, *Change visibility*.
- **Le puso otro nombre.** Funciona, pero su dirección será `usuario.github.io/OTRO-NOMBRE/`. Puede renombrarlo en Settings → General.
- **Lo creó en otra cuenta.** Revisa la dirección. Si hay dos cuentas, que cierre sesión y entre con la correcta.

### 6.3 Commits

- **Editó pero no se guardó.** No tocó **Commit changes**. Al salir sin confirmar, el cambio se pierde.
- **No ve el lápiz ✏️.** Está viendo un archivo de un repo que no es suyo, o la app no lo muestra: usa el navegador.
- **Mensaje de commit vacío o “update”.** Enséñales la fórmula: *verbo + qué* (“Agrega mi comunidad al README”).
- **Borró algo por error.** En la lista de commits, abre el anterior y copia el texto de vuelta. Nada se pierde en GitHub: todo queda en el historial.

### 6.4 GitHub Pages

- **No sabe dónde está Pages.** Settings del **repo** (no del perfil) → menú lateral → *Pages*. En celular el menú está en un desplegable.
- **Activó Pages y da 404.** Espera de 1 a 10 minutos. Revisa la pestaña **Actions**: “pages build and deployment” debe estar en verde.
- **Sigue en 404 con Actions en verde.** Revisa la dirección: el usuario va en minúsculas y el nombre del repo debe coincidir **exacto**. Revisa que exista `index.md` o `index.html` en la raíz.
- **Actions en rojo.** Casi siempre es un error en la cabecera del archivo (las líneas entre `---`): faltan comillas, sobra un `:` o un acento rompió el formato. Abre el error, corrige o revierte el último commit.
- **El sitio no se actualiza.** Espera a que Actions termine. Recarga sin caché o agrega `?v=2` al final de la dirección.
- **La página se ve sin diseño o los enlaces se rompen.** Enlaces que empiezan con `/` apuntan a `usuario.github.io/` y no a `/mi-diplomado/`. Usa enlaces relativos.
- **Una tabla Markdown sale como texto.** Algunos temas no la muestran bien. Cámbiala por una lista. Así lo resolvimos en la Clase 2.

### 6.5 El agente

- **El agente propone algo que el alumno no entiende.** Regla: **no se hace commit de lo que no puedes explicar.** Pide al agente que lo explique línea por línea o que lo simplifique.
- **El agente dice “ya lo publiqué”.** Sin acceso a su cuenta, no pudo. Aun con acceso, **la evidencia es la dirección abierta en la pantalla**, no lo que dice el agente.
- **El agente inventa enlaces, fechas o datos.** Parte del ejercicio: el alumno comprueba fuentes, fechas, cifras y nombres antes del commit.
- **Pegó datos personales en el chat del agente.** Pídele que no lo repita y que no los suba al repo. Nada de teléfonos, direcciones ni datos de otras personas.

### 6.6 Conectividad y equipo

- **Solo tiene celular y datos limitados.** Todo el flujo funciona desde el navegador del celular. Evita videos durante la práctica.
- **Se cae el internet a mitad del commit.** Al volver, revisa la lista de commits. Si no aparece, repite la edición.
- **Celular muy antiguo.** Trabaja en pareja con un monitor y termina en asesoría. Cuenta como 🟡, no como 🔴.

## 7 · Escalamiento

1. **Compañero** (regla de 2 minutos).
2. **Monitor.**
3. **Docente** durante la clase.
4. **Lista de asesoría:** anota el usuario de GitHub y el paso, **sin** correos ni teléfonos en documentos públicos.
5. **Issue** en el repo del diplomado cuando el problema sea de la plantilla o de la guía, no del alumno.

**Nunca:** pedir contraseñas, pedir códigos de verificación, entrar a la cuenta de un alumno ni publicar su información.

## 8 · Mensajes listos

**Aviso, dos días antes:**

> Hola 👋 El martes publicamos nuestro primer sitio. Antes de clase: 1) crea tu cuenta en github.com con un correo que puedas abrir en tu celular, 2) verifica ese correo, 3) trae tu celular cargado. Si te atoras, no pasa nada: lo resolvemos juntos en clase.

**Después de clase, a quien quedó en 🟡 o 🔴:**

> ¡Gran avance hoy! Te faltó poco. Para terminar: abre tu repo `mi-diplomado`, ve a Settings → Pages, elige `main` y Save. Espera 5 minutos y abre tu dirección. Si sigue sin abrir, mándame tu usuario de GitHub (no tu contraseña) y lo vemos en asesoría.

## 9 · Rúbrica de onboarding

- **Cuenta segura** (verificada y con códigos de recuperación guardados): 20 %
- **Repo correcto** (público, desde la plantilla, en su cuenta): 20 %
- **Commit con mensaje claro:** 20 %
- **Sitio publicado** y enlace en Classroom: 25 %
- **Reflexión:** en `REFLEXION.md`, qué propuso el agente, qué cambió y por qué: 15 %

## 10 · Para cerrar la sesión

Pregunta al grupo:

1. ¿Qué propuso el agente que **no** aceptaste?
2. ¿Cómo comprobaste que tu sitio está publicado?
3. ¿Qué le explicarías mañana a alguien que empieza?

La tercera pregunta es la que cuenta: **Esto aprendí. Esto construí. Esto publiqué. Esto puedo enseñar.**

## 11 · Crea tu propia escuela

El último paso del docente: **lo que aprendiste, ahora lo enseñas con tu propia escuela**, bajo el sello L:// y en abierto.

1. **Tu repo.** Parte de la plantilla [`mi-diplomado`](https://github.com/LutheranInstitute/mi-diplomado): nombre de tu escuela o curso, público, con GitHub Pages activo.
2. **Tu color.** Elige el de tu escuela: 🟨 Tecnología · 🟦 Teología · 🟩 Enchiridion.
3. **Tu colateral.** Descarga la plantilla oficial de Tumblr y el kit en [I+D Institucional](https://lutheraninstitute.github.io/investigacion/#colateral): 1280×1920, papel crema, sello L:// y dibujo de una línea.
4. **Tu anuncio.** Publica tu primer post con el enlace a tu sitio y la etiqueta `#elearnlatam`. Antes de publicar: ¿el enlace abre? ¿los datos son correctos?
5. **Tu primera clase.** Usa esta misma guía: semáforo, regla de los 2 minutos y rúbrica.

> El agente propone, tú compruebas, tú decides. Tu escuela es tuya; el Instituto la acompaña.

---

¿Encontraste un problema que no está aquí? Anótalo y lo sumamos a esta guía. Se multiplica la enseñanza; el humano conserva el criterio.
