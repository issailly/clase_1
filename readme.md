# Resumen de Análisis y Diseño de Software

## 1. Introducción al Análisis y Diseño de Software
El desarrollo de software no se trata de sentarse a programar de inmediato. De hecho, el 66% de los proyectos fracasan debido a requerimientos mal definidos.

* **Análisis (El QUÉ):** Entender a fondo el problema antes de resolverlo (quién usará el sistema, qué necesita y qué restricciones hay).
* **Diseño (El CÓMO):** Planear la solución técnica (arquitectura, base de datos, interfaces y flujos).

> 💸 **Regla del 1-10-100:** Corregir un error en la fase de análisis cuesta $1, en diseño $10, en programación $100 y en producción más de $1000. ¡Planear ahorra dinero y evita catástrofes!

---

## 2. El Ciclo de Vida del Software (SDLC)
Es el conjunto de etapas por las que pasa un sistema desde que nace como una idea hasta que se vuelve obsoleto. Es un proceso cíclico que se divide en 6 fases:* **Análisis de Requerimientos:** Se definen las necesidades y se crea la Especificación de Requerimientos.
* **Diseño:** Se crean los planos, diagramas y maquetas del sistema.
* **Implementación:** Los programadores escriben el código real.
* **Pruebas (QA):** Se buscan y corrigen bugs antes del lanzamiento.
* **Despliegue:** El software se sube a producción y llega a los usuarios reales.
* **Mantenimiento:** Se corrigen fallas del día a día y se agregan nuevas funciones.

---

## 3. Metodologías Estructuradas vs. ⚡ 4. Metodologías Ágiles
Existen dos filosofías opuestas para gestionar proyectos de software:

### 📏 Metodologías Estructuradas (Tradicionales)
Se basan en planificar todo al inicio y seguir el plan de forma rígida. El cliente ve el producto solo al final.

* **Modelo Cascada (Waterfall):** Secuencial puro; cada fase debe terminar al 100% antes de iniciar la siguiente.
* **Modelo en V:** Enfocado en la calidad. Cada fase de desarrollo tiene una fase de pruebas gemela.
* **Modelo Espiral:** Trabaja por iteraciones enfocadas en el análisis y reducción de riesgos.
* **Ideales para:** Sistemas críticos (salud, aviación, banca) donde un error cuesta vidas o millones de dólares.

### ⚡ Metodologías Ágiles (Modernas)
Nacidas en 2001 con el Manifiesto Ágil. Valoran más la adaptación al cambio, las interacciones humanas y el software funcional que la burocracia y los planes fijos. El trabajo se divide en ciclos cortos (iteraciones) de 1 a 4 semanas.

* **Scrum:** Trabaja con Sprints (ciclos cortos), reuniones diarias de 15 minutos (Dailies) y roles claros (Product Owner, Scrum Master, Developers).
* **Kanban:** Usa un tablero visual con columnas para limitar el trabajo en curso (WIP) y evitar atascos.
* **XP (Programación Extrema):** Enfoque técnico de alta calidad (programación en parejas, desarrollo guiado por pruebas o TDD).
* **Ideales para:** Startups, aplicaciones móviles y productos interactivos que cambian constantemente.

---

## 5. Ingeniería de Requerimientos
Un requerimiento es la descripción exacta de lo que el sistema debe hacer o una restricción que debe cumplir. Se dividen en:

* **Funcionales (El QUÉ):** Las acciones concretas de la app (ej: *"El sistema debe permitir pagar con tarjeta"*).
* **No Funcionales (El CÓMO):** Atributos de calidad y restricciones (ej: *"La página debe cargar en menos de 3 segundos"*).

> 🎯 **Cualidad SMART:** Los requerimientos nunca deben ser ambiguos (como decir "la app debe ser rápida"). Tienen que ser específicos, medibles y verificables.

Se descubren mediante técnicas de elicitación (hablar con los usuarios a través de entrevistas, encuestas, observaciones o prototipos) y se debe aceptar que siempre pueden cambiar a lo largo del camino.