### inicializar git
git init

### git status
git status

### añadir nuevo origen remoto
git remote add <url_repository>

### crear una nueva rama
git checkout -b <branch_name>

### cambiar rama
git checkout <branch_name>

### actualizar rama remota
git pull origin <branch_name>
NOTA: estar ubicado en la rama local en la que se quiera actualizar

### añadir todos los cambios realizador 
git add .

### añadir un commit
git commit -m <message>

### subir cambios realizador a repositorio origen
git push origin <branch_name>

### para saber en que rama estoy trabajando
git branch 

### para saber las url de origin actual
git remote -v