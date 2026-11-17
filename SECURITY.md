# Seguridad / Security

**Español** · [English](#english)

## Español

### Modelo de amenaza

SenySync Studio se ejecuta **enteramente en tu navegador**. No hace peticiones de red, no tiene servidor, no tiene cuentas y no envía telemetría. Tus archivos nunca salen de tu máquina.

Superficie real de entrada:
- Archivos SVG importados → se sanitizan: se eliminan `script`, `foreignObject`, `style`, `animate`, `animateTransform`, `animateMotion`, `set`, atributos `on*`, `javascript:` y referencias externas. Si se retira CSS incrustado, se avisa.
- JSON importado → se normalizan claves, se limpian caracteres de control y marcas bidi, y se extrae de bloques de código o prosa.
- Todo texto de usuario se escapa antes de insertarse en el DOM.
- Los registros locales opcionales viven en claves separadas del proyecto y nunca guardan contenido de la obra.

### Reportar una vulnerabilidad

**No abras un Issue público con detalles de explotación.** Abre un Issue titulado `SECURITY: contacto privado` sin detalles, y se te indicará un canal privado.

Incluye después: versión, navegador, pasos de reproducción y un archivo mínimo que lo demuestre.

### Versiones soportadas

| Versión | Soporte |
|---|---|
| v1 · Build 1 | ✅ |

---

<a name="english"></a>

## English

### Threat model

SenySync Studio runs **entirely in your browser**. It makes no network requests, has no server, no accounts and sends no telemetry. Your files never leave your machine.

Real input surface:
- Imported SVG files → sanitized: `script`, `foreignObject`, `style`, `animate`, `animateTransform`, `animateMotion`, `set`, `on*` attributes, `javascript:` and external references are removed. If embedded CSS is stripped, the user is warned.
- Imported JSON → keys normalized, control characters and bidi marks stripped, extracted from code blocks or prose.
- All user text is escaped before being inserted into the DOM.
- Optional local ledgers live under keys separate from the project and never store work content.

### Reporting a vulnerability

**Do not open a public Issue with exploitation details.** Open an Issue titled `SECURITY: private contact` with no details, and you will be given a private channel.

Then include: version, browser, reproduction steps and a minimal file that demonstrates it.

### Supported versions

| Version | Support |
|---|---|
| v1 · Build 1 | ✅ |