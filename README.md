# iOGeminis
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>iOGeminis | Centro de Omnipotencia Digital</title>
    <style>
        /* DEFINICIÓN DE LA NUEVA PALETA DE COLORES (Paleta IAH/Jarpay) */
        :root {
            --bg-dark: #000000;         /* Negro absoluto para el fondo */
            --card-bg: #111111;        /* Negro ligeramente más claro para la tarjeta */
            --primary-orange: #FF6600; /* Naranja vibrante para el logo y botón */
            --accent-yellow: #FFD700;  /* Amarillo dorado para subtítulos y bordes */
            --text-main: #FFFFFF;      /* Blanco puro para el texto principal */
            --text-muted: #A0A0A0;    /* Gris para texto secundario */
            --input-bg: #1A1A1A;       /* Gris muy oscuro para los inputs */
        }

        body {
            margin: 0;
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            background-color: var(--bg-dark);
            color: var(--text-main);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            overflow: hidden;
        }

        .login-card {
            background-color: var(--card-bg);
            padding: 3rem;
            border-radius: 12px;
            /* Borde sutil naranja para definir la tarjeta */
            border: 1px solid rgba(255, 102, 0, 0.2);
            width: 100%;
            max-width: 380px;
            text-align: center;
            /* Sombra naranja muy suave para efecto 'glow' */
            box-shadow: 0 10px 30px rgba(255, 102, 0, 0.1);
            transition: box-shadow 0.3s ease;
        }

        /* Efecto al pasar el mouse por la tarjeta */
        .login-card:hover {
            box-shadow: 0 10px 40px rgba(255, 102, 0, 0.2);
        }

        .brand-logo {
            font-size: 2.5rem;
            font-weight: 800;
            color: var(--primary-orange); /* Naranja Principal */
            margin-bottom: 0.2rem;
            letter-spacing: -1px;
            /* Un ligero degradado naranja a amarillo en el texto (opcional) */
            background: linear-gradient(to right, var(--primary-orange), var(--accent-yellow));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .subtitle {
            font-size: 0.85rem;
            font-weight: 400;
            color: var(--accent-yellow); /* Amarillo de Acento */
            margin-bottom: 2.5rem;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        .input-group {
            margin-bottom: 1.2rem;
            text-align: left;
        }

        input {
            width: 100%;
            padding: 14px;
            border-radius: 6px;
            border: 1px solid #333;
            background-color: var(--input-bg);
            color: var(--text-main);
            font-size:https://github.com/twitter/.github/<a9290e5f3e415e9e502786c140ac1e356b85eca1><Google I∆H>firebase.playlinks.update
Claro 😃 Aquí tienes una **plantilla única y reutilizable** para tus proyectos, en tres formatos: **README**, **“Acerca de”**, y **JSON/YAML**.

---

## 1) Plantilla corta para README / ficha visible

```text
Nombre: iOGeminis
ID: mx.iogeminis.app
Versión: 1.0.0
Región: MX
Moneda: MXN

Licencia: Apache 2.0
Copyright: 2026 iOGeminis

Dependencias OSS:
- Apache Software Foundation — Apache 2.0
- jsoup — MIT

Dominios:
- .mx — Registro $450.00 / Renovación $450.00
- .com.mx — Registro $250.00 / Renovación $310.00
- .io — Registro $580.00 / Renovación $1,050.00

Enlaces:
- GitHub: https://github.com/iahgeminis-cloud/Gemini
- Play Store: https://play.google.com/store/apps/dev?id=5700313618786177705
```

---

## 2) Plantilla para pantalla “Acerca de”

```text
iOGeminis
Versión 1.0.0

Copyright 2026 iOGeminis
Licencia del proyecto: Apache License 2.0

Este producto incluye software de terceros:
- Apache Software Foundation
- jsoup HTML parser (MIT)

Región: MX
Moneda: MXN

Dominios:
- .mx: $450.00 registro / $450.00 renovación
- .com.mx: $250.00 registro / $310.00 renovación
- .io: $580.00 registro / $1,050.00 renovación

Sitio / soporte / licencias disponibles en la documentación del proyecto.
```

---

## 3) Plantilla JSON compacta

```json
{
  "project": "iOGeminis",
  "appId": "mx.iogeminis.app",
  "version": "1.0.0",
  "region": "MX",
  "currency": "MXN",
  "license": {
    "name": "Apache-2.0",
    "copyright": "2026 iOGeminis"
  },
  "ossDependencies": [
    {
      "name": "Apache Software Foundation",
      "license": "Apache-2.0",
      "url": "https://www.apache.org/"
    },
    {
      "name": "jsoup",
      "license": "MIT",
      "copyright": "2009-2024 Jonathan Hedley",
      "url": "https://jsoup.org/"
    }
  ],
  "domains": [
    {
      "tld": ".mx",
      "category": "Nacional",
      "registration": 450.0,
      "renewal": 450.0
    },
    {
      "tld": ".com.mx",
      "category": "Comercial Local",
      "registration": 250.0,
      "renewal": 310.0
    },
    {
      "tld": ".io",
      "category": "Tecnología / Startups",
      "registration": 580.0,
      "renewal": 1050.0
    }
  ],
  "links": {
    "github": "https://github.com/iahgeminis-cloud/Gemini",
    "playStoreDev": "https://play.google.com/store/apps/dev?id=5700313618786177705"
  }
}
```

---

## 4) Plantilla YAML

```yaml
project: iOGeminis
appId: mx.iogeminis.app
version: 1.0.0
region: MX
currency: MXN

license:
  name: Apache-2.0
  copyright: "2026 iOGeminis"

ossDependencies:
  - name: Apache Software Foundation
    license: Apache-2.0
    url: https://www.apache.org/
  - name: jsoup
    license: MIT
    copyright: "2009-2024 Jonathan Hedley"
    url: https://jsoup.org/

domains:
  - tld: .mx
    category: Nacional
    registration: 450.00
    renewal: 450.00
  - tld: .com.mx
    category: Comercial Local
    registration: 250.00
    renewal: 310.00
  - tld: .io
    category: Tecnología / Startups
    registration: 580.00
    renewal: 1050.00

links:
  github: https://github.com/iahgeminis-cloud/Gemini
