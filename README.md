# Luca Baello

<p align="left">
  <a href="https://lucabaello1998.github.io/"><b>🌐 Portfolio</b></a> •
  <a href="#-español"><b>Español 🇦🇷</b></a> • 
  <a href="#-english"><b>English 🇺🇸</b></a>
</p>

---

## 🇦🇷 Español

¡Hola! Soy **Luca Baello**, Desarrollador **Fullstack SSR** enfocado en arquitecturas escalables, sistemas web de punta a punta y flujos de ingeniería potenciados con **IA aplicada** (orquestación multiagente, tooling y métricas de rendimiento).

> 🟢 **Abierto a nuevas oportunidades** — Fullstack SSR (React / Next.js + .NET), remoto o híbrido desde Buenos Aires.
> Escribime a [luca.baello@gmail.com](mailto:luca.baello@gmail.com) o por [LinkedIn](https://www.linkedin.com/in/luca-baello).

Actualmente curso la **Licenciatura en Informática** en la Universidad Nacional de Hurlingham (UNAHUR). Radicado en Buenos Aires, Argentina.

### 🚀 Stack Técnico

* **Backend**: .NET 8 / ASP.NET Core, C#, EF Core, SQL Server, PostgreSQL / PostGIS, SignalR, SQLite, PHP 8.3 / Laravel 12, Arquitectura Limpia / Capas, REST APIs, JWT & Auth flows.
* **Frontend**: React 19, Next.js 15, TypeScript, Vite, Tailwind CSS, PrimeReact, Material UI, Zustand.
* **Mobile / PWA**: Flutter (Riverpod), Capacitor, Progressive Web Apps offline-first.
* **Tooling & AI**: Orquestación de agentes (Claude Code, OpenCode, Codex, Gemini), automatización de testing, optimización de consumo de tokens, MCP servers.

### 🧪 Cómo trabajo

* **Producto completo, no un snippet**: cada repo tiene API, UI, tests y una guía de uso y despliegue.
* **Calidad verificable**: 15 repos con CI en verde y más de 1.000 pruebas automáticas (xUnit, pytest, PHPUnit, Dart, Vitest, node --test).
* **Decisiones documentadas**: los README explican por qué está hecho así y qué límites tiene.

### 🛠️ Proyectos Destacados

* 🧺 **[LavAR](https://github.com/lucabaello1998/LavAR)** · *nuevo*  
  La lavandería de barrio deja el cuaderno: API .NET 8 + panel React donde el mostrador carga el pedido, y el cliente lo sigue con un **código de 6 letras** (`/p/K7M2QP`), sin descargar nada ni registrarse. Precio congelado al recibir, estados con reglas (no se entrega algo que no está listo), avisos por WhatsApp con el mensaje ya escrito y Docker de una sola imagen con SQLite. 68 tests y consultas públicas con rate limit.
* 🕒 **[fichada](https://github.com/lucabaello1998/fichada)** *nuevo*  
  Demo de fichaje laboral para una pyme: el empleado ficha entrada/salida desde el celular, la app valida el perímetro de la sucursal con haversine y el encargado ve las horas de la semana con extras pasadas las 8 h/día. React 19 + Vite + TypeScript, reglas de negocio en un módulo puro y testeado (18 tests), datos en el navegador. No es un control de asistencia real: el GPS del navegador se puede falsear, y el README lo dice.
* 🧾 **[facturacion-ar](https://github.com/lucabaello1998/facturacion-ar)**  
  Librería .NET 8 para facturación electrónica argentina: arma y firma el TRA de WSAA (PKCS#7), cachea token y sign y pide el CAE por WSFEv1 sin escribir SOAP a mano. Incluye un mock de AFIP para trabajar sin certificado: 29 tests. Sin credenciales en el repo y con el detalle de qué falta para producción.
* 📝 **[engineering-notes](https://github.com/lucabaello1998/engineering-notes)**  
  Cuaderno de notas de ingeniería con síntoma, causa, arreglo y cómo detectarlo la próxima vez. Cada nota cita el repo y el commit donde se arregló: chips que necesitaban dos toques, MediaWiki que corta en 500 categorías, un MCP que se rompe con un `console.log`.
* 🧱 **[FieldOps](https://github.com/lucabaello1998/fieldops-modernization)** • [Presentación](https://github.com/lucabaello1998/fieldops-modernization/blob/main/docs/FieldOps.pptx)  
  Modernización de un sistema de gestión de campo en producción (PHP 7.4 + jQuery, 76 tablas sin claves foráneas, 11,3 M de filas) a Laravel 12 + PHP 8.3 + MySQL 8: el esquema real migrado sin recortes, Kanban con drag & drop validado en el servidor y 62 tests de feature sobre MySQL real, con demo reproducible en Docker y CI que corre tests + 10 verificaciones e2e con Chrome headless.
* 🔍 **[legacy-lens](https://github.com/lucabaello1998/legacy-lens)** • [Informe de ejemplo](https://lucabaello1998.github.io/legacy-lens/)  
  CLI en Python que radiografía un sistema legacy PHP/MySQL en un comando: lee el dump, reconstruye las relaciones que nunca se documentaron, detecta SQL concatenado, funciones extintas y secretos hardcodeados, y devuelve un **índice de dolor de migración** con plan de acción. 24 reglas, 70 tests, Docker y salida HTML/JSON/Markdown. Los snippets salen con los literales tapados: el informe se puede compartir sin filtrar una contraseña.
* 💸 **[sueldos-ar](https://github.com/lucabaello1998/sueldos-ar)** • [Observatorio](https://lucabaello1998.github.io/sueldos-ar/)  
  Motor de liquidación argentino en .NET 8 con la ley como dato: SAC, vacaciones, aportes, ganancias e indemnizaciones, 77 tests xUnit + 101 de Python y base legal por concepto. Incluye un observatorio que releva ofertas tech cada semana y publica el hallazgo incómodo: la mayoría no declara sueldo y las que lo declaran suelen publicar montos de relleno.
* 🎛️ **[OpenCockpit](https://github.com/lucabaello1998/OpenCockpit)** • [Descargar](https://github.com/lucabaello1998/OpenCockpit/releases/latest)  
  Dashboard de escritorio (Electron 44 + React 19 + Vite) multi-herramienta: audita de forma 100% local sesiones, tokens, costos y conversaciones de Claude Code, OpenCode, Codex, Gemini/Antigravity, Copilot, Cursor y Cline/Roo Code sin backend ni telemetría. 323 comprobaciones de seguridad y correctitud en su suite.
* 📦 **[FletAR](https://github.com/lucabaello1998/FletAR)**  
  Marketplace de fletes y logística liviana en Argentina. Backend desacoplado en .NET 8 + PostGIS + SignalR con cliente mobile en Flutter (Riverpod): subasta a ciegas, chat por oferta y GPS en vivo con autorización explícita.
* ⚡ **[ai-progress](https://github.com/lucabaello1998/ai-progress)**  
  Widget flotante para Windows y Linux que muestra el progreso de tareas de agentes de IA (`status.json`), uso de Claude/Codex/OpenCode y límites, sin telemetría.
* 🗺️ **[direcciones_ar](https://github.com/lucabaello1998/direcciones_ar)**  
  Paquete de Dart para autocompletado y geocodificación inversa de direcciones argentinas con Nominatim: caché LRU, rate limit y parseo en calle, altura, barrio y localidad.
* 🧪 **[liquid-glass-lab](https://github.com/lucabaello1998/liquid-glass-lab)**  
  Laboratorio experimental de UI: refracción SVG en runtime (`feDisplacementMap` + SDF), React 19, Tailwind v4 y dnd-kit.

### 📫 Contacto

* **Portfolio**: [lucabaello1998.github.io](https://lucabaello1998.github.io/)
* **LinkedIn**: [in/luca-baello](https://www.linkedin.com/in/luca-baello)
* **Email**: [luca.baello@gmail.com](mailto:luca.baello@gmail.com)
* **Ubicación**: Buenos Aires, Argentina

---

## 🇺🇸 English

Hi there! I'm **Luca Baello**, a **Fullstack SSR Developer** focused on scalable end-to-end web architectures and software engineering workflows augmented with **applied AI** (multi-agent orchestration, custom developer tooling, and performance/token benchmarking).

> 🟢 **Open to new opportunities** — Fullstack SSR (React / Next.js + .NET), remote or hybrid from Buenos Aires.
> Reach me at [luca.baello@gmail.com](mailto:luca.baello@gmail.com) or on [LinkedIn](https://www.linkedin.com/in/luca-baello).

Currently pursuing a **B.S. in Computer Science** at Universidad Nacional de Hurlingham (UNAHUR). Based in Buenos Aires, Argentina.

### 🚀 Tech Stack

* **Backend**: .NET 8 / ASP.NET Core, C#, EF Core, SQL Server, PostgreSQL / PostGIS, SignalR, SQLite, PHP 8.3 / Laravel 12, Clean Architecture / Layered Design, RESTful APIs, JWT & Auth flows.
* **Frontend**: React 19, Next.js 15, TypeScript, Vite, Tailwind CSS, PrimeReact, Material UI, Zustand.
* **Mobile / PWA**: Flutter (Riverpod), Capacitor, offline-first Progressive Web Apps.
* **Tooling & AI**: AI Agent Orchestration (Claude Code, OpenCode, Codex, Gemini), test automation, token cost optimization, MCP servers.

### 🧪 How I work

* **Whole product, not a snippet**: every repo ships an API, a UI, tests and a usage + deploy guide.
* **Verifiable quality**: 15 repos with green CI and over 1,000 automated tests (xUnit, pytest, PHPUnit, Dart, Vitest, node --test).
* **Documented decisions**: the READMEs explain why it is built this way and where the limits are.

### 🛠️ Featured Projects

* 🧺 **[LavAR](https://github.com/lucabaello1998/LavAR)** · *new*  
  The neighborhood laundromat drops the paper notebook: a .NET 8 API + React panel where the counter logs the order, and the customer follows it with a **6-letter code** (`/p/K7M2QP`) — no app, no sign-up. Prices frozen at drop-off, state rules (you can't hand over what isn't ready), pre-written WhatsApp notices and a single Docker image with SQLite. 68 tests and rate-limited public lookups.
* 🕒 **[fichada](https://github.com/lucabaello1998/fichada)** *new*  
  Clock-in/clock-out demo for a small business: the employee punches in from the phone, the app checks the branch perimeter with haversine and the manager sees weekly hours with overtime past 8 h/day. React 19 + Vite + TypeScript, business rules in a pure tested module (18 tests), data in the browser. Not a real attendance system: browser GPS can be spoofed, and the README says so.
* 🧾 **[facturacion-ar](https://github.com/lucabaello1998/facturacion-ar)**  
  .NET 8 client for Argentine e-invoicing: builds and signs the WSAA TRA (PKCS#7), caches token + sign and requests the CAE through WSFEv1 without hand-writing SOAP. Ships an AFIP mock so it runs without a certificate: 29 tests. No credentials in the repo, and the README spells out what production still needs.
* 📝 **[engineering-notes](https://github.com/lucabaello1998/engineering-notes)**  
  Engineering notes with symptom, cause, fix and how to catch it next time. Every note cites the repo and commit where it was fixed: filter chips that needed two taps, MediaWiki truncating at 500 categories, an MCP server broken by one `console.log`.
* 🧱 **[FieldOps](https://github.com/lucabaello1998/fieldops-modernization)** • [Deck](https://github.com/lucabaello1998/fieldops-modernization/blob/main/docs/FieldOps.pptx)  
  Modernization of a production field-operations system (PHP 7.4 + jQuery, 76 tables without foreign keys, 11.3M rows) to Laravel 12 + PHP 8.3 + MySQL 8: the real schema migrated as-is, a server-validated drag & drop Kanban and 62 feature tests against real MySQL, with a reproducible Docker demo and CI running the suite plus 10 headless-Chrome e2e checks.
* 🔍 **[legacy-lens](https://github.com/lucabaello1998/legacy-lens)** • [Sample report](https://lucabaello1998.github.io/legacy-lens/)  
  Python CLI that X-rays a legacy PHP/MySQL system in one command: parses the dump, rebuilds the relationships nobody ever documented, flags concatenated SQL, dead functions and hardcoded secrets, and returns a **migration pain index** with an action plan. 24 rules, 70 tests, Docker, HTML/JSON/Markdown output. Snippets ship with literals masked, so the report can be shared without leaking a password.
* 💸 **[sueldos-ar](https://github.com/lucabaello1998/sueldos-ar)** • [Observatory](https://lucabaello1998.github.io/sueldos-ar/)  
  Argentine payroll engine in .NET 8 where the law is data: severance, vacations, contributions, income tax and SAC, with 77 xUnit + 101 Python tests and the legal basis for every line item. Ships a weekly observatory that scrapes tech job posts and publishes the uncomfortable finding: most postings do not state a salary, and the ones that do usually publish filler amounts.
* 🎛️ **[OpenCockpit](https://github.com/lucabaello1998/OpenCockpit)** • [Download](https://github.com/lucabaello1998/OpenCockpit/releases/latest)  
  Multi-tool desktop dashboard (Electron 44 + React 19 + Vite) for local AI engineering audits: tracks token usage, costs, sessions, and full conversation transcripts across Claude Code, OpenCode, Codex, Gemini/Antigravity, Copilot, Cursor, and Cline without backends or telemetry. 323 security and correctness checks in its suite.
* 📦 **[FletAR](https://github.com/lucabaello1998/FletAR)**  
  Freight and on-demand logistics marketplace for Argentina. Decoupled .NET 8 + PostGIS + SignalR backend paired with a cross-platform Flutter mobile client: blind bidding, per-offer chat and live GPS with explicit authorization.
* ⚡ **[ai-progress](https://github.com/lucabaello1998/ai-progress)**  
  Windows and Linux floating widget that shows AI agent task progress (`status.json`), Claude/Codex/OpenCode usage and limits, with no telemetry.
* 🗺️ **[direcciones_ar](https://github.com/lucabaello1998/direcciones_ar)**  
  Dart package for Argentine address autocomplete and reverse geocoding on Nominatim: LRU cache, rate limiting, and parsing into street, number, neighborhood and city.
* 🧪 **[liquid-glass-lab](https://github.com/lucabaello1998/liquid-glass-lab)**  
  Interactive UI lab showcasing real-time SVG refraction (`feDisplacementMap` + SDF), React 19, Tailwind v4, and dnd-kit.

### 📫 Connect with Me

* **Portfolio**: [lucabaello1998.github.io](https://lucabaello1998.github.io/)
* **LinkedIn**: [in/luca-baello](https://www.linkedin.com/in/luca-baello)
* **Email**: [luca.baello@gmail.com](mailto:luca.baello@gmail.com)
* **Location**: Buenos Aires, Argentina

---

## Capturas / Screenshots

Cada una es del producto corriendo, no una maqueta. El resto está en el README de cada repo.

| | |
|---|---|
| **LavAR** — panel del mostrador y seguimiento del cliente<br>![LavAR](https://raw.githubusercontent.com/lucabaello1998/LavAR/main/docs/panel.png) | **mlbb-draft** — tier list medida con winrate/banrate y drafter con bans<br>![mlbb-draft](https://raw.githubusercontent.com/lucabaello1998/mlbb-draft/main/docs/tierlist.png) |
| **job-radar** — ofertas rankeadas contra el perfil, con el motivo de cada punto<br>![job-radar](https://raw.githubusercontent.com/lucabaello1998/job-radar/main/docs/captura.png) | **FletAR** — publicar un flete y ver ofertas cerca<br>![FletAR](https://raw.githubusercontent.com/lucabaello1998/FletAR/master/docs/capturas/01-crear-publicacion.png) |
| **OpenCockpit** — uso, tokens y costo de siete herramientas de IA<br>![OpenCockpit](https://raw.githubusercontent.com/lucabaello1998/opencockpit/main/docs/capturas/resumen.png) | **sueldos-ar** — recibo de sueldo con la ley como dato<br>![sueldos-ar](https://raw.githubusercontent.com/lucabaello1998/sueldos-ar/main/docs/capturas/recibo.png) |
| **legacy-lens** — radiografía de un sistema legacy en un comando<br>![legacy-lens](https://raw.githubusercontent.com/lucabaello1998/legacy-lens/main/docs/capturas/reporte.png) | **cvfit** — encaje CV / aviso, gaps y CV adaptado<br>![cvfit](https://raw.githubusercontent.com/lucabaello1998/cvfit/main/docs/capturas/interfaz.png) |
| **FieldOps** — modernización PHP 7.4 → Laravel 12, tablero real<br>![FieldOps](https://raw.githubusercontent.com/lucabaello1998/fieldops-modernization/main/docs/capturas/deck/02-tablero.png) | **fichada** — fichaje con perímetro y horas de la semana<br>![fichada](https://raw.githubusercontent.com/lucabaello1998/fichada/master/docs/demo.png) |
