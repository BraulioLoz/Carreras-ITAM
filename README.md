# Comandos para crear el repositorio

## PRIMERA VERSIÓN
git clone git@github.com:BraulioLoz/Carreras-ITAM.git .

git status

git checkout -b feat/scaffold

ni index.html

mkdir assets 

mkdir .\assets\img, .\assets\css, .\assets\js

ni .\assets\css\custom.css, .\assets\js\main.js

git add .\assets\img\, .\assets\css\custom.css, .\index.html

git commit -m "feat: Esqueleto html de la página, navbar personalizada v0, cards de carreras v0"

git push origin feat/scaffold

## SEGUNDA VERSIÓN
git add .\README.md

git commit -m "Agrego v0 del README con los primeros comandos"

git push origin feat/scaffold

## TERCERA VERSIÓN
### Comandos para preparar main y hacer Pull Request desde feat/scaffold

#### 1. Ver commits de la rama de trabajo
git checkout feat/scaffold
git log --oneline --reverse

### (Se identifica el hash del primer commit, por ejemplo: 1b1b482)

#### 2. Crear la rama main apuntando al primer commit
git branch -f main 1b1b482
git checkout main

#### 3. Subir main al remoto
git push -f origin main

Hice el puill request y lo resolví por lo que no tengo el primer URL al pull request pero hago uno segundo.


## Pull request 
### Primero
Lo resolví :(

### Segundo
https://github.com/BraulioLoz/Carreras-ITAM/pull/2

### TerceroVi
