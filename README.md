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