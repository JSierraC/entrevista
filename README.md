# Proyecto Clonado de: https://github.com/yihyang/laravel-car-interview-question

# Laravel Car Solutions

The Car Solutions posee múltiples talleres ubicados en diferentes ubicaciones con diferentes horarios de trabajo.

Actualmente, la compañía está construyendo una plataforma para su personal administrativo con el fin de programar citas de reserva con diferentes talleres.

Siempre que un cliente llama para programar una cita. El personal de administración debe poder verificar la disponibilidad de los talleres, hacer recomendaciones y también crear una nueva cita.

El personal del taller deberá tener acceso a las citas todos los días para preparar las piezas y herramientas necesarias.

## Your task

Crear endpoints que permitan al personal de administración:

1. Enumere todas las citas con la capacidad de filtrar por cada taller según el workshop_id proporcionado

2. Programe una cita según la solicitud del cliente

  - Debería poder crear una nueva cita basada en la información proporcionada

  - Aparte de eso, también debe detectar la disponibilidad del taller y evitar que se creen citas con tiempo superpuesto.

3. Recomendar los talleres según la disponibilidad y las ubicaciones.

  - El endpoint debe poder recomendar talleres basados ​​en

    1. Disponibilidad (Mostrar taller que no tenga cita durante el tiempo previsto)

    2. Ubicación (clasifique el taller según la distancia)

## Notas

- Siéntase libre de incluir cualquier suposición o nota que tenga

- Incluya todas las instrucciones o guías que tenga para que podamos probar el trabajo que ha realizado

