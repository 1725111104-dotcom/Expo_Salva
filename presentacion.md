# Las Herramientas Esenciales para un Ingeniero de Software
> **Aguirre Barragán Eduardo                
Espinosa García Yasmin
Montiel Ortiz Axel Josué
Peralta Martínez Estefany**

---

## 1. Control de Versiones y Colaboración

> *Garantiza el rastreo de cambios, la reversión segura y el trabajo en equipo sin conflictos.*

### 🔹 **Git** (Local)
- **¿Qué hace?**: Sistema de control de versiones distribuido.
- **Función principal**: Registra el historial de cambios del código, permite trabajar en ramas (*branches*) paralelas y fusionar trabajo de forma segura.

### 🔹 **GitHub / GitLab / Bitbucket** (Cloud)
- **¿Qué hacen?**: Plataformas en la nube para alojar repositorios Git.
- **Función principal**:
  - **GitHub**: Estándar global para código abierto y colaboración mediante *Pull Requests*.
  - **GitLab**: Enfoque *DevOps* integral con pipelines CI/CD nativos.
  - **Bitbucket**: Integración profunda con el ecosistema Atlassian (Jira).

---

## 2. Entornos de Desarrollo y Editores

> *La navaja suiza donde el ingeniero escribe, depura y empaqueta su código.*

| Herramienta | Tipo | Descripción y Uso Principal |
| :--- | :--- | :--- |
| **VS Code** | Editor Ligero | Extensible, veloz y el más popular del mercado. Soporta casi cualquier lenguaje mediante extensiones. |
| **JetBrains Suite**<br>*(IntelliJ, PyCharm, WebStorm)* | IDEs Especializados | Entornos de desarrollo integrados ultra potentes con refactorización avanzada y autocompletado inteligente por lenguaje. |
| **Docker** | Contenedorización | Empaqueta la aplicación y sus dependencias en contenedores aislados. Garantiza que el código funcione igual en cualquier máquina (*"en mi local sí funciona"* es historia). |

---

## 3. Integración y Despliegue Continuo (CI/CD)

> *Automatización del ciclo de vida del software: construcción, pruebas y entrega a producción.*
### ⚡ **GitHub Actions / GitLab CI**
- **Propósito**: Automatización de workflows directamente integrada en el repositorio de código.
- **Uso**: Se activa al hacer `git push` o abrir un PR; ejecuta pruebas y despliega automáticamente usando archivos de configuración YAML.

### ⚙️ **Jenkins**
- **Propósito**: Servidor de automatización *open-source* altamente personalizable.
- **Uso**: Ideal para arquitecturas empresariales complejas o infraestructura auto-hospedada (*on-premise*).

---

## 4. Computación en la Nube

> *Infraestructura escalable bajo demanda para ejecutar aplicaciones globales sin gestionar hardware físico.*

- **AWS (Amazon Web Services)**: 
  - *Líder del mercado.* Ofrece el catálogo más amplio de servicios (EC2, S3, Lambda, RDS).
- **Microsoft Azure**: 
  - *Sólida integración empresarial.* Preferida por corporativos que usan el stack de Microsoft (.NET, Active Directory).
- **Google Cloud Platform (GCP)**: 
  - *Potencia en datos e IA.* Destaca en analítica de datos, Kubernetes (*GKE*) y modelos de aprendizaje automático.

---

## 5. Gestión de Bases de Datos

> *Persistencia de datos estructurados y no estructurados con alto rendimiento.*

### 🏢 **Relacionales (SQL)** — *Estructura e Integridad ACID*
* **PostgreSQL**: Base de datos relacional avanzada de código abierto, conocida por su robustez y soporte para datos complejos.
* **MySQL**: Extremadamente popular, rápida y pilar de la web moderna.

### ⚡ **No Relacionales (NoSQL)** — *Escalabilidad y Flexibilidad*
* **MongoDB**: Base de datos orientada a documentos (JSON/BSON), ideal para esquemas dinámicos y desarrollo ágil.
* **Redis**: Almacenamiento clave-valor en memoria de velocidad ultra rápida; usada principalmente para *caching*, sesiones y colas de mensajes.

---

## 6. Pruebas y Depuración

> *Asegura la calidad, estabilidad y seguridad del software antes de llegar al usuario.*

### 🛠️ **Pruebas Unitarias e Integración**
- **Jest** *(JavaScript/TypeScript)* | **JUnit** *(Java)* | **PyTest** *(Python)*
- *Función*: Evalúan fragmentos individuales de código (funciones, clases) para confirmar que retornen el resultado esperado.

### 🌐 **Pruebas End-to-End (E2E)**
- **Cypress / Playwright**
- *Función*: Simulan la interacción real de un usuario en el navegador (clics, formularios, navegación) de principio a fin.

### 📡 **Pruebas de APIs**
- **Postman**
- *Función*: Diseñar, probar, documentar y simular peticiones HTTP (REST, GraphQL) a servicios backend.

---

## 7. Gestión de Proyectos y Metodologías Ágiles

> *Organización estratégica del equipo, planificación de sprints y documentación técnica.*

- **Jira / Linear**: Tableros Kanban y Scrum para asignación de tareas, seguimiento de *bugs* y métricas de velocidad de desarrollo.
- **Notion / Confluence**: Centralización de la documentación técnica, guías de arquitectura, decisiones de diseño (*ADRs*) y onboarding del equipo.

---

## Conclusión

Un **Ingeniero de Software integral** no necesita dominar cada herramienta al 100%, sino comprender **cómo interactúan entre sí**:

1. Escribe código en **VS Code / JetBrains** dentro de un contenedor **Docker**.
2. Controla los cambios con **Git** y los sube a **GitHub**.
3. Un pipeline de **GitHub Actions** ejecuta pruebas en **Jest/PyTest** y verifica la API con **Postman**.
4. Si todo pasa, la app se despliega en la nube (**AWS/Azure**) conectada a **PostgreSQL** y **Redis**.
5. Todo el avance se rastrea en **Jira** y se documenta en **Notion**.

---

*¡Gracias por su atención!*

# Referencias Bibliográficas


## Control de Versiones y Colaboración
* **Git Documentation**. (s. f.). *About Version Control and Git*. Recuperado de https://git-scm.com/doc
* **GitHub Docs**. (s. f.). *GitHub flow and collaboration tools*. Recuperado de https://docs.github.com
* **GitLab Documentation**. (s. f.). *GitLab CI/CD and Version Control*. Recuperado de https://docs.gitlab.com

## Entornos de Desarrollo y Contenedores
* **Docker Documentation**. (s. f.). *Docker Overview and Containerization*. Recuperado de https://docs.docker.com/get-started/overview/
* **JetBrains**. (s. f.). *Developer Tools and IDEs Documentation*. Recuperado de https://www.jetbrains.com/documentation/
* **Visual Studio Code Documentation**. (s. f.). *Getting Started with VS Code*. Recuperado de https://code.visualstudio.com/docs

## Integración y Despliegue Continuo (CI/CD)
* **GitHub Actions**. (s. f.). *Understanding GitHub Actions*. Recuperado de https://docs.github.com/en/actions
* **Jenkins User Documentation**. (s. f.). *Jenkins User Handbook*. Recuperado de https://www.jenkins.io/doc/

## Computación en la Nube
* **Amazon Web Services (AWS)**. (s. f.). *AWS Cloud Products and Solutions Documentation*. Recuperado de https://aws.amazon.com/documentation/
* **Google Cloud Platform**. (s. f.). *GCP Documentation*. Recuperado de https://cloud.google.com/docs
* **Microsoft Azure**. (s. f.). *Azure Documentation and Architecture Center*. Recuperado de https://learn.microsoft.com/azure/

## Gestión de Bases de Datos
* **MongoDB Documentation**. (s. f.). *The MongoDB Manual*. Recuperado de https://www.mongodb.com/docs/manual/
* **PostgreSQL Global Development Group**. (s. f.). *PostgreSQL Official Documentation*. Recuperado de https://www.postgresql.org/docs/
* **Redis Documentation**. (s. f.). *Redis In-Memory Data Store Guide*. Recuperado de https://redis.io/docs/

## Pruebas y Depuración
* **Cypress Documentation**. (s. f.). *End-to-End Testing Framework*. Recuperado de https://docs.cypress.io
* **Jest Documentation**. (s. f.). *Delightful JavaScript Testing*. Recuperado de https://jestjs.io/docs/getting-started
* **Playwright Docs**. (s. f.). *Fast and reliable end-to-end testing*. Recuperado de https://playwright.dev/docs/intro
* **Postman Learning Center**. (s. f.). *Postman API Platform Docs*. Recuperado de https://learning.postman.com/docs/

## Gestión de Proyectos y Metodologías Ágiles
* **Atlassian**. (s. f.). *Jira Software and Confluence User Guides*. Recuperado de https://www.atlassian.com/software/jira/guides
* **Linear Docs**. (s. f.). *Linear Method for Software Development*. Recuperado de https://linear.app/docs
* **Notion Help Center**. (s. f.). *Notion for Engineering Teams*. Recuperado de https://www.notion.so/help