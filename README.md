# masteruah

git clone https://github.com/maxzapata/masteruah

git add --a

git commit -m "commit inicial"

git push origin main

mkdir privada

vi privado.txt

vi .gitignore

vi 1.txt

git add --a

git commit -m "Añadir .gitignore y 1.txt"

git tag v0.1

git push origin tag v0.1

git remote add sshuah git@github.com:maxzapata/masteruah.git

NOMBRE				GITHUB

Dario De La Hoz			https://github.com/dariohoz

Eneko Lakasta			https://github.com/enekid

Joseph Reyes			https://github.com/jossjack

LINK del gist 
https://gist.github.com/maxzapata/8498133ceca89c2e7025f69812b86c07

git checkout -b v0.2

vi 2.txt

git add --a

git commit -m "Subida fichero 2.txt"

git push sshuah v0.2

git checkout main

git merge v0.2

#Se añade Hola al fichero 1.txt en la rama main
#Se añade Adios al fichero 1.txt en la rama v0.2

git merge v0.2

git branch --merged

git branch --no-merged

#Se arregla el fichero1.txt

git add --a

git commit -m "fix del fichero 1.txt"

