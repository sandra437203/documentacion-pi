#Caracterizacion
# Caracterización del Proyecto: MoscoDays

## 1. ¿Qué es este proyecto y qué problema solucionamos?
* **Nombre del proyecto:** Mosco Days
* **El problema:** Ahora mismo, pedir los días moscosos es un rollo. Se hace todo en papel, hay que rellenar mil formularios, pasar la información a mano, revisar plazos a ojo y al final se pierde mucho tiempo y es fácil que se pierdan papeles o haya líos con los turnos.
* **Nuestra solución:** Vamos a hacer una aplicación web para que los profes puedan pedir sus días libres en un parpadear, eligiendo el día en el calendario y dejando el trabajo preparado para los alumnos sin complicaciones.

---

## 2. Objetivos

* **Objetivo principal:** Digitalizar por completo el proceso de los días moscosos para dejar atrás el papeleo y conseguir que todo sea mucho más rápido, cómodo y transparente.
* **Objetivos específicos:**
  * Que el sistema compruebe solo si te puedes coger el día.
  * Que cada profesor pueda ver qué días le quedan libres (separando si estamos en época de clases o de vacaciones) y mirar cómo van sus solicitudes
  * Facilitarle la vida a dirección para que puedan ver las peticiones de un vistazo y dar al botón de aprobar o rechazar escribiendo el motivo
  * Tener centralizados los datos de los profes, los turnos y el calendario escolar del centro

---

## 3. Requisitos principales de la app

### Lo que los usuarios podrán hacer
* **Pedir días libres:** El profe entra, selecciona la fecha (avisando con al menos una semana de antelación) y deja apuntado el itinerario o tareas para los alumnos.
* **Consultar saldo y estado:** Ver los días que te quedan disponibles y saber si tu solicitud está pendiente, aceptada o rechazada.
* **Revisión de dirección:** El director o responsable puede entrar, ver quién pide el día y aceptarlo o denegarlo justificando el motivo.
* **Comprobación automática de normas:** 
  * Controlar que no se pidan más de 8 personas a la vez (4 de mañana y 4 de tarde).
  * Bloquear fechas prohibidas (los 7 primeros/últimos días de curso, antes o después de Navidad/Pascua, y épocas de exámenes o evaluación).
* **Panel de administración:** Para cargar los calendarios, configurar los turnos y meter los datos del profesorado sin tener que picarlo a mano en el código.

### Características técnicas (Requisitos no funcionales)
* **Multiplataforma (Web):** Se podrá usar desde ordenadores, tablets o móviles sin necesidad de instalar nada raro.
* **Fácil e intuitiva:** Por ejemplo, que los días que no se puedan coger salgan marcados en rojo para no perder el tiempo intentando seleccionarlos.
* **Segura:** Mantener bien guardados y protegidos los datos de los profesores.

---