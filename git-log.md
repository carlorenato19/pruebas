### Git log
Muestra el historial de commits
`gi log --pretty=format:"%h - %an, %ar : %s"`
Muestra el historial con el formato que indicamos.

### Limitar la salida del historial
`git log -n`: Cambiamos la n por cualquier número entero, por ejemplo:
`git log -2`nos mostrará los últomos 2 commits.

`git log --after="2018-04-28 00:00:00"` Muestra los commits realizados antes de la fecha especificada.

`git log --before="2018-04-28 00:00:00"` Muestra los commits realizados después de la fecha especificada.

Las banderas del comando `git log` se pueden usar juntas según nos convenga, por ejemplo:
`git log --after="2018-04-28 00:00:00" --before="2018-04-27 10:00:00"`

`git log  --oneline `
Este comando nos muestra el historial en una sola línea por commit.
