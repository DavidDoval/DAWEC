Git cheatsheet:
----------------

Iniciar proyecto
`git init`
Inicia el proyecto en el directorio local

Editar el .git/config y poner la ruta al repositorio
```
[core]
	repositoryformatversion = 0
	filemode = false
	bare = false
	logallrefupdates = true
	symlinks = false
	ignorecase = true
[remote "origin"]
	url = https://github.com/DavidDoval/DAWEC.git
	fetch = +refs/heads/*:refs/remotes/origin/*
[branch "main"]
	remote = origin
	merge = refs/heads/main
```

Ver estado cambios en directorio local:
`git status`

Añadir ficheros al repositorio local:
`git add .`

hacer commit
`git commit -m "mensaje asociado al commit"`

subir cambios
`git push`