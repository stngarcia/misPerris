Preparación del ambiente para misPerrisApp:
a. Opcional, actualizar conda
conda update conda --yes

b. crear el ambiente virtual.
conda create --name misPerrisApp python=3.7 --yes

c. activar el ambiente virtual.
conda activate misPerrisApp

d. Cargar las librerías necesarias, se debe estar dentro del ambiente virtual.
pip install -r requirements.txt

e. desactivar el ambiente virtual.
conda deactivate

f. Eliminar el ambiente virtual, primero debe desactivar el ambiente virtual antes de eliminarlo.
conda remove --yes --name misPerrisApp --all
