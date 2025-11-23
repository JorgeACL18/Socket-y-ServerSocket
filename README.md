# Trabajo 25 PSP

En este trabajo tuvimos que crear un programa que, al proporcionarle una dirección IP o escribir "localhost", se conecte y nos ofrezca utilizar alguno de los puertos "famosos".

## Paso 1:
Primero de todo, hacemos el import del Socket, el Scanner y el IOException.

<img width="199" height="117" alt="Captura de pantalla 2025-11-23 173959" src="https://github.com/user-attachments/assets/b591a8f9-9c92-41b6-9c84-b7bfbf83efdb" />

Ahora, dentro de la clase principal, creamos la función Puertos que es un boolean que devuelve true o false si la conexión al puerto se realizó correctamente.

<img width="511" height="199" alt="Captura de pantalla 2025-11-23 174010" src="https://github.com/user-attachments/assets/1ebb819f-da36-4802-89e1-d1b9681b6578" />

## Paso 2:
Ya en el paso 2 es donde creamos nuestra función main:

<img width="922" height="1055" alt="Captura de pantalla 2025-11-23 174032" src="https://github.com/user-attachments/assets/1bf95f6b-bc4b-4d16-985f-37146bee8361" />

Creamos un bucle el cual repite la misma secuencia donde pide escribir una dirección IP o localhost para después escribir el puerto que queramos usar. El resultado sería este (en mi caso ninguno de los puertos me funcionó):

<img width="709" height="181" alt="Captura de pantalla 2025-11-23 174208" src="https://github.com/user-attachments/assets/a812a4e7-f471-4016-8463-7e88b159284b" />
<img width="709" height="181" alt="Captura de pantalla 2025-11-23 174231" src="https://github.com/user-attachments/assets/bd0e1ea7-fdaf-4614-ab51-f8a2bc4b2c01" />
<img width="709" height="181" alt="Captura de pantalla 2025-11-23 174249" src="https://github.com/user-attachments/assets/889a134a-dc31-4053-9a2d-9f32204ee8b2" />
<img width="709" height="181" alt="Captura de pantalla 2025-11-23 174337" src="https://github.com/user-attachments/assets/61584a9b-16c9-44f3-8a98-5bfedc6d3db8" />

## FIN
