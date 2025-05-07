## Mermaid no tiene diagramas de casos de usos :(

# Relaciones entre Actores Externos y Procesos

**Alumno:**
- Participa en el **Proceso de Matrícula**
  - Dentro de este flujo se incluye el **Proceso de Control de Asistencia**  
    <<include>>
  - Una vez completada la Matrícula, se extienden:
    - **Proceso de Asignación de Aulas y Secciones**  
      <<extend>>
    - **Proceso de Evaluación Académica y Pedagógica**  
      <<extend>>

**Apoderado:**
- Colabora en el **Proceso de Matrícula**
- Recibe notificaciones del **Proceso de Control de Asistencia**