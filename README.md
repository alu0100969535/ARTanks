## Gif de ejecución:

![](img/ARRecording.gif)


## Funcionamiento

Se ha modificado el escenario de tal manera que posicionamos el ARSession y ARSessionOrigin en la raiz de la escena.

Eliminamos la cámara por defecto y añadimos una ARCamera

Por úlimo hacemos un prefab con el AR Default Plane y se lo asignamos a un componente de ARPlaneManager que debe estar en el mismo gameObject del ARSessionOrigin.