# Caso de Uso Elegido

Registrar Consulta Veterinaria

---

# Objetos Participantes

- Veterinario
- PantallaConsulta
- ControlConsulta
- Mascota
- Consulta
- Diagnostico

---

# Flujo Principal

1. El veterinario selecciona registrar consulta.
2. El sistema solicita los datos de la mascota.
3. El veterinario ingresa observaciones clínicas.
4. El sistema registra la consulta.
5. El veterinario registra el diagnóstico.
6. El sistema guarda la información y muestra confirmación.

---

# Mensajes Principales

| N° | Emisor | Receptor | Mensaje |
|---|---|---|---|
| 1 | Veterinario | PantallaConsulta | iniciarConsulta() |
| 2 | PantallaConsulta | ControlConsulta | registrarConsulta() |
| 3 | ControlConsulta | Mascota | buscarMascota() |
| 4 | ControlConsulta | Consulta | crearConsulta() |
| 5 | ControlConsulta | Diagnostico | registrarDiagnostico() |
| 6 | ControlConsulta | PantallaConsulta | mostrarConfirmacion() |