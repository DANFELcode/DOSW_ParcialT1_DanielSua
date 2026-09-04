# DOSW_ParcialT1_DanielSua

##  Diagrama de contexto

![diagrama de contexto](docs/context.png)


## Requerimientos

#### Funcionales
1. El sistema debe poder conectarse a dos sistemas externos:
    * Enlace academico(para validar las materias)
    * NotifyMe(para enviar notificaciones sobre reservas)
2. El sistema debe tener reglas para la gestion y toma de tutorias tales como:
    * Solo permitir solicitar si esta inscrito en la materia
    * Permitir maximo 30 minutos de reserva para tutores profesores y 60 minutos para tutores estudiantes de pregrado
3. El sistema debe retornar al solicitante el mejor tutor disponible basado en tres criterios:
    * FASTEST_AVAILABLE(se busca el mas rapido disponible)
    * EXPERT_FIRST(prioriza profesores)
    * PEER_TUTORING(prioriza tutores)


#### No funcionales
1. Se debe emplear una tipografia legible que cumpla con los estandares minimos de contraste y accesibilidad web
2. El diseño debe incluir la paleta de colores del programa Ingenieria de sistemas y la identidad visual institucional
