---
layout: home
title: "Diplomado agéntico"
handle: "æ://neuromitosis/teotech · #OpenCourseWare 🏵️"
headline: "Una clase abierta puede viajar, reproducirse y mejorar."
lede: "🤳 Diplomado en Transformación Digital · Instituto Luterano Latinoamericano. Se multiplica la enseñanza. El humano conserva el criterio."
cycle: ["APRENDER","CONSTRUIR","COMPROBAR","ENSEÑAR"]
ticker:
  - {countdown: "2@19:00", label: "EN VIVO · MARTES 7 PM TEXAS"}
  - "AGENTE PROPONE → ALUMNO COMPRUEBA → HUMANO DECIDE"
  - "TUTOR æ EN TU TELÉFONO · SIN NUBE"
  - "ENTREGAS EN CLASSROOM"
  - "NUNCA PEGUES CONTRASEÑAS EN UN CHAT"
---

<div class="stats"><div class="stat"><b>4</b><span>MÓDULOS</span></div><div class="stat"><b>{{ site.clases | size }}</b><span>CLASES</span></div><div class="stat"><b>5</b><span>REPOS</span></div></div>

<div class="row"><button type="button" class="btn" data-fold-all>DESPLEGAR TODO +</button><button type="button" class="btn y" data-tutor-open>PREGÚNTALE A æ</button></div>

<details class="fold" id="empieza" open>
<summary><span class="n">01</span><span class="t">Empieza aquí<small>4 pasos · antes de la primera clase</small></span><span class="pm"></span></summary>
<div class="in-fold" markdown="1">
1. **Requisitos:** celular con datos o Wi-Fi, tu Gmail (el mismo del Classroom), el código del Classroom que te dio el docente y la Comunidad Tech de WhatsApp. Para el Módulo 2, una cuenta gratuita en GitHub.
2. **Tu agente:** instala Hark y escríbele «Hola, soy alumno del Diplomado en Transformación Digital». [Cómo instalar ›](instalar/)
3. **Primera práctica, 10 minutos:** haz una pregunta real de tu escuela, iglesia o negocio a Hark y a otra IA. Compara en qué coinciden y qué comprobarías primero. Anota qué propusieron, qué comprobaste y qué decidiste.
4. **Tu repo:** usa la plantilla, nómbrala `mi-diplomado` y sube el enlace a Classroom.

<div class="row"><a class="btn y" href="https://github.com/LutheranInstitute/mi-diplomado">USAR PLANTILLA ›</a><a class="btn" href="https://classroom.google.com/w/NzA3NjQyMTc1MzI2/t/all">CLASSROOM ›</a></div>

<div id="elearnlatam" style="margin:18px 0;padding:14px;border:3px solid #E8B400;background:#fff8e6;text-align:center">
<div class="lbl">æQR://elearnlatam/whatsapp</div>
<p><strong>Únete a #eLearnLATAM</strong> · el grupo de WhatsApp del Diplomado. Escanea o toca. <br><small>Join our WhatsApp group · scan or tap.</small></p>
<img src="/diplomado-agentico/assets/aeqr/elearnlatam-whatsapp.png" alt="æQR para unirte a #eLearnLATAM en WhatsApp" width="220" style="max-width:60%;height:auto;margin:6px auto;display:block">
<div class="row" style="justify-content:center"><a class="btn g" href="https://chat.whatsapp.com/IBfCSjTAA3h6OlppM8mUzh">UNIRME A #eLearnLATAM ›</a></div>
</div>

</div>
</details>

<details class="fold b" id="ruta">
<summary><span class="n">02</span><span class="t">Ruta<small>4 módulos · {{ site.clases | size }} clases</small></span><span class="pm"></span></summary>
<div class="in-fold" markdown="0">
{% assign mods = site.clases | sort: "orden" | group_by: "modulo" %}{% for m in mods %}
<div class="lbl">MÓDULO {{ m.name }}</div>
<ul class="mlist">{% for c in m.items %}<li><span class="s">{{ c.sesion }}</span>{% if c.ready %}<a href="{{ c.url | relative_url }}">{{ c.title }}</a>{% else %}<span class="soon">{{ c.title }}</span>{% endif %}</li>{% endfor %}</ul>
{% endfor %}
</div>
</details>

<details class="fold g" id="tareas">
<summary><span class="n">03</span><span class="t">Tareas<small>lo que se entrega · rúbricas de 100</small></span><span class="pm"></span></summary>
<div class="in-fold" markdown="1">
| Tarea | Entrega |
|---|---|
| M1 · Bitácora de supervisión | Doc con 3 encargos: qué propuso, qué comprobaste, qué decidiste |
| M4 · T1 · Repo con historia | README y 3 commits claros |
| M4 · T2 · Colaborar | Revisión en el repo de un compañero |
| M4 · T3 · Commit con agente | Cambio propuesto por agente, revisado por ti |
| Proyecto final | Sitio en GitHub Pages útil para tu comunidad |

Rúbrica del proyecto: historia clara 25 · uso crítico del agente 25 · pertinencia 25 · colaboración y revisión 25.

<div class="row"><a class="btn g" href="https://classroom.google.com/w/NzA3NjQyMTc1MzI2/t/all">ENTREGAR EN CLASSROOM ›</a><a class="btn" href="app/">RÚBRICAS COMPLETAS ›</a></div>
</div>
</details>

<details class="fold" id="agentes">
<summary><span class="n">04</span><span class="t">Agentes<small>Hark · Hermes · tutor æ</small></span><span class="pm"></span></summary>
<div class="in-fold" markdown="1">
- **Hark:** para todos. Gratis en iPhone, Android y web.
- **Hermes Agent:** opcional para avanzados. Software libre en tu computadora, un VPS o Termux.
- **Tutor æ:** corre dentro de tu navegador con WebGPU. Lee la página que estás viendo.

<div class="row"><a class="btn b" href="instalar/">INSTALAR ›</a><button type="button" class="btn" data-copy="curl -fsSL https://hermes-agent.nousresearch.com/install.sh | bash">COPIAR HERMES</button></div>
</div>
</details>

<details class="fold k" id="regla">
<summary><span class="n">05</span><span class="t">Regla de ejecución<small>cómo trabajamos con agentes</small></span><span class="pm"></span></summary>
<div class="in-fold" markdown="1">
**Descubrir → preparar → revisión humana → ejecutar → conservar evidencia.**

Piezas comunes: meta, contexto, memoria, habilidades, herramientas y permiso humano. Ningún agente califica, borra ni entrega por ti.

> Evidencia ≠ autoridad: la supervisión informa, el humano decide.
</div>
</details>

<details class="fold b" id="toolchain">
<summary><span class="n">06</span><span class="t">Toolchain<small>repos · herramientas · todo abierto</small></span><span class="pm"></span></summary>
<div class="in-fold" markdown="1">
**Repositorios**

| Repo | Para qué |
|---|---|
| [diplomado-agentico](https://github.com/LutheranInstitute/diplomado-agentico) | Este portal: clases, tareas, licencia |
| [mi-diplomado](https://github.com/LutheranInstitute/mi-diplomado) | Plantilla del alumno: README, AGENTS, REFLEXION |
| [teotech-theme](https://github.com/LutheranInstitute/teotech-theme) | Theme 9:16 con WebGPU y tutor æ |
| [escuela-teologia](https://github.com/LutheranInstitute/escuela-teologia) | Escuela de Teología: Catecismo Menor |
| [biblioteca-luterana](https://github.com/LutheranInstitute/biblioteca-luterana) | Fuentes: Enchiridion, Confesiones |

**Herramientas**

| Capa | Herramienta |
|---|---|
| Aprender | Google Classroom · Comunidad Tech en WhatsApp |
| Agentes | Hark · Hermes Agent · tutor æ |
| IA local | WebGPU · WebLLM · Qwen2.5 0.5B |
| Construir | Git · GitHub · Markdown |
| Publicar | GitHub Pages · Jekyll |
| Comprobar | Historial de commits · revisión humana |

```text
>_ aprender → construir → comprobar → enseñar ↺
```

<div class="row"><a class="btn y" href="https://github.com/LutheranInstitute/mi-diplomado">USAR PLANTILLA ›</a><a class="btn" href="https://lutheraninstitute.github.io/teotech-theme/">VER THEME ›</a><button type="button" class="btn" data-copy="git clone https://github.com/LutheranInstitute/mi-diplomado.git">COPIAR CLONE</button></div>
</div>
</details>

<details class="fold g" id="teologia">
<summary><span class="n">07</span><span class="t">Escuela de Teología<small>Catecismo Menor · sábados 7 PM Texas</small></span><span class="pm"></span></summary>
<div class="in-fold" markdown="1">
La misma escuela, otra materia: **aprender → construir → comprobar → enseñar** con el Catecismo Menor de Lutero. Híbrido y virtual por Zoom + Hark Pro, de 3 a 103 años.

> La Escritura es la norma; Hark solo ayuda; el humano decide.

<div class="row"><a class="btn g" href="https://lutheraninstitute.github.io/escuela-teologia/">ENTRAR A TEOLOGÍA ›</a><a class="btn" href="https://classroom.google.com/c/ODA2NjU2ODIxNTg0?cjc=edejxhep">CLASSROOM TEOLOGÍA ›</a><a class="btn" href="https://lutheraninstitute.github.io/teologia/">BIBLIOTECA LUTERANA ›</a></div>
</div>
</details>

<div class="row"><a class="btn" href="app/">ABRIR APP CLÁSICA ›</a><a class="btn" href="licencia/">LICENCIA</a></div>
