# 07 — Calendario y Citas

El módulo de **Calendario** en Odoo es la herramienta para gestionar la agenda

Además de las funcionalidades básicas de una agenda, posee las integraciones y el módulo de **Citas**

## 1. Calendario y Disponibilidad del Equipo

El módulo de Calendario ofrece una vista estándar similar a cualquier otra aplicación de agenda

- **Vistas:** El usuario puede filtrar la vista por día, semana o mes, según sus preferencias
- **Disponibilidad del Equipo:** Permite ver los calendarios de otros usuarios dentro de Odoo, facilitando la programación de reuniones en grupo
- **Creación de Eventos:** Se pueden crear eventos directamente desde el calendario, definiendo la hora de inicio y fin, o si es un evento de día completo
- **Recordatorios y Notificaciones:** Es posible establecer recordatorios por email o SMS, configurando con cuánta antelación se desea recibir la alerta

![Foto](../assets/img/07-calendario_y_citas/FotoCalendario01.png)
![Foto](../assets/img/07-calendario_y_citas/FotoCalendario02.png)

## 2. Integración con Google Calendar

Para centralizar toda la agenda, se recomienda vincular Odoo con **Google Calendar**

- **Configuración en GCP:** Crear un proyecto en Google Cloud Platform (por ejemplo, "ODU Calendar") y habilitar la **API de Google Calendar**
- **Credenciales:** Al crear las credenciales, seleccionar el tipo de aplicación **“Aplicación web”** 
- **URI de Redireccionamiento:** Debe configurar la URL autorizada para la redirección
- **Vínculo en Odoo:** En los **Ajustes de Calendario**, copiar y pegar el **Client ID** y **Client Secret** obtenidos de GCP

## 3. Odoo Meet o Enlaces Externos

Al crear un evento o reunión, Odoo permite definir la ubicación o el método de llamada

- **Enlaces Externos:** Se puede agregar una URL de llamada de plataformas externas como Zoom o Google Meet
- **Reunión de Odoo (Odoo Meet):** Odoo ofrece su propia opción de videollamada, permite iniciar la llamada directamente desde Odoo, añadir participantes y enviar mensajes dentro de la llamada. Incluso configurar opciones como detección de quién está hablando 
- **Gestión:** Las notas y archivos asociados a la reunión se almacenan en la base de datos

## 4. Módulo Citas (Enterprise)

El módulo de **Citas** es una aplicación de pago (Enterprise) diseñada para la programación de servicios

- **Tipos de Citas:** Se pueden configurar distintos tipos
- **Parámetros de Configuración:** Incluyen:
  - **Duración:** Tiempo de la cita
  - **Tiempo de Margen:** Intervalo entre citas para descanso o preparación
  - **Ventana de Planificación:** Fechas disponibles para reservar
  - **Tiempo Mínimo de Reserva:** Antelación mínima para reservar
  - **Disponibilidad:** Horarios en los que se puede agendar
- **Enlaces Públicos y Preguntas Previas:**  
  - Genera un enlace público para que la persona reserve
  - Se pueden configurar preguntas previas para recopilar información sobre el motivo de la cita
---

Una vez que la cita se reserva a través del enlace, se agenda automáticamente en el calendario de Odoo del usuario correspondiente