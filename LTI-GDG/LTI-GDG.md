# LTI – Visión de Producto y Arquitectura

## 1. Descripción breve del software LTI

LTI es un sistema de seguimiento de candidatos (ATS) innovador y eficiente, diseñado para optimizar y agilizar los procesos de selección de talento en empresas modernas. LTI centraliza la gestión de vacantes, la recepción, el filtrado y la evaluación de candidatos, facilitando la comunicación y el control total del proceso desde una sola plataforma.

Una de las ventajas competitivas clave de LTI es que las funcionalidades de revisión y filtrado de candidatos, programación de entrevistas y gestión visual del pipeline de selección pueden ser gestionadas directamente a través de aplicaciones móviles para Android y iOS. Esto permite a los reclutadores acceder y administrar información crítica, agendar entrevistas y monitorizar el estado de los candidatos en tiempo real, desde cualquier lugar y en cualquier momento, usando su dispositivo móvil.

Gracias a estas capacidades móviles, LTI ofrece máxima flexibilidad y productividad, permitiendo una gestión ágil del proceso de selección y empoderando a los equipos de reclutamiento para tomar decisiones rápidas y basadas en datos, sin depender de estar en la oficina frente a una computadora

### Lean Canvas LTI – Applicant Tracking System

| Sección               | Detalle                                                                                     |
|-----------------------|--------------------------------------------------------------------------------------------|
| **Problema**          | - Procesos de selección manuales y dispersos<br>- Dificultad para filtrar y contactar candidatos rápidamente<br>- Falta de movilidad y acceso ágil desde el móvil<br>- Baja trazabilidad y poca visibilidad del pipeline de selección |
| **Segmentos clientes**| - Empresas medianas y grandes<br>- Reclutadores internos<br>- Consultoras de selección<br>- Equipos móviles de reclutamiento        |
| **Propuesta de valor única** | - Centralización total del proceso de selección<br>- Gestión de candidatos, entrevistas y pipeline 100% móvil y multiplataforma<br>- Ahorro de tiempo y decisiones ágiles desde cualquier lugar         |
| **Solución**          | - Creación de vacantes y publicación multicanal<br>- Filtros automáticos, ranking y gestión de candidatos en web y móvil<br>- Agendamiento de entrevistas y gestión visual del pipeline desde app móvil y escritorio    |
| **Canales**           | - Web propia (SaaS)<br>- Aplicaciones móviles Android/iOS<br>- Email marketing<br>- LinkedIn, redes sociales<br>- Marketplace de soluciones HR Tech                                              |
| **Fuentes de ingresos**| - Suscripción mensual/usuario (modelo SaaS)<br>- Paquetes premium por funcionalidades avanzadas<br>- Implementación y soporte empresarial                                    |
| **Estructura de costes** | - Desarrollo y mantenimiento software<br>- Infraestructura en la nube<br>- Soporte y onboarding<br>- Marketing y ventas<br>- Actualizaciones y seguridad de datos                            |
| **Métricas clave**    | - Cantidad de procesos gestionados<br>- Tiempo promedio de contratación<br>- % de uso móvil vs web<br>- Tasa de éxito de cierres<br>- Satisfacción del usuario<br>- Retención y churn           |
| **Ventaja competitiva** | - Gestión auténticamente móvil de funcionalidades críticas<br>- Experiencia simplificada y centrada en el usuario reclutador<br>- Escalabilidad y flexibilidad avanzada para equipos modernos  |


## 2. Casos de Uso Principales

A continuación una tabla con todos los casos de uso propuestos

| Funcionalidad                               | Nombre de caso de uso               | Descripción de caso de uso                                          | Roles de usuario              |
|---------------------------------------------|-------------------------------------|----------------------------------------------------------------------|-------------------------------|
| Gestión de vacantes                        | Crear puesto de trabajo (MVP)       | Crear una nueva vacante y publicarla en diferentes canales.           | Reclutador, Administrador     |
|                                             | Editar vacante                      | Modificar la información de una vacante previamente creada.           | Reclutador                    |
| Recepción y organización de aplicaciones    | Centralizar aplicaciones            | Recibir y almacenar todas las postulaciones en la plataforma.         | Reclutador, Administrador     |
|                                             | Exportar aplicaciones               | Descargar información de aplicaciones recibidas en diferentes formatos.| Reclutador, Administrador     |
| Revisión y filtrado de candidatos           | Filtrar y rankear candidatos (MVP)  | Visualizar/aplicar filtros y ranking a candidatos; disponible en móvil.| Reclutador                    |
|                                             | Buscar candidato por criterios       | Buscar candidatos por palabras clave, experiencia o competencias.      | Reclutador                    |
| Comunicación automatizada                  | Enviar notificaciones automáticas   | Enviar mensajes automáticos a candidatos mientras avanza el proceso.   | Reclutador, Sistema           |
|                                             | Personalizar mensajes               | Modificar el contenido de los mensajes enviados.                       | Reclutador                    |
| Programación de entrevistas                 | Agendar entrevistas (MVP)           | Asignar entrevistas de manera centralizada, desde web o app móvil.     | Reclutador, Candidato         |
|                                             | Confirmar/cancelar entrevista       | Aceptar o cancelar entrevistas agendadas.                              | Reclutador, Candidato         |
| Pruebas y evaluaciones online               | Enviar pruebas                      | Mandar pruebas a candidatos seleccionados.                             | Reclutador                    |
|                                             | Revisar resultados                  | Analizar resultados de pruebas directamente en la plataforma.          | Reclutador                    |
| Gestión del pipeline de selección           | Visualizar pipeline y estado        | Ver el avance de cada candidato en el proceso, desde cualquier dispositivo.| Reclutador                    |
|                                             | Modificar estado de candidato       | Cambiar la etapa de cada candidato desde web o móvil                   | Reclutador                    |
| Reporting y analítica básica                | Acceder a métricas y reportes       | Consultar estadísticas: tiempos, fuentes y ratios del proceso.         | Reclutador, Administrador     |
|                                             | Descargar reportes                  | Descargar reportes y gráficas para presentaciones.                     | Reclutador, Administrador     |
| Gestión documental                         | Adjuntar y consultar documentos     | Guardar CVs, cartas y archivos relevantes de candidatos.               | Reclutador, Administrador     |
| Cumplimiento de normativas                  | Solicitar consentimiento            | Registrar aceptación de protección de datos personales.                | Candidato, Sistema            |
|                                             | Generar auditorías                  | Consultar/regenerar registros para auditorías.                         | Administrador, Auditoría      |


Los casos de uso principales seleccionados son:

* Crear puesto de trabajo (MVP)

Descripción detallada: Permite al reclutador o administrador crear una nueva vacante ingresando toda la información relevante (nombre de puesto, requisitos, salario, canal de publicación, etc.) y publicar la oferta en portales, web corporativa y redes sociales desde la plataforma.

Roles de usuario asociados: Reclutador, Administrador

```mermaid
%% Caso: Crear puesto de trabajo (MVP)
sequenceDiagram
    participant Reclutador
    participant Administrador
    participant Sistema

    Reclutador->>Sistema: Solicita crear nueva vacante
    Sistema-->>Reclutador: Solicita datos (título, descripción, requisitos, canales)
    Reclutador->>Sistema: Ingresa datos y confirma creación
    Sistema-->>Administrador: Notifica nueva vacante creada (opcional)
    Sistema-->>Reclutador: Confirma publicación exitosa

```

* Filtrar y rankear candidatos (MVP)

Descripción detallada: El reclutador puede visualizar y filtrar los candidatos que han aplicado a una vacante según criterios definidos (palabras clave, nivel de experiencia, formación, etc.). Además, la interfaz está disponible en la aplicación móvil, lo que permite gestionar esta tarea completamente desde dispositivos Android e iOS.

Roles de usuario asociados: Reclutador

```mermaid
%% Caso: Agendar entrevistas (MVP)
sequenceDiagram
    participant Reclutador
    participant Candidato
    participant Sistema

    Reclutador->>Sistema: Solicita agendar entrevista con candidato
    Sistema-->>Reclutador: Solicita fecha, hora y tipo de entrevista
    Reclutador->>Sistema: Ingresa detalles y confirma cita
    Sistema-->>Candidato: Envía invitación y solicitud de confirmación
    Candidato->>Sistema: Confirma o rechaza entrevista
    Sistema-->>Reclutador: Notifica confirmación o rechazo
```

* Agendar entrevistas (MVP)

Descripción detallada: Facilita la asignación de entrevistas entre reclutadores y candidatos, permitiendo elegir fecha, hora, tipo de entrevista (virtual/presencial) y enviar confirmación tanto desde la web como desde la app móvil. Los candidatos pueden recibir notificaciones y confirmar o rechazar fechas propuestas.

Roles de usuario asociados: Reclutador, Candidato


```mermaid
%% Caso: Agendar entrevistas (MVP)
sequenceDiagram
    participant Reclutador
    participant Candidato
    participant Sistema

    Reclutador->>Sistema: Solicita agendar entrevista con candidato
    Sistema-->>Reclutador: Solicita fecha, hora y tipo de entrevista
    Reclutador->>Sistema: Ingresa detalles y confirma cita
    Sistema-->>Candidato: Envía invitación y solicitud de confirmación
    Candidato->>Sistema: Confirma o rechaza entrevista
    Sistema-->>Reclutador: Notifica confirmación o rechazo
```


## 3. Modelo de Datos


```mermaid

erDiagram
    VACANTE ||--o{ APLICACION : tiene
    CANDIDATO ||--o{ APLICACION : postula_a
    CANDIDATO ||--o{ ENTREVISTA : participa
    VACANTE ||--o{ ENTREVISTA : organiza

    USUARIO ||--o{ VACANTE : crea
    USUARIO ||--o{ ENTREVISTA : agenda
    USUARIO ||--o{ MENSAJE : recibe
    CANDIDATO ||--o{ DOCUMENTO : posee
    CANDIDATO ||--o{ MENSAJE : recibe

    APLICACION {
      string id
      string id_candidato
      string id_vacante
      datetime fecha_postulacion
      string estado
    }
    VACANTE {
      string id
      string titulo
      string descripcion
      datetime fecha_publicacion
      string estado
    }
    CANDIDATO {
      string id
      string nombre_completo
      string email
      string telefono
      string estado_postulacion
    }
    ENTREVISTA {
      string id
      string id_candidato
      string id_vacante
      datetime fecha_hora
      string tipo
      string estado
    }
    USUARIO {
      string id
      string nombre
      string email
      string rol
    }
    MENSAJE {
      string id
      string id_usuario
      string contenido
      string tipo
      datetime fecha_envio
      string estado
    }
    DOCUMENTO {
      string id
      string id_candidato
      string tipo
      string url_almacenamiento
      datetime fecha_subida
    }

```

## 4. Diseño Alto Nivel