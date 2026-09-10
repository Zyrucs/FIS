# Requerimientos Funcionales 

## 1. Requerimientos Funcionales

| ID | Requerimiento | Descripción |
|---|---|---|
| **RF-001** | Registro y gestión de usuarios | El sistema deberá permitir registrar, consultar, modificar y gestionar los usuarios de acuerdo con su rol dentro de la escuela de patinaje. |
| **RF-002** | Gestión de roles | El sistema deberá manejar los roles de **Estudiante/Patinador, Entrenador, Padre de familia y Administrador**, asignando a cada uno los permisos correspondientes. |
| **RF-003** | Gestión de patinadores | El sistema deberá permitir al Administrador crear, consultar y modificar la información de los patinadores registrados en el sistema. |
| **RF-004** | Gestión de entrenadores | El sistema deberá permitir al Administrador crear, consultar y modificar la información de los entrenadores. |
| **RF-005** | Gestión de padres de familia | El sistema deberá permitir al Administrador crear, consultar y modificar la información de los padres o acudientes asociados a los patinadores. |
| **RF-006** | Gestión de sanciones | El sistema deberá permitir al Entrenador y al Administrador crear y modificar sanciones asociadas a los patinadores. |
| **RF-007** | Consulta de sanciones | El sistema deberá permitir consultar el historial de sanciones de cada patinador. |
| **RF-008** | Autorización de competencias | El sistema deberá permitir al Padre de familia autorizar o rechazar la participación del patinador en competencias. |
| **RF-009** | Autorización de cambio de uniforme | El sistema deberá permitir al Padre de familia autorizar o rechazar solicitudes relacionadas con cambios de uniforme del patinador. |
| **RF-010** | Registro de pagos | El sistema deberá permitir registrar los pagos realizados por los usuarios correspondientes a los servicios de la escuela de patinaje. |
| **RF-011** | Registro del medio de pago | El sistema deberá permitir registrar si un pago fue realizado mediante **efectivo o transferencia bancaria mediante Bre-B**. |
| **RF-012** | Validación de pagos | El sistema deberá permitir validar el estado de los pagos registrados, diferenciando entre pagos pendientes, validados y rechazados. |
| **RF-013** | Dashboard de pagos | El sistema deberá proporcionar un dashboard que permita visualizar y consultar información relacionada con los pagos de los patinadores. |
| **RF-014** | Consulta del estado de cuenta | El sistema deberá permitir consultar el estado de los pagos de cada patinador, incluyendo pagos realizados y pagos pendientes. |
| **RF-015** | Control de asistencia | El sistema deberá permitir registrar y consultar la asistencia de los patinadores a los entrenamientos. |
| **RF-016** | Consulta de asistencia | El sistema deberá permitir consultar el historial de asistencia de cada patinador. |
| **RF-017** | Migración de información existente | El sistema deberá permitir incorporar la información existente de los patinadores almacenada actualmente en la base de datos del propietario. |
| **RF-018** | Gestión de información de pagos | El sistema deberá permitir reemplazar el control de pagos realizado actualmente mediante archivos de Excel por un sistema centralizado de gestión y consulta. |


- El sistema **no contará con una pasarela de pago**.
- Los medios de pago contemplados inicialmente son:
  - **Efectivo**
  - **Transferencia mediante Bre-B**
- El sistema deberá registrar y permitir validar los pagos, pero no procesará directamente la transacción bancaria.
- Actualmente el control de pagos se realiza mediante un archivo de **Excel**, por lo que el nuevo sistema deberá centralizar esta información.
- El Administrador tendrá permisos para gestionar patinadores, entrenadores y padres de familia, además de crear y modificar sanciones.
- El Entrenador podrá crear y modificar sanciones y gestionar la asistencia.
- El Padre de familia tendrá la responsabilidad de autorizar competencias y cambios de uniforme.
