# Modelo de datos

## Cliente
- id
- nombre
- teléfono
- correo
- dirección

## Mascota
- id
- nombre
- especie
- raza
- fecha de nacimiento
- peso
- cliente (dueño)

## Cita
- id
- fecha y hora
- motivo
- veterinario
- mascota
- estado: solicitada, confirmada, cancelada o completada

## Historial médico
Cada mascota tiene un historial con sus consultas:
- fecha
- motivo
- diagnóstico
- tratamiento
- vacunas

## Relaciones
- Un cliente puede tener varias mascotas. Cada mascota tiene un solo dueño.
- Una mascota puede tener muchas citas. Cada cita es de una sola mascota.
- Cada mascota tiene un historial, y el historial tiene muchas consultas.
