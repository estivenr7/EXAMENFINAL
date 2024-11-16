Este es el codigo de mi examen final
Sistema de Gestión de Reservas de Habitaciones de un Hotel
Se solicita el desarrollo de un sistema que permita gestionar reservas en un hotel. El sistema debe incluir las
siguientes funcionalidades:
1. Registrar una nueva reserva, proporcionando:
• Nombre del cliente
• Fecha de inicio y fecha de fin de la reserva
• Tipo de habitación (Sencilla, Doble, Suite)
2. Listar todas las reservas existentes, mostrando el cliente, las fechas de reserva y el tipo de habitación.
3. Actualizar las fechas de una reserva existente.
4. Cancelar una reserva, eliminándola de la base de datos.
Requerimientos técnicos:
Backend:
• Desarrollado en Java 17 o superior con Spring Framework.
• Debe exponer un API REST con operaciones CRUD que permita manejar las reservas.
Base de Datos:
• Usar MySQL con una base de datos llamada hotel_reservas y una tabla reservas con las siguientes
columnas:
o id 
o nombre_cliente 
o fecha_inicio 
o fecha_fin 
o tipo_habitacion 

Frontend:
• Crear una interfaz en React que permita interactuar con las funcionalidades del backend:
• Un formulario para registrar reservas.
• Una tabla que liste todas las reservas.
• Botones para actualizar fechas y cancelar reservas
