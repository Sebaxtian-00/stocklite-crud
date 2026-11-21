# Registro de prompts de IA — StockLite CRUD

Este archivo documenta prompts de referencia usados para organizar el desarrollo asistido por IA. En la exposición, muestra la conversación real de trabajo y explica qué instrucciones utilizaste. No afirmes que enviaste cada prompt por separado si adaptaste o combinaste las instrucciones.

## 1. Definición de requisitos
**Prompt:** Actúa como analista de requisitos de software. Necesito una aplicación web CRUD sencilla para gestionar un inventario. Define objetivo, campos de cada producto, operaciones CRUD y criterios de aceptación. El proyecto debe poder explicarse en una demostración de máximo diez minutos.

**Propósito:** definir alcance, datos y comportamiento esperado antes de programar.

## 2. Selección de tecnologías
**Prompt:** Propón una solución que se ejecute en el navegador sin instalar dependencias ni configurar un servidor de base de datos. Usa HTML5, CSS3 y JavaScript puro, con LocalStorage. Explica las limitaciones de esta arquitectura.

**Propósito:** elegir tecnologías simples y reconocer que LocalStorage no permite compartir información entre distintos computadores.

## 3. Diseño de interfaz
**Prompt:** Diseña una interfaz moderna y clara en español para un gestor de inventario llamado StockLite. Incluye resumen de indicadores, tabla de productos, búsqueda, filtro por categoría y formulario para agregar o editar.

**Propósito:** ordenar la información y hacer visibles las acciones del usuario.

## 4. Implementación CRUD
**Prompt:** Implementa crear, consultar, actualizar y eliminar productos en JavaScript. Guarda los registros en LocalStorage, genera códigos consecutivos y actualiza los indicadores después de cada operación.

**Propósito:** construir la lógica central de la aplicación.

## 5. Validaciones y manejo de datos
**Prompt:** Revisa el formulario. Valida nombre de mínimo dos caracteres, categoría permitida, cantidad entera no negativa y precio numérico no negativo. Muestra errores claros y evita insertar el texto del usuario como HTML.

**Propósito:** reducir errores de captura y mejorar la seguridad de la interfaz.

## 6. Búsqueda y filtros
**Prompt:** Agrega búsqueda por nombre o código y filtro por categoría. Actualiza la tabla sin recargar la página y muestra un mensaje cuando no existan coincidencias.

**Propósito:** mejorar la consulta del inventario.

## 7. Revisión y refactorización
**Prompt:** Actúa como revisor de código. Busca errores en validaciones, LocalStorage, edición, eliminación y actualización de totales. Propón mejoras manteniendo la solución sencilla y sin frameworks.

**Propósito:** revisar el resultado y probarlo antes de darlo por terminado.

## 8. Documentación y video
**Prompt:** Prepara un README con descripción, tecnologías, instrucciones para ejecutar, estructura del proyecto, limitaciones y lista de prompts. También crea un guion de máximo diez minutos que explique el proceso y demuestre las cuatro operaciones CRUD.

**Propósito:** organizar la entrega y la exposición.

## Reflexión
La IA sirve como apoyo para analizar, proponer y acelerar tareas, pero sus respuestas deben comprobarse. El estudiante conserva la responsabilidad de ejecutar el programa, revisar el comportamiento, comprender el código y explicar sus limitaciones.
