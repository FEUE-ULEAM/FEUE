# 🏛️ Portal Oficial de la FEUE - ULEAM

Plataforma web oficial de la **Federación de Estudiantes Universitarios del Ecuador (FEUE) - Filial ULEAM**. Este es un espacio digital colaborativo, institucional y sin fines de lucro, diseñado para centralizar información relevante para el estudiantado, optimizar la logística de eventos universitarios, difundir oportunidades académicas y proyectar una gestión moderna y transparente.

🌐 **Sitio en producción:** [feue.uleam.edu.ec](https://feue.uleam.edu.ec)

---

## 📋 Sobre el Proyecto y Propósito

Infraestructura digital iniciativa **Coordinación General de la FEUE ULEAM 2026** con el objetivo de dotar a la representación estudiantil de herramientas tecnológicas propias. 

### ¿Qué se debe publicar aquí?
* **Información Institucional:** Comunicados oficiales, normativas, estatutos, rendición de cuentas y noticias de interés universitario.
* **Gestión de Eventos:** Módulos interactivos, landing pages, cronogramas y sistemas de acreditación o pases digitales para eventos institucionales (ej. Murga Universitaria, congresos, brigadas, ).
* **Herramientas para el Estudiante:** Recursos de utilidad pública como mapas interactivos del campus, guías de trámites y enlaces a oportunidades académicas.

---

## 🔒 Políticas de Seguridad y Privacidad (Lectura Obligatoria)

⚠️ **ESTE ES UN REPOSITORIO PÚBLICO.** Cualquier archivo subido a este espacio puede ser visto y descargado por cualquier persona en la red. 

Para proteger la integridad de la organización y cumplir con la Ley Orgánica de Protección de Datos Personales (LOPDP), **queda estrictamente prohibido**:
1. **Exponer datos personales:** Nunca subir bases de datos en Excel, CSV, JSON o código fuente que contengan nombres completos vinculados a números de cédula, teléfonos personales, correos privados o direcciones de estudiantes y docentes.
2. **Subir credenciales o llaves privadas:** Jamás incluir contraseñas, tokens de acceso, llaves privadas de APIs (Firebase/Google Cloud) con permisos de escritura sin reglas de seguridad, ni certificados digitales (`.p12`).
3. **Almacenar documentos confidenciales:** Actas internas reservadas o información sensible deben gestionarse de forma local o en almacenamiento institucional privado, nunca en este repositorio.

*(Nota técnica: Las configuraciones sensibles o bases de datos administrativas deben manejarse mediante variables de entorno, almacenamiento local aislado o servicios en la nube debidamente asegurados).*

---

## 📂 Estructura y Organigrama del Proyecto

El repositorio está organizado de manera modular para facilitar su mantenimiento por futuras directivas:

```text
feue-uleam/
├── 📁 admin/                 # Panel de control y gestión interna de la directiva
│   ├── dashboard.js          # Lógica del panel administrativo
│   ├── gobierno.html         # Módulo de gestión de gobierno estudiantil
│   └── login.html            # Interfaz de autenticación administrativa
├── 📁 assets/                # Recursos globales (logotipos FEUE, fuentes, estilos base)
├── 📁 invitaciones2/         # Módulo web para invitaciones protocolarias y eventos
│   └── index.html
├── 📁 mapa-uleam/            # Mapa interactivo de unidades académicas y campus
│   ├── 📁 assets/            # Íconos y gráficos específicos del mapa
│   ├── 📁 css/               # Hojas de estilo del mapa
│   ├── 📁 js/                # Lógica de interactividad y geolocalización
│   └── index.html
├── 📁 murga/                 # Plataforma logística para la Murga Universitaria ULEAM
│   ├── 26murgapass.html      # Sistema de pases digitales / acreditación 2026
│   └── murgamain.html        # Página principal y reglamento del evento
├── 📁 pases/                 # Sistema general de generación y validación de pases
├── 📄 CNAME                  # Configuración de dominio personalizado (feue.uleam.edu.ec)
├── 📄 index.html             # Página de inicio (Landing Page principal de la FEUE)
└── 📄 README.md              # Documentación oficial y lineamientos del repositorio
```
📜 Créditos y Derechos
Todos los derechos reservados © 2026 - FEUE ULEAM.

Iniciativa desarrollada e impulsada por el Coordinador General de la FEUE ULEAM 2025-2027.

El código base se mantiene abierto para fines de transparencia, auditoría y continuidad institucional de la representación estudiantil universitaria, los contenidos e imagen deben mantener el respeto y homogeneidad institucional, la administración y el contenido publicado son responsabilidad de la FEUE ULEAM y deberán mantenerse dentro de las políticas y normativas vigentes de la Universidad Laica Eloy Alfaro de Manabi. La Dirección Institucional se reserva la facultad de suspender el subdominio en caso de incumplimiento.
