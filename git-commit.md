## git commit
Confirma los archivos preparados
`git commit -m <"mensaje">`
Los archivos preparados pasan a ser parte del historial de cambios.
### git commit -a -m
Salta el área de preparación.
Git prepara automáticamente todos los archivos rastreados antes de confirmarlos.

## git commit --amend
Rehace la confirmación

Este comando utiliza el área de preparación para la confirmación.
Al final terminarás con una sola confirmación - la segunda confirmación reemplaza el resultado de la primera.

Si no hemos hecho cambios desde la última confirmación entonces la instantánea lucirá exactamente igual u lo único que cambiaremos será el mensaje del commit.
