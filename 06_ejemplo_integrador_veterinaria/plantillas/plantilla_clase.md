# Clases Detectadas — Veterinaria

| Clase | Descripción | Posibles atributos |
|---|---|---|
| Mascota | Representa al animal atendido | nombre, especie, raza |
| Cliente | Dueño de la mascota | dni, nombre, telefono |
| Turno | Representa una cita médica | fecha, hora, estado |
| Consulta | Atención veterinaria realizada | fechaConsulta, observaciones |
| Diagnostico | Resultado de la consulta | descripcion, tratamiento |

---

# Relaciones Detectadas

- Un Cliente puede tener varias Mascotas.
- Una Mascota puede tener varios Turnos.
- Un Turno puede generar una Consulta.
- Una Consulta puede contener un Diagnóstico.