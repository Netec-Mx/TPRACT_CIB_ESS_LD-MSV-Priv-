<img src="images/neteclogo.png" alt="logo" width="300"/>

# Fundamentos de Ciberseguridad

## Plataforma de laboratorios

Te damos la bienvenida a la **plataforma de laboratorios** del curso **Fundamentos de Ciberseguridad**. Aquí podrás explorar diferentes tecnologías a través de prácticas guiadas. ¡Desarrolla tus habilidades y lleva tus conocimientos al siguiente nivel!

## Descripción del curso

Taller práctico introductorio orientado a comprender los principales riesgos de ciberseguridad y las medidas básicas de protección. A través de actividades de ingeniería social, autenticación multifactor, análisis de archivos sospechosos y consulta de vulnerabilidades CVE, los participantes conocerán herramientas y técnicas para identificar amenazas y fortalecer la seguridad de la información.

**Duración:** 2 horas (120 minutos), 100% práctica.

## Objetivos del curso

Identificar los principales riesgos asociados con la ingeniería social, comprender el funcionamiento de la autenticación multifactor, utilizar herramientas para analizar archivos y enlaces sospechosos e interpretar información pública sobre vulnerabilidades de seguridad, reconociendo su impacto y posibles medidas de mitigación.

## Perfil de audiencia

Usuarios finales, estudiantes y profesionales interesados en adquirir conocimientos fundamentales de ciberseguridad, especialmente quienes desean reconocer amenazas comunes y familiarizarse con herramientas básicas de protección y análisis de seguridad.

## Prerrequisitos

- Conocimientos básicos de informática, navegación web y uso de aplicaciones digitales.
- Haber culminado el curso Fundamentos de Ciberseguridad disponible en Cisco NetAcad.

## Lista de laboratorios

Cada uno de estos laboratorios está diseñado para ofrecerte una experiencia práctica. Haz clic en los enlaces para comenzar.

### [Práctica 1. Introducción a la Ingeniería Social](Capitulo01/README.md)

  - **Descripción**: análisis del caso real del ataque a Twitter (2020), simulación de correo, SMS y llamada fraudulentos en SecuLab, y discusión grupal sobre el factor humano.
  - ⏱️ **Duración estimada**: 30 min.

### [Práctica 2. Introducción a la Autenticación de Dos Factores | Cisco Duo](Capitulo02/README.md)

  - **Descripción**: clasificación de factores de autenticación y recorrido de las demostraciones de Cisco Duo para comparar la autenticación tradicional con la multifactor.
  - ⏱️ **Duración estimada**: 10 min.

### [Práctica 3. Aplicación de uso de inteligencia (sandbox)](Capitulo03/README.md)

  - **Descripción**: análisis en VirusTotal del hash, la URL y el adjunto de un correo sospechoso, e interpretación de detecciones y resultados de sandbox.
  - ⏱️ **Duración estimada**: 25 min.

### [Práctica 4. Introducción al análisis de vulnerabilidades CVE](Capitulo04/README.md)

  - **Descripción**: búsqueda de vulnerabilidades reales en la National Vulnerability Database y elaboración de una ficha con severidad, productos afectados, explotación conocida y mitigación.
  - ⏱️ **Duración estimada**: 40 min.

### [Práctica 5. Introducción al análisis de severidad de vulnerabilidades con CVSS](Capitulo05/README.md)

  - **Descripción**: interpretación del vector CVSS de Heartbleed, cálculo en la calculadora oficial de FIRST y priorización de vulnerabilidades.
  - ⏱️ **Duración estimada**: 15 min.

### Distribución del tiempo

| Práctica | Herramienta | Duración |
|---|---|---|
| 1. Introducción a la Ingeniería Social | SecuLab (Google AI Studio) | 30 min |
| 2. Introducción a la Autenticación de Dos Factores | Cisco Duo (demostraciones) | 10 min |
| 3. Aplicación de uso de inteligencia (sandbox) | VirusTotal | 25 min |
| 4. Introducción al análisis de vulnerabilidades CVE | National Vulnerability Database | 40 min |
| 5. Introducción al análisis de severidad con CVSS | NVD y calculadora CVSS de FIRST | 15 min |
| **Total** | | **120 min** |

## Instrucciones generales del laboratorio

1. Antes del taller, preparar el equipo y las cuentas con la [Guía de configuración](Setup_Guide.md).
2. Cada práctica está en su carpeta `CapituloNN` con su `README.md` y, cuando aplica, una carpeta `recursos` con las plantillas y archivos de trabajo. Para descargar un archivo, abrirlo y seleccionar **Download raw file**.
3. Guardar los entregables en `Documentos\Taller_Ciberseguridad\PracticaNN\` con las iniciales del participante en el nombre.
4. Todas las actividades son defensivas y usan casos públicos o datos ficticios. No escribir contraseñas reales en ninguna herramienta, no subir archivos confidenciales a VirusTotal y no abrir enlaces sospechosos.
5. Las prácticas 4 y 5 se realizan en equipos de 2 o 3 participantes; las demás son individuales con discusión grupal.

## Estructura del repositorio

```text
.
├── README.md            Página principal (este archivo)
├── Setup_Guide.md       Guía de configuración del entorno
├── images/              Logotipo y diagramas de las prácticas
├── Capitulo01/          Práctica 1: README.md y recursos/
├── Capitulo02/          Práctica 2
├── Capitulo03/          Práctica 3
├── Capitulo04/          Práctica 4
└── Capitulo05/          Práctica 5
```

## Recursos adicionales

- [CISA: Avoiding Social Engineering and Phishing Attacks](https://www.cisa.gov/news-events/news/avoiding-social-engineering-and-phishing-attacks)
- [CISA: autenticación multifactor](https://www.cisa.gov/topics/cybersecurity-best-practices/multifactor-authentication)
- [VirusTotal: cómo funciona](https://docs.virustotal.com/docs/how-it-works)

## Enlaces de referencia

- [National Vulnerability Database](https://nvd.nist.gov/)
- [CVE Program](https://www.cve.org/)
- [FIRST: especificación de CVSS 3.1](https://www.first.org/cvss/v3.1/specification-document)
- [CISA Known Exploited Vulnerabilities Catalog](https://www.cisa.gov/known-exploited-vulnerabilities-catalog)

---

## 📬 **Contacto y más información**

Si tienes alguna pregunta o necesitas más detalles, no dudes en [contactarnos](mailto:soporte@netec.com). También puedes encontrar más recursos en nuestra [página](https://netec.com).

---

¡Gracias por visitar nuestra plataforma! No olvides revisar todos los laboratorios y comenzar tu viaje de aprendizaje hoy mismo.
