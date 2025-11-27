[🇬🇧 English version](README.md)

# Ingeniero de Software Backend (Python · FastAPI · AWS)

Ingeniero Físico e **ingeniero de backend y sistemas** freelance.  
Diseño y construyo **servicios backend y flujos de datos robustos** en Python, con foco en **APIs REST, PostgreSQL y AWS (EC2/RDS/S3)**. En varios proyectos he conectado estos backends con **aplicaciones móviles para operación en campo (offline→online)** y, cuando es necesario, con **dispositivos embebidos (STM32/ESP32)**.

Mi enfoque principal está en la **fiabilidad del backend, la integridad de los datos y la trazabilidad**.  
Como línea secundaria, tengo experiencia en **sistemas embebidos y de borde** para integración hardware–software.

Contacto: **agraciamartelo@gmail.com · Medellín, Colombia**  
LinkedIn: [linkedin.com/in/alberto-gracia](https://www.linkedin.com/in/alberto-gracia)

---

## Experiencia principal

- **Backend y APIs (Principal)**  
  Python (FastAPI/Flask), diseño de APIs REST, JWT/OAuth2, RBAC, OpenAPI/Swagger, SQLAlchemy asíncrono, paginación, validación y manejo de errores.

- **Cloud y DevOps (Principal)**  
  AWS (EC2, RDS PostgreSQL, S3, SES), Docker, Git, GitHub Actions (CI/CD), Terraform, configuración de entornos, logging y monitoreo básico.

- **Datos y Observabilidad (Principal)**  
  PostgreSQL, diseño de esquemas, migraciones con Alembic, optimización básica de consultas, logs estructurados, métricas y trazabilidad/auditoría.

- **Sistemas Embebidos y de Borde (Secundario)**  
  STM32, ESP32, C/C++, UART/SPI/I2C, timers/PWM (steppers/servos), patrones básicos de OTA y watchdog, protocolos edge–cloud.

- **Frontend y Móvil (Complementario)**  
  Angular (TypeScript) y Flutter (Dart) para clientes web/móvil que consumen APIs REST, con almacenamiento local y flujos de sincronización.

---

## Proyecto destacado — Tablero de Ajedrez Autónomo

**ChessProject** — Tablero de ajedrez robótico basado en STM32 con integración de IA en tiempo real  

Sistema electromecánico que ejecuta partidas de ajedrez en un tablero físico. Un pórtico XY tipo CNC, accionado por motores paso a paso y un imán con servo, mueve las piezas automáticamente. El firmware en STM32 gestiona el control de movimiento y la seguridad, mientras que un backend en Python orquesta la lógica de juego y la telemetría.

**Stack técnico**

- Firmware: STM32/HAL (C), timers/PWM, finales de carrera, protocolo UART  
- Backend: Flask (Python), Stockfish, python-chess, Docker  
- Herramientas: Eagle PCB, Linux, logging y telemetría básicos

**Aspectos destacados**

- Traducción de movimientos de IA/online a movimiento físico sobre el tablero  
- Homing seguro, manejo de límites y recuperación ante errores  
- Guía de puesta en marcha documentada y diagramas de hardware reproducibles

**Próximos pasos**

- Añadir perfiles de velocidad/aceleración y ajuste fino de jitter  
- Estandarizar telemetría con ROS2 (TF2, colcon)  
- Mejoras mecánicas (rigidez, cableado, carcasa)

Videos de demostración:

- [Video 1](https://drive.google.com/file/d/1ilU88anA28Sm5uKsdmvKJDmgogQCD1F5/view)  
- [Video 2](https://drive.google.com/file/d/19l9fdWrFyc15zySGSjjqOn4_oBJ1EvTn/view)

---

## Stack tecnológico

### Lenguajes
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?logo=postgresql&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=white)

### Frameworks y librerías
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?logo=python&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?logo=angular&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white)
![ROS2](https://img.shields.io/badge/ROS2-22314E?logo=ros&logoColor=white)

### Bases de datos
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)

### DevOps / Cloud
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=github-actions&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?logo=terraform&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0089D6?logo=azure-devops&logoColor=white)

### Calidad y APIs
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?logo=pytest&logoColor=white)
![OpenAPI](https://img.shields.io/badge/OpenAPI-6BA539?logo=openapiinitiative&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?logo=swagger&logoColor=black)

---

## Idiomas

| Idioma   | Nivel |
|----------|-------|
| Español  | Nativo |
| Inglés   | C1 |
| Alemán   | B2 |

---

## Sobre mí

Ingeniero Físico con formación multidisciplinaria, combinando **desarrollo backend, infraestructura en la nube y sistemas embebidos**.  
Actualmente enfocado en **roles de backend (Python, FastAPI, AWS, PostgreSQL, CI/CD)**, manteniendo un fuerte interés en proyectos de robótica y sistemas embebidos que requieran una integración estrecha entre hardware y software.
