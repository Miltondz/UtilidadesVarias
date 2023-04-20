# Pasos simples para crear repositorio local en github #



###  Pasos ###

* Crea repositorio en github, 
* Copia la direccion del repositorio 
 
![alt text](https://imgsh.net/i/PoHoI8p.png) 

* Ubicate en la carpeta local 
* Si estas en windows explorer puedes escribir CMD en la barra de direccion del explorer 
![alt text](https://imgsh.net/i/hNVYsY1.png)
* Asegurate que estas en la carpeta correcta (dir)

### Initialize the local directory as a Git repository. ###
````
git init -b main
````

### Adds the files in the local repository and stages them for commit. To unstage a file, use 'git reset HEAD YOUR-FILE'.###
````
git add .
````

### Commits the tracked changes and prepares them to be pushed to a remote repository. ###
### To remove this commit and modify the file, use 'git reset --soft HEAD~1' and commit and add the file again. ###
````
git commit -m "First commit"
````

### Adding a local repository to GitHub using Git ###

### Sets the new remote ###
````
 git remote add origin <REMOTE_URL>
````
### Verifies the new remote URL ###
````
git remote -v
````
### Pushes the changes in your local repository up to the remote repository you specified as the origin ###
````
git push origin main
````

### Verifica en github ###



