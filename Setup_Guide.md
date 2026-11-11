<img src="images/neteclogo.png" alt="logo" width="300"/>

# Setup Guide General

## Fundamentos de Ciberseguridad

| Control documental | Información |
|---|---|
| Clave del curso | TPRACT_CIB_ESS_LD MSV (Priv) |
| Versión del documento | 1.0 |
| Estado | BORRADOR: revisión documental completa; pendiente de validación con cuentas de participante |
| Instructor responsable | Por asignar por Netec |
| Fecha de elaboración | 2026-11-10 |
| Fecha de última validación | 2026-11-10 (revisión de herramientas y enlaces) |
| Repositorio de laboratorios | Repositorio de GitHub de Netec del curso (rama `main`) |
| Rama y revisión analizada | `main`, versión 1.0 |
| Alcance revisado | 1 capítulo del temario, 5 prácticas, 10 archivos de recursos, README principal y Setup Guide |
| Modalidad del entorno | Web (servicios gratuitos) con aplicaciones de ofimática locales o en la web |

[Inicio](README.md)

# Objetivo

Preparar, para cada participante, un equipo con navegador actualizado, una aplicación para editar documentos de Word y Excel, y una cuenta de Google con acceso a Google AI Studio. También se deben tener accesibles los sitios de Cisco Duo, VirusTotal, la National Vulnerability Database, CISA y FIRST. El entorno se considera listo cuando se aprueban las validaciones de la sección [Validación del Entorno](#validacion-entorno). No se instala software de seguridad ni se usa la línea de comandos.

# Requisitos de Hardware

| Recurso | Mínimo requerido | Recomendado | Observaciones |
|---|---|---|---|
| Equipo | Laptop o PC de 64 bits, 2 núcleos | 4 núcleos | Todas las herramientas son web |
| Memoria RAM | 4 GB | 8 GB | Varias pestañas del navegador abiertas |
| Espacio libre | 1 GB | 2 GB | Los archivos de las prácticas ocupan menos de 1 MB |
| Pantalla | 1366 × 768 | 1920 × 1080 | Facilita trabajar con el navegador y la plantilla a la vez |
| Conectividad | 5 Mbps | 10 Mbps | Acceso HTTPS sin bloqueo a los sitios de la sección [Servicios Externos Requeridos](#servicios-externos) |

# Sistemas Operativos Compatibles

| Sistema operativo | Edición y versión | Arquitectura | Condición de soporte o validación |
|---|---|---|---|
| Windows | 10 u 11 | x64 | Plataforma base; compatible según fabricante; pendiente de validar con cuenta de participante |
| macOS | 13 o posterior | Apple silicon o Intel | Compatible según fabricante; no validado |
| Linux | Distribución con navegador actualizado | x64 | Compatible según fabricante; no validado |

Las instrucciones usan Windows y nombres de menú en español.

# Software Requerido

| Componente | Edición y versión requerida | Arquitectura | Obligatorio u opcional | Fuente oficial |
|---|---|---|---|---|
| Navegador Google Chrome o Microsoft Edge | Versión estable vigente | x64 | Obligatorio | [google.com/chrome](https://www.google.com/chrome/) |
| Editor de documentos y hojas de cálculo | Microsoft 365 (escritorio o web), Google Docs y Sheets, o LibreOffice | x64 | Obligatorio | [microsoft365.com](https://www.microsoft365.com/) o [libreoffice.org](https://www.libreoffice.org/download/download-libreoffice/) |
| Google AI Studio | Servicio administrado, nivel gratuito | N/A | Obligatorio (Práctica 1) | [aistudio.google.com](https://aistudio.google.com/) |
| Demostraciones de Cisco Duo | Servicio administrado, sin cuenta | N/A | Obligatorio (Práctica 2) | [duo.com/demos](https://duo.com/demos) |
| VirusTotal | Servicio administrado, uso público gratuito | N/A | Obligatorio (Práctica 3) | [virustotal.com](https://www.virustotal.com/) |
| National Vulnerability Database | Servicio público del NIST | N/A | Obligatorio (prácticas 4 y 5) | [nvd.nist.gov](https://nvd.nist.gov/) |
| Calculadora CVSS 3.1 de FIRST | Servicio público | N/A | Obligatorio (Práctica 5) | [first.org/cvss/calculator/3.1](https://www.first.org/cvss/calculator/3.1) |

Los servicios web cambian su interfaz sin previo aviso. Registrar la fecha de prueba y cualquier diferencia observada en el [Registro de validación](#registro-validacion).

# Herramientas y Dependencias

## Paquetes, frameworks y componentes adicionales

| Dependencia | Versión o restricción | Componente que la necesita | Método de instalación o habilitación |
|---|---|---|---|
| Simulador SecuLab | Instrucciones de sistema del repositorio o app compartida por el instructor | Práctica 1 | Pegar `Capitulo01/recursos/SecuLab_Instrucciones_Sistema.txt` en **System instructions** de Google AI Studio |
| Plantillas de entregables | Versión 1.0 del repositorio | Prácticas 1 a 5 | Carpetas `CapituloNN/recursos/` |
| Archivo de prueba EICAR (solo su hash) | Hash SHA-256 público | Práctica 3 | No se descarga; se consulta por hash |

## Licencias, cuentas y permisos

| Recurso o servicio | Licencia o suscripción | Cuenta o rol requerido | Permiso mínimo | Responsable de habilitación |
|---|---|---|---|---|
| Google AI Studio | Gratuita | Cuenta de Google (mayor de edad, región con servicio disponible) | Usuario | Cada participante |
| VirusTotal | Uso público gratuito | Sin cuenta (opcional: cuenta gratuita de la comunidad) | Búsqueda y carga pública | Cada participante |
| Cisco Duo, NVD, CISA y FIRST | Acceso público | Sin cuenta | Lectura | No aplica |
| Repositorio de laboratorios | Repositorio de GitHub de Netec | Cuenta de GitHub con acceso de lectura, o paquete ZIP del instructor | Lectura | Netec |

No registrar contraseñas ni códigos de verificación en el repositorio ni en los entregables. En el simulador SecuLab nunca se escriben datos reales.

# Instalación y Configuración

## 1. Obtener los materiales

- Repositorio autorizado: repositorio de GitHub del curso (botón **Code > Download ZIP**) o paquete ZIP entregado por el instructor.
- Revisión: rama `main`.
- Directorio de trabajo: `Documentos\Taller_Ciberseguridad\` con las subcarpetas `Practica01` a `Practica05`.
- Archivos de entrada: carpetas `recursos` de cada capítulo. Los entregables se generan durante el taller.

## 2. Instalar o habilitar los componentes

### Navegador y editor de documentos

1. Verificar que el navegador esté actualizado (**Configuración > Acerca de**).
2. Abrir un documento `.docx` y una hoja `.xlsx` de prueba en el editor elegido.

**Resultado esperado:** ambos archivos se abren y se pueden guardar.

### Cuenta de Google y Google AI Studio

1. Iniciar sesión en [aistudio.google.com](https://aistudio.google.com/) con la cuenta de Google.
2. Aceptar los términos de uso si aparecen.
3. Abrir un chat nuevo y enviar *"Responde solo OK"*.

**Resultado esperado:** el modelo responde OK.

### Carpetas de trabajo

1. Crear `Documentos\Taller_Ciberseguridad\` y, dentro, las carpetas `Practica01` a `Practica05`.
2. Copiar a cada carpeta el contenido de `CapituloNN\recursos` correspondiente.

**Resultado esperado:** 10 archivos de recursos distribuidos en las 5 carpetas.

## 3. Preparar archivos de configuración

No se requieren archivos de configuración.

# Variables de Entorno

No se requieren variables de entorno.

# Configuración Base para los Laboratorios

## Parámetros comunes

| Parámetro | Valor o convención | Observaciones |
|---|---|---|
| Raíz de trabajo | `Documentos\Taller_Ciberseguridad\` | Una carpeta por práctica |
| Nombre de entregables | `Nombre_[INICIALES].ext` o `Nombre_[EQUIPO].ext` | Práctica 4 por equipo |
| Datos | Casos públicos y datos ficticios | Nunca datos reales de la organización |
| Equipos | 2 o 3 participantes | Prácticas 4 y 5 |

## Estructura de carpetas

```text
Documentos\Taller_Ciberseguridad\
├── Practica01\ ... Practica05\   Recursos y entregables de cada práctica
```

## Recursos compartidos

No hay recursos compartidos entre participantes. En la Práctica 4 cada equipo trabaja con el CVE asignado en `CVE_Asignados.xlsx`.

## Preparación antes de cada práctica

| Práctica | Preparación |
|---|---|
| 1 | Sesión iniciada en Google AI Studio; el instructor comparte el enlace de la app SecuLab si la tiene publicada |
| 2 | Abrir [duo.com/demos](https://duo.com/demos) y aceptar solo las cookies necesarias |
| 3 | Comprobar que la red permite subir archivos a VirusTotal; si no, el instructor proyecta esa parte |
| 4 | Formar equipos y asignar los CVE de `CVE_Asignados.xlsx` |
| 5 | Tener a la mano la ficha de la Práctica 4 |

## Correcciones de coherencia

| Inconsistencia o dependencia omitida | Configuración unificada | Ajuste necesario en las copias de trabajo |
|---|---|---|
| El temario indica la app "SecuLab" en Google AI Studio, pero no proporciona su enlace | Instrucciones de sistema de SecuLab en `Capitulo01/recursos`, para recrearla en Google AI Studio; el instructor puede usar la app oficial si la tiene | Ninguno |
| El temario agrupa las 5 prácticas en el Capítulo 1 | Una carpeta `CapituloNN` por práctica, según la estructura de laboratorios de Netec | Ninguno |
| La Práctica 3 requiere ejemplos maliciosos sin riesgo | Se usa el archivo de prueba estándar EICAR (solo su hash y su URL pública en VirusTotal) y un PDF inofensivo | Ninguno |

# Servicios Externos Requeridos <a id="servicios-externos"></a>

| Servicio | URL, endpoint o región | Uso | Acceso requerido |
|---|---|---|---|
| Google AI Studio | [aistudio.google.com](https://aistudio.google.com/) | Práctica 1 | Cuenta de Google |
| Cisco Duo | [duo.com/demos](https://duo.com/demos) | Práctica 2 | Público |
| VirusTotal | [virustotal.com](https://www.virustotal.com/) | Práctica 3 | Público |
| NVD | [nvd.nist.gov](https://nvd.nist.gov/) | Prácticas 4 y 5 | Público |
| CISA KEV | [cisa.gov/known-exploited-vulnerabilities-catalog](https://www.cisa.gov/known-exploited-vulnerabilities-catalog) | Práctica 4 | Público |
| FIRST | [first.org/cvss](https://www.first.org/cvss/calculator/3.1) | Práctica 5 | Público |
| GitHub | [github.com](https://github.com/) | Descarga de materiales | Lectura del repositorio |

## Configuración de red

| Origen | Destino | Protocolo y puerto | Sentido | Condición |
|---|---|---|---|---|
| Equipo del participante | aistudio.google.com, duo.com, virustotal.com, nvd.nist.gov, cisa.gov, first.org, github.com | HTTPS 443 | Saliente | Dominios permitidos en el proxy o firewall; la subida de archivos a virustotal.com debe estar permitida para la Práctica 3 |

# Creación de Entornos / Máquinas Virtuales / Emuladores

No aplica. El taller no requiere máquinas virtuales ni contenedores.

<a id="validacion-entorno"></a>

# Validación del Entorno

| ID | Componente o capacidad | Procedimiento | Resultado esperado | Evidencia mínima |
|---|---|---|---|---|
| V-01 | Materiales | Descargar el ZIP del repositorio y abrir `Capitulo01/recursos/Plantilla_Analisis_Ingenieria_Social.docx` | El documento se abre y se puede editar | Captura |
| V-02 | Google AI Studio | Pegar `SecuLab_Instrucciones_Sistema.txt` en **System instructions** y enviar `INICIAR` | Aparece el ESCENARIO 1 | Captura |
| V-03 | Cisco Duo | Abrir [la demostración de Duo Push](https://duo.com/demos/multi-factor-authentication-mfa-with-duo-push) | La demostración avanza con clics | Captura |
| V-04 | VirusTotal | Buscar el hash `275a021bbfb6489e54d471899f7db9d1663fc695ec2fe2a2c4538aabf651fd0f` | Informe con detecciones de EICAR | Captura |
| V-05 | VirusTotal (carga) | Subir `Capitulo03/recursos/Factura_Pendiente_Demo.pdf` | Informe del archivo | Captura |
| V-06 | NVD | Abrir [CVE-2021-44228](https://nvd.nist.gov/vuln/detail/CVE-2021-44228) | Puntaje 10.0 CRITICAL | Captura |
| V-07 | FIRST | Abrir la [calculadora CVSS 3.1](https://www.first.org/cvss/calculator/3.1) y cargar el vector de Heartbleed | Puntaje 7.5 | Captura |

**Criterio de entorno listo:** V-01 a V-07 aprobadas. Si falla V-05 por políticas de red, la Tarea 4 de la Práctica 3 se realiza con la búsqueda por hash que proyecte el instructor.

# Comandos de Verificación

No aplica. El taller se valida en interfaces web con los procedimientos V-01 a V-07.

# Troubleshooting

| Síntoma | Causa probable | Comprobación | Corrección | Validación posterior |
|---|---|---|---|---|
| Google AI Studio no está disponible | Restricción de edad, región o cuenta administrada | Mensaje al iniciar sesión | Usar una cuenta de Google personal que cumpla los requisitos o trabajar en pareja | V-02 |
| VirusTotal pide CAPTCHA o limita búsquedas | Muchas consultas desde la misma red | Mensaje en pantalla | Resolver el CAPTCHA manualmente y espaciar las búsquedas | V-04 |
| La NVD responde lento | Alta demanda del servicio | Tiempo de carga | Recargar en un minuto o consultar [cve.org](https://www.cve.org/) | V-06 |
| Un sitio no carga | Bloqueo de red | Abrir el sitio desde otra red | Solicitar a TI la autorización del dominio | V-02 a V-07 |

# Checklist Final

- [ ] Navegador actualizado y editor de documentos funcional.
- [ ] Cuenta de Google con acceso a Google AI Studio.
- [ ] Sitios de Duo, VirusTotal, NVD, CISA y FIRST accesibles.
- [ ] Recursos descargados en `Documentos\Taller_Ciberseguridad\`.
- [ ] Validaciones V-01 a V-07 aprobadas.

# Resumen

Para iniciar el taller, cada participante necesita un navegador actualizado, un editor de documentos y hojas de cálculo, una cuenta de Google con acceso a Google AI Studio y acceso a los sitios públicos de Cisco Duo, VirusTotal, NVD, CISA y FIRST. No se instala software ni se usa la línea de comandos.

<a id="registro-validacion"></a>

## Registro de validación

| Fecha | Responsable | Plataforma o entorno probado | Resultado | Limitaciones o acciones pendientes |
|---|---|---|---|---|
| 2026-11-10 | Desarrollo de contenido Netec | Revisión de enlaces y herramientas: demostraciones de Duo, informe de EICAR en VirusTotal (archivo y URL), CVE en NVD, calculadora de FIRST | APTO para publicación del repositorio | No se ejecutó el taller completo con cuentas de participante. Pendiente: V-01 a V-07 |

## Referencias oficiales

| Documento o recurso | URL | Fecha de consulta |
|---|---|---|
| Google AI Studio | https://aistudio.google.com/ | 2026-11-10 |
| Cisco Duo: demostraciones | https://duo.com/demos | 2026-11-10 |
| VirusTotal: cómo funciona | https://docs.virustotal.com/docs/how-it-works | 2026-11-10 |
| EICAR: archivo de prueba | https://www.eicar.org/download-anti-malware-testfile/ | 2026-11-10 |
| National Vulnerability Database | https://nvd.nist.gov/ | 2026-11-10 |
| CISA KEV | https://www.cisa.gov/known-exploited-vulnerabilities-catalog | 2026-11-10 |
| FIRST: especificación de CVSS 3.1 | https://www.first.org/cvss/v3.1/specification-document | 2026-11-10 |

[Inicio](README.md)
