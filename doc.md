### Inicializar git
git init

### Git status
git status

### Añadir nuevo origen remoto
git remote add <url_repository>

### Crear una nueva rama
git checkout -b <branch_name>

### Cambiar rama
git checkout <branch_name>

### Actualizar rama remota
git pull origin <branch_name>
NOTA: estar ubicado en la rama local en la que se quiera actualizar

### Añadir todos los cambios realizador 
git add .

### Añadir un commit
git commit -m <message>

### Subir cambios realizador a repositorio origen
git push origin <branch_name>

### Para saber en que rama estoy trabajando
git branch 

### Para saber las url de origin actual
git remote -v