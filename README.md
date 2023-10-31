# Pre Parcial

Para este ejercicio se debe contar con la API provista para la materia: `https://github.com/mauriciobergallo/utn-dabd-restapi`; la url que se debe utilizar es: `http://localhost:3000/api/products/`

## Se pide

A partir del formulario HTML hecho en Bootstrap se debe...
- Migrar el form a ReactiveForm
- Crear las validaciones:
  - Product Name: mínimo de caracteres 5, campo requerido.
  - Product Description: mínimo de caracteres 10, campo requerido.
  - Product Price: valor mínimo 1, campo requerido.
  - Product Location: mínimo de caracteres 5, campo requerido.
  - Product Stock: valor mínimo 1, valor máximo 100, campo requerido.
  - Product TimeFraction: valor mínimo 10, máximo 60.
- Validación Asíncrona: Se debe validar que al momento de crear el product, el mismo no exista en el BackEnd
- Utilizando ValueChange, debemos:
  - Si es producto, agregar Stock y sus validaciones.
  - Si es servicio, no agregar Stock y definir el TimePeriod y sus validaciones.
- Estilos en el form:
  - Borde en rojo para los inputs (cuando son visitados y no son validos).
  - Mensaje con el error ocurrido.

## Está aprobado cuando...

- El formulario guarda el producto creado
- El formulario valida correctamente los valores de entrada
- Se ejecutan todas las validaciones