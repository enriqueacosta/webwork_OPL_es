# Agregar un problema a una tarea (en blanco, o del OPL en inglés)

## Crear un problema en blanco
Si ya se ha creado una [tarea-- FALTA LINK](link), se puede crear un problema en banco de la siguiente manera:

*  Ir al *editor de tareas* en el menú.
*  Ingresar a la página de detalles de la tarea.
*  Al final de la página seleccionar `Agregar blank problem template(s) to end of homework set`
*  Guardar los cambios.

Esto va a crear un problema al final de la tarea (aparece como el último problema) con archivo `blankProblem.pg`. 

*  Seleccionar `Editar problema` (ícono de lápiz) o, otra forma, seleccionar `Ver problema` y en la página en la que ser carga el problema seleccionar `Edit3` justo debajo del recuadro gris que contiene el problema.

Esto carga el editor, pero va a aparecer in mensaje de alerta arriba a la derecha que dice algo como 
```
The file '[TMPL]/settest/blankProblem.pg' is a blank problem!
To edit this text you must use the 'NewVersion' action below to save it to another file.
```

Seguir estas instrucciones seleccionando `NewVersion` en la parte de abajo de la página y eligiendo el nombre del archivo que se le quiere dar, por ejemplo `MiPrimerProblema.pg`. Dejar la opción `Replace current problem: ...` seleccionada y presionar el botón `Ejecutar`.

Va a salir un mensaje verde arriba que dice algo como:
```
Saved to file '[TMPL]/settest/MiPrimerProblema.pg'
The source file for 'set test / problem 16 has been changed from '[TMPL]/settest/blankProblem.pg' to '[TMPL]/settest/MiPrimerProblema.pg'
```
Esto indica que se creó el problema correctamente.

## Editar un problema

Para ver vistas previas, seleciona "View-->Take action" abajo (view está seleccionado por defecto). 
*  Si quieres guardar tu trabajo, selecciona: "Update-->Take Action".

## Agregar un problema del OPL en inglés a una tarea sin editarlo.

*  Ir al *Explorador de problemas* en el menú.
*  Seleccionar `Subject`, `Chapter`, `Section` (en ese orden, cada selección habilita la lista siguiente).

Va a salir un mensaje como `There are 20 matching WeBWorK problems`. 

*  Presionar `view problems` para ver estos 20 problemas (esot puede tomar un tiempo, pues son cargados de una gran base de datos).

Esto va a cargar todos los problemas y cada uno tiene un botón `Agregar` para poder agregarlo a una tarea.

*  Seleccionar la tarea a la que se van a agregar los problemas en la parte superior de la página `Add problems to Target Set:`. También se puede crear una nueva tarea desde esta misma página con el botón y campo justo debajo.
*  Presionar `Agregar` con los problemas que se quieran agregar. Cada vez que se agreguen va a aparecer un mensaje verde en la parte superior derecha.

## Hacer ediciones a un problema agregado del OPL (volverlo propio)

*  Ir a la página de un problema particular que se haya agregado a alguna tarea.
*  Selecciona "Edit3" justo debajo de la caja azul del problema. Eso abre una nueva ventana con el editor. 
*  Arriba a la derecha vas a ver un mensaje como `The file '[TMPL]/Library/Michigan/Chap14Sec1/Q13.pg' is protected!` pues no puedes editar el problema del OPL. Debes hacer un copia propia así:
   -  Abajo, selecciona "new version"
   -  Elige la opción "Replace current problem: ..." (que está seleccionado por defecto)
   -  Click en "take action"
   -  Ahora te va a salir un mensaje verde arriba a la derecha que dice algo como: `Saved to file '[TMPL]/local/Library/Michigan/Chap14Sec1/Q13.pg'` ... eso quiere decir que ta tienes tu propia copia para editar. 

# Traducir un problema dentro de la plataforma de WeBWork

## Traducir un problema propio (por ejemplo, creado a partir de un `blankProblem.pg`):

## Traducir un problema del OPL en inglés
 
