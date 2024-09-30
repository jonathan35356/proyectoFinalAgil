# proyectoFinalAgil
Gestion de reservas de un restaurante de comida rapida 

Descripción:
Este proyecto es un sistema de reservas para un restaurante de comidas rápidas que permite a los usuarios realizar reservas en línea, optimizando la gestión de mesas y mejorando la experiencia del cliente.

/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

Objetivos:
- Proporcionar un sistema de reservas simple y efectivo.
- Facilitar la visualización del menú del restaurante.
- Permitir la gestión de pedidos y la cola de espera de manera eficiente.
- Notificar a los usuarios cuando sus pedidos están listos y disponibles.
- Mejorar la experiencia del cliente en un entorno de comida rápida.
- 
/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

Caracteristicas

Reserva gratuita: Los usuarios pueden reservar mesas sin costo al ingresar a la aplicación.
Visualización del menú: Acceso fácil al menú del restaurante.
Recepción de pedidos: Posibilidad de recibir pedidos a través de la aplicación.
Disponibilidad de mesa: Gestión de la disponibilidad de mesas según el horario.
Notificaciones: Alertas para los usuarios cuando sus pedidos están listos.
Gestión de la cola de espera: Información sobre la posición en la cola cuando el restaurante está lleno, indicando en qué fila se encuentran.
Aplicación móvil: Diseñada para ser utilizada en dispositivos móviles, con un diseño minimalista y fácil de usar.

/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
 
 Roadmap
1. Investigación y diseño inicial (Día 1)
1.1 Desarrollo de la interfaz de usuario minimalista (Día 1)
2 Implementación de la funcionalidad de reserva y visualización del menú (Día 2)
2.1. Integración de la gestión de pedidos y notificaciones (Día 2)
3 Pruebas y ajuste del sistema (Día 3)
3.1 Presentación del producto final (Día 3)
   
/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

Backlog del Producto
el backlog de tareas esta en TRELLO (https://trello.com/invite/b/66f5d68b1e5559bdfb2c59e8/ATTI0027ec40d1c7ea53dbf562e44b57a2cd286C9C30/proyecto-scrum)

/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
Sprint Planning

Duración del Sprint: 2 días
Historias de Usuario y Tareas
Historia de Usuario 1: Reservas y Disponibilidad

Como usuario, quiero poder hacer una reserva en línea de manera gratuita, para asegurar mi lugar en el restaurante.
Tareas:
  Definir los campos requeridos para la reserva (nombre, número de personas, fecha y hora).
  Definir los criterios de aceptación para la funcionalidad de reservas (la reserva debe ser gratuita, confirmación en tiempo real).
  Priorizar esta historia de usuario en el backlog y asegurar que esté clara para el equipo de desarrollo.
  Historia de Usuario 2: Ver la Disponibilidad de Mesas

Como usuario, quiero ver la disponibilidad de mesas según el horario seleccionado, para saber si hay espacio.
Tareas:
  Definir cómo se visualizará la disponibilidad de mesas (colores, estados: disponible/no disponible).
  Definir los criterios de aceptación (mostrar disponibilidad en tiempo real según el horario).
  Colaborar con el equipo para asegurar que el sistema gestione las reservas correctamente.
  Historia de Usuario 3: Ver el Menú

Como usuario, quiero ver el menú del restaurante, para elegir lo que quiero pedir.
Tareas:
  Definir cómo se mostrará el menú (categorías de comida, precios, descripciones).
  Definir los criterios de aceptación (el menú debe ser fácil de navegar, mostrar precios e incluir imágenes opcionales).
  Priorizar esta historia en el backlog y asegurarte de que el diseño de la interfaz sea intuitivo.
  Historia de Usuario 4: Hacer Pedidos

Como usuario, quiero poder hacer un pedido desde la aplicación, para que esté listo cuando llegue.
Tareas:
  Definir los pasos necesarios para hacer un pedido (selección de elementos, personalización del pedido, envío del pedido).
  Establecer los criterios de aceptación (debe permitir agregar múltiples elementos al carrito, confirmar el pedido y recibir una notificación cuando esté   
  listo).
  Revisar con el equipo de desarrollo la integración del sistema de pedidos con la cocina del restaurante.
  Historia de Usuario 5: Gestión de la Cola de Espera

Como usuario, quiero saber mi posición en la fila de espera cuando el restaurante esté lleno, para saber cuánto me falta para ser atendido.
Tareas:
  Definir cómo se mostrará la posición en la fila (número de personas antes, tiempo estimado de espera).
  Establecer los criterios de aceptación (debe mostrar la posición en la cola en tiempo real, con estimación precisa del tiempo de espera).
  Asegurarte de que el equipo implemente la funcionalidad para gestionar la cola y reflejar los cambios dinámicos.
  
///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
Asignación de Tareas

Desarrollador 1: Jael
Reservas y Disponibilidad:
  Tarea 1.1: Definir los campos requeridos para la reserva.
  Tarea 1.2: Definir los criterios de aceptación para la funcionalidad de reservas.
Ver la Disponibilidad de Mesas:
  Tarea 2.1: Definir cómo se visualizará la disponibilidad de mesas.
  
Desarrollador 2: María
Ver el Menú:
  Tarea 3.1: Definir cómo se mostrará el menú.
  Tarea 3.2: Definir los criterios de aceptación para el menú.
Hacer Pedidos:
  Tarea 4.1: Definir los pasos necesarios para hacer un pedido.
  
Desarrollador 3: Luis Edaurdo Villalba 
Gestión de la Cola de Espera:
  Tarea 5.1: Definir cómo se mostrará la posición en la fila.
Interfaz de usuario: En la página de la reserva, al confirmar la inclusión en la cola de espera, se mostrará un número indicando la posición actual en la fila
Actualización en tiempo real: Si la posición cambia, el usuario debe ver actualizaciones automáticas sin necesidad de recargar la página. Esto puede implementarse usando tecnologías como WebSockets o polling.
Notificaciones: Se puede enviar una notificación por SMS, correo electrónico o a través de la aplicación cuando su mesa esté lista o si la posición en la fila se ha actualizado significativamente 
Indicador de tiempo estimado: Además de la posición en la fila, se podría mostrar un tiempo estimado de espera basado en el promedio de tiempo por mesa.
  
  Tarea 5.2: Establecer los criterios de aceptación para la cola de espera.
Capacidad del restaurante: La cola de espera se activará solo si el restaurante ha alcanzado su capacidad máxima de reservas en un momento determinado.
Límite de espera: Se establecerá un límite máximo de clientes en la cola de espera. Si se excede ese límite, los usuarios podrían recibir un mensaje informándoles que no es posible hacer más reservas en ese momento.
Cancelación automática: Si un cliente no llega en el tiempo estimado para ocupar su mesa, será eliminado de la cola de espera, y se notificará al siguiente cliente en la fila.
Duración del turno: Se debe definir un tiempo máximo de espera aceptable para los clientes en cola, más allá del cual se les debe notificar la opción de cancelar o esperar más tiempo.
Prioridad especial: Puede haber criterios especiales de prioridad para ciertos usuarios, como clientes VIP o familias con niños pequeños
  
Colaboración:
Colaborar con Juan en la gestión de reservas y con María en la integración del menú y los pedidos.
Story Points (Opcional)
Reserva y Disponibilidad: 5
Ver la Disponibilidad de Mesas: 3
Ver el Menú: 4
Hacer Pedidos: 5
Gestión de la Cola de Espera: 4

