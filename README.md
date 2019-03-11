# karma

Las razones de estas convenciones:
Generación automática del registro de cambios.

Formato del mensaje de confirmación:

`<type>(<scope>): <subject>`

`<body>`

`<footer>`

Ejemplo de mensaje de confirmación:
docs: se hace cambio en el documento01

por mal redacción se hace cambio en el documento, en la pag 01

example
Asunto del mensaje (primera línea)
La primera línea no puede tener más de 70 caracteres, la segunda línea siempre está en blanco y las otras líneas deben ajustarse a 80 caracteres. El tipo y el alcance siempre deben estar en minúsculas, como se muestra a continuación.
<type>Valores permitidos :
* feat (nueva característica para el usuario)
*	fix (corrección de errores para el usuario)
*	docs (cambios a la documentación)
* style (formateo, puntos y comas que faltan, etc.)
*	refactor (cambio de nombre de una variable)
*	test (agregando pruebas faltantes, no hay cambio en el código de producción)
*	chore (actualizando tareas, etc; sin cambio de código de producción)
<scope>Valores de ejemplo :

	
El <scope>puede estar vacía (por ejemplo, si el cambio es un mundial o difíciles de asignar a un solo componente), en cuyo caso se omiten los paréntesis. En proyectos más pequeños, como los complementos de Karma, <scope>está vacío.

## *Versionado Semántico 2.0.0-rc.2*

Explicación de la numeración de las versiones
Los identificadores de cada versión de Joomla siguen una convención numérica de tres niveles, en la que los niveles se definen por la importancia de los cambios en el software.

`[major].[minor].[patch]`
Estos tres niveles se definen como:

* Un incremento en el identificador de versión major (mayor) indica una ruptura de la compatibilidad hacia atrás.
* Un incremento en el identificador de versión minor (menor) indica la adición de nuevas características o un cambio significativo en características existentes.
* Un incremento en el identificador de versión patch (parche) indica que se han corregido fallos.

## Ejemplos

Estás usando la versión 3.3.6 de Joomla. Esto significa que tu versión es versión mayor 3, versión menor 3, y versión parche 6. Si se lanza un parche para la 3.3.6, tu versión de Joomla se incrementaría a la 3.3.7. Si se lanza una nueva versión menor para la versión mayor 3, tu nueva versión de Joomla sería la 3.4.0. Esta página siempre mostrará la versión actual estable soportada de Joomla, incluyendo las versiones menor y de parche, en la esquina superior derecha.
