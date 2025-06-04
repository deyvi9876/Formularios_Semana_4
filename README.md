# Formularios_Semana_4
README – Formulario de Inscripción Escolar (Explicación de Etiquetas)
Este proyecto es un formulario web moderno diseñado para simular la inscripción de estudiantes a una escuela, con enfoque en las etiquetas HTML semánticas, estilos CSS interactivos y funcionalidades básicas con JavaScript puro.

 Estructura y Explicación de Etiquetas HTML
html
Copiar
Editar
<!DOCTYPE html>
<html lang="es"> ... </html>
Declara el tipo de documento (HTML5) y el idioma principal (español).

 Etiquetas usadas en el formulario
Etiqueta	Descripción
<form>	Contenedor principal del formulario. Usa id para manejar eventos con JavaScript.
<label>	Etiqueta asociada a cada campo (input, select, etc.) con el atributo for. Mejora accesibilidad.
<input>	Campo de entrada. Se usa con diferentes type según la información requerida: text, email, number, radio, checkbox, tel.
<select>	Lista desplegable (usada para elegir la ciudad). Contiene múltiples <option>.
<textarea>	Área de texto para comentarios más largos.
<button>	Botón para enviar o limpiar el formulario.
<div>	Estructura visual y agrupación de elementos (.form-group, .container, .resultado).
<h1>, <h3>	Títulos jerárquicos que estructuran el contenido.
<span>	Se usa para mostrar etiquetas dentro de los datos enviados (.etiqueta).
<small>	Texto auxiliar debajo de los inputs para dar instrucciones o validaciones.

 CSS – Estilos Interactivos
Selectores de clase (.clase): usados para dar estilos personalizados a cada bloque del formulario.

Pseudoclases:

:hover → cambio de color o elevación en botones e imágenes.

:focus → resalta campos activos para mejor UX.

Transiciones (transition): hacen los cambios más suaves.

Flex y responsive design: se adapta a distintos tamaños de pantalla.

Fondos:

Se usó background: url(...) para establecer una imagen de fondo.

También se agregó una capa .background-overlay semitransparente.

 Validaciones HTML5
required: obliga al usuario a completar ese campo.

pattern: restringe el formato del texto (ej: solo letras o solo números).

min / max: usados en <input type="number"> para definir edad mínima y máxima.

placeholder: texto guía dentro del input antes de escribir.

 Funcionalidad JavaScript
Se utilizó addEventListener('submit') para interceptar el envío del formulario.

Se usó FormData para extraer valores de los campos.

Se construyó el resultado dinámicamente y se muestra en pantalla.

Se usó scrollIntoView() para hacer scroll automático hacia el resultado.

Un botón adicional limpia el formulario con form.reset().

