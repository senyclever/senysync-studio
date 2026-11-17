# Contribuir / Contributing

**Español** · [English](#english)

## Español

¡Gracias por tu interés! Este proyecto es un solo archivo HTML sin dependencias, y eso es una decisión de diseño, no una limitación.

### Reglas que no se negocian

1. **Versión y build se mantienen en "1"**.
2. **Sin librerías externas, sin CDNs, sin peticiones de red.**
3. **Todo texto de interfaz en español e inglés** vía `L(es, en)`. Ninguna tercera lengua.
4. **ES5**: `var`, `function`, concatenación de strings. Sin sintaxis moderna.
5. **Una sola función de layout** para texto, alimentando canvas y SVG. No se rompe la paridad.
6. La IA **nunca** dibuja texto, animación, partículas, glow ni desenfoque.
7. El blindaje es de **solo lectura y no bloqueante**.
8. Cada cambio añade pruebas al Self-Test y declara el número esperado.
9. Optimiza para **teléfono**: objetivos táctiles, filas que envuelven, scroll contenido.
10. Sin ternarios anidados dentro de concatenaciones HTML de botones.

### Cómo proponer un cambio

1. Abre un Issue describiendo el problema o la mejora.
2. Si es un fallo, incluye: navegador, sistema, pasos exactos y el resultado del Self-Test.
3. Para código, envía reemplazos aislados con ancla única verificada, no archivos enteros reescritos.
4. Comprueba que el ancla aparece **una sola vez** en el archivo, contando también los literales dentro de los tests.
5. Ejecuta el Self-Test y reporta el número: `📤 Exportar → 🧪 Self-Test`.

Al contribuir, aceptas que tu aportación se licencie bajo Apache License 2.0.

---

<a name="english"></a>

## English

Thanks for your interest! This project is a single HTML file with no dependencies, and that is a design decision, not a limitation.

### Non-negotiable rules

1. **Version and build stay at "1"**.
2. **No external libraries, no CDNs, no network requests.**
3. **Every UI string in Spanish and English** via `L(es, en)`. No third language.
4. **ES5**: `var`, `function`, string concatenation. No modern syntax.
5. **One layout function** for text, feeding canvas and SVG. Parity is never broken.
6. The AI **never** draws text, animation, particles, glow or blur.
7. The armor is **read-only and non-blocking**.
8. Every change adds Self-Test cases and states the expected number.
9. Optimize for **phone**: tap targets, wrapping rows, contained scroll.
10. No nested ternaries inside HTML button concatenation.

### How to propose a change

1. Open an Issue describing the problem or improvement.
2. For bugs include: browser, OS, exact steps and the Self-Test result.
3. For code, send isolated replacements with a verified unique anchor, not rewritten whole files.
4. Check the anchor appears **exactly once** in the file, counting literals inside the tests too.
5. Run the Self-Test and report the number: `📤 Export → 🧪 Self-Test`.

By contributing you agree your contribution is licensed under the Apache License 2.0.