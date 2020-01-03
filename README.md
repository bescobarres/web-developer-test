<div align="center">
	<div>
		<img width="200" src="http://e-volution.co/wp-content/uploads/2017/09/evolution-desktop.png" alt="Footters Core">
	</div>
    <h1 width="200">Web Developer Test</h1>
	<p>La siguiente es una prueba para evaluar aspectos técnicos de los candidatos a  <b>desarrollador Web</b>.</p>
</div>

## Introducción
Este repositorio contiene una serie de requerimientos de un Caso Práctico, que busca evaluar las capacidades técnicas del candidato con respecto a las principales funciones y responsabilidades que se requieren dentro del área de Desarrollo de Tecnología de _e-volution_.

#### ¿Qué se busca evaluar?
Principalmente los siguientes aspectos:
* Creatividad para resolver los requerimientos.
* Calidad del código entregado (estructura y buenas prácticas).
* Eficiencia de la solución entregada.
* Familiaridad con librerías, frameworks y plataformas de desarrollo.

## Importante
1. No hay tiempo establecido para entregar la prueba. Aun así, recomendamos emplear un máximo de **3-4 días** y enviar todo lo que puedas.
2. Se recomienda añadir un `archivo.md` en la solución aportada para explicar mediante texto lo que se considere oportuno.
3. **Al finalizar**, existen 2 opciones para entregar su proyecto:
    * Subir la prueba al repositorio personal y enviar la url del repositorio a la siguiente dirección de correo electrónico [administracion@e-volution.co](mailto:administracion@e-volution.co).
    * Crear un archivo comprimido ( _.zip_ ) de su proyecto y enviar a la siguiente dirección de correo electrónico [administracion@e-volution.co](mailto:administracion@e-volution.co).

## Descripción
Desarrollar una aplicación que permitirá a los usuarios crear y gestionar varias tareas.
La aplicación debe almacenar los siguientes datos en una estructura de base de datos
correctamente normalizada:

1. Nombre de la tarea.
2. Prioridad de la tarea.
3. Fecha de vencimiento.

El sistema debe requerir autenticación para poder visualizar y/o editar las tareas
del usuario actualmente conectado.
La autenticación debe hacerse a través de combinación de correo electrónico/contraseña.

Las tareas serán de propiedad de un único usuario (el creador de la tarea) y deben alertar
al usuario que alguna tarea se va a vencer a través de la interfaz gráfica al iniciar sesión.

Implementar una vista única con una interfaz tipo "modal" para añadir los elementos pendientes y
una interfaz de lista que permite al usuario gestionar (eliminar/editar) las tareas pendientes.

Ademas se debe desarrollar un formulario de registro para darle la oportunidad a los usuarios nuevos
de ingresar al sistema y administrar sus tareas.

### Notas
* La prueba debe realizarse en NodeJs.
* La prueba debe realizarse con algun framework de Javascript como ReactJs, Angular ó VueJs.
* Se puede usar cualquier motor base de datos, aunque valoramos preferiblemente MongoDB.
* Puntos extras por implementación de unit tests.
* Se valorará un correcto control de errores.
* Total libertad para añadir cualquier funcionalidad extra que considere interesante, ya sea para extender o mejorar la descrita.
