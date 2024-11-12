# Sistema de Reserva de Mesas en un Restaurante

## Proyecto PJ 01: TRANSVERSAL

### Objetivo
Este proyecto tiene como objetivo la creación desde cero de un sitio web integrado en la intranet de un restaurante para la gestión de reservas de mesas. Este sistema permitirá a los camareros gestionar y visualizar en tiempo real la disponibilidad de mesas y sillas en el restaurante.

### Duración
Duración aproximada del proyecto: **30 horas**

### Organización del Espacio
- **Metodología**: Basada en retos
- **Agrupación de alumnos**: Trabajo en equipo (4 alumnos)

#### Estructura del Restaurante
El restaurante cuenta con diferentes espacios, específicamente:
- **3 terrazas**
- **2 comedores**
- **4 salas privadas**

#### Funcionamiento de la Aplicación
Los usuarios de la aplicación serán los **camareros del restaurante**, quienes deben poder ver:
- La disponibilidad de mesas.
- Las sillas que puede tener cada mesa.

El sistema permitirá que los camareros marquen las mesas como ocupadas cuando lleguen los clientes, indicando que cada mesa estará ocupada o libre en tiempo real, sin necesidad de reservarla para un día y hora específicos. Esto hará que sea dinámico el hecho de poder ver la disponiblidad que tenemos en el restaurante

#### Gestión de Usuarios y Recursos
Cada camarero debe iniciar sesión en el sistema (login) antes de marcar una mesa como ocupada o liberarla. Una vez que los clientes se retiran, el camarero liberará el recurso (mesa) para que esté disponible de nuevo. Los usuarios ya están predefinidos en la base de datos, por lo que no se necesitan formularios de alta/baja/modificación.

#### Historial de Ocupación
Se debe registrar la fecha y hora en que una mesa es ocupada y posteriormente liberada. El sistema debe permitir visualizar un historial de ocupaciones, filtrado por recurso (mesa) y ubicación/sala, lo cual ayudará a evaluar la frecuencia de uso de cada recurso.

### Desglose por Módulos

1. **MP9 - Diseño de interfaces web**
   - Realizar un mockup del sitio web, con diseño homogéneo, uso de CSS y responsividad.

2. **MP6 - Desarrollo web en entorno cliente**
   - Implementar acciones dinámicas en JavaScript, como validación de formularios y uso de SweetAlerts.

3. **MP7 - Desarrollo web en entorno servidor**
   - Conexión con la base de datos mediante consultas de selección (filtros de búsqueda) y modificación (reserva y liberación de recursos).
   - Uso de sesiones para login/logout.

4. **MP2 - Bases de datos**
   - Creación y poblado de la base de datos, así como consultas para actualizar y filtrar ocupaciones.

5. **MP8 - Despliegue de aplicaciones web**
   - Planificación del proyecto (GANTT o Roadmap en GitHub).
   - Asignación de roles en el equipo (coordinador, impulsor, finalizador).
   - Seguimiento diario con reuniones (Daily Meeting).
   - Uso de un repositorio compartido con el profesorado, con actualizaciones diarias de código.
   - Distribución del proyecto en ramas, issues, milestones y labels.

### Rol del Equipo Docente
- Observación directa de los equipos de estudiantes
- Registro de observaciones en el aula

### Integrantes del Equipo
- **Eric Alcazar: Impulsor**
- **Dylan Castles: Finalizador**
- **David Hompanera: Cohesionador**
- **Manav Sharma: Coordinador**

