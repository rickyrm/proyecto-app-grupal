## **MVP: Funcionalidades mínimas**
El MVP incluirá las funciones esenciales para que los usuarios puedan organizar tareas y gastos sin complicaciones. 

### **Características principales del MVP**
1. **Registro e inicio de sesión de usuarios**  
   - Cada usuario puede registrarse con un correo electrónico y contraseña.
   - Crear un grupo para su piso compartido o unirse a uno existente con un código de invitación.

2. **Gestión de tareas**  
   - Un calendario compartido donde los usuarios puedan crear y asignar tareas (e.g., limpieza de cocina, sacar la basura).  
   - Opciones básicas: añadir tarea, asignarla a un usuario, marcarla como completada.

3. **División de gastos**  
   - Registrar gastos compartidos (e.g., supermercado, alquiler, servicios).  
   - Dividir automáticamente el coste entre los usuarios del grupo.  
   - Mostrar un saldo básico para ver quién debe a quién.

4. **Notificaciones básicas**  
   - Enviar recordatorios para tareas asignadas o para saldar deudas pendientes.

5. **Interfaz amigable y sencilla**  
   - Panel principal con acceso rápido a:
     - Calendario de tareas.
     - Registro de gastos.

---

## **Historias de usuario**
Estas historias reflejan las necesidades básicas de los usuarios y guían el desarrollo del MVP.

### **Gestión de tareas**
1. Como **usuario**, quiero crear una tarea con un nombre, fecha y asignar un responsable para organizar las tareas del hogar.
2. Como **usuario**, quiero ver todas las tareas en un calendario para saber qué se necesita hacer y cuándo.
3. Como **usuario**, quiero marcar una tarea como completada para que los demás sepan que ya está hecha.

### **Gestión de gastos**
4. Como **usuario**, quiero registrar un gasto con una descripción y un monto para dividirlo entre los compañeros.
5. Como **usuario**, quiero ver un resumen de quién debe dinero y cuánto, para evitar malentendidos.
6. Como **usuario**, quiero liquidar deudas para mantener el balance actualizado.

### **Notificaciones**
7. Como **usuario**, quiero recibir recordatorios de mis tareas asignadas para no olvidarlas.
8. Como **usuario**, quiero ser notificado si alguien registra un gasto para estar al tanto.

### **Registro y grupos**
9. Como **usuario**, quiero crear una cuenta para usar la aplicación y tener acceso a mi grupo de convivencia.
10. Como **usuario**, quiero unirme a un grupo con un código para participar en la organización del piso.

---

## **Diagrama de navegación**
1. **Pantalla de inicio**  
   - Botones: "Registrarse", "Iniciar sesión".
   
2. **Pantalla principal (Dashboard)**  
   - Calendario de tareas.  
   - Resumen de gastos.  
   - Botón "Añadir" (para crear tareas o gastos).

3. **Pantalla de tareas**  
   - Lista de tareas pendientes.  
   - Calendario.  
   - Botón "Nueva tarea".

4. **Pantalla de gastos**  
   - Registro de gastos compartidos.  
   - Resumen de saldos.  
   - Botón "Nuevo gasto".

---

### **Siguientes pasos**
- **Prototipo**: Diseñar una maqueta de las pantallas para entender la interfaz.
- **Tecnología**: Usar herramientas simples como:
  - **Frontend**: React.js.
  - **Backend**: Node.js con Express o Django.
  - **Base de datos**: Firebase o MongoDB (para simplicidad en el MVP).
- **Iteración**: Lanzar el MVP y recopilar feedback.


