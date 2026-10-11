---
layout: default
title: "Instalar Hark y Hermes Agent"
permalink: /instalar/
---

[← Portal](../)

# Instalar tu agente

## Hark · para todos los alumnos
Gratis en iPhone (iOS 17.6 o posterior), Android y web.

1. Descarga **Hark Pro**: [App Store](https://apps.apple.com/us/app/hark-pro/id6772362941) · [Google Play](https://play.google.com/store/apps/details?id=com.hark.android) · [web](https://www.hark.com/).
2. Crea tu cuenta con tu Gmail, el mismo del Classroom.
3. Opcional: conecta Google para que te ayude con Drive y Docs.
4. Primer encargo: «Soy alumno del Diplomado en Transformación Digital. Ayúdame a…».

## Hermes Agent · para alumnos avanzados (opcional)
Software libre (licencia MIT) de Nous Research. Funciona en tu computadora, en un servidor propio (VPS) o en Android con Termux.

**Linux, macOS o WSL2**
```bash
curl -fsSL https://hermes-agent.nousresearch.com/install.sh | bash
source ~/.bashrc
```

**Windows (PowerShell)**
```powershell
iex (irm https://hermes-agent.nousresearch.com/install.ps1)
```

**Elegir el modelo**
```bash
hermes setup --portal   # Nous Portal: una sola suscripción para modelo y herramientas
hermes model            # o tu propio proveedor
```

**Usarlo**
```bash
hermes          # conversar
hermes doctor   # diagnosticar problemas
hermes gateway setup   # WhatsApp o Telegram (Módulo 3, siempre con revisión humana)
```

**Android:** usa la [guía de Termux](https://hermes-agent.nousresearch.com/docs/getting-started/termux), no el instalador de computadora.

Más información: [guía rápida](https://hermes-agent.nousresearch.com/docs/getting-started/quickstart) · [repositorio](https://github.com/NousResearch/hermes-agent).

> Nunca pegues llaves de API ni contraseñas en el chat ni en el repositorio.
