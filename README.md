# webcam_capture
Per tal de poder treballar amb aquest repositori s'han de seguir els següents passos: 
### Instal·lació del software necessari a través del terminal
* Cmake:
> sudo apt-get install cmake
* Llibraries OpenCV:
> sudo apt-get install libopencv-dev
### Ús del GitHub
Si volem utilitzar un repositori que es troba al GitHub, hi hem de tenir un compte. En cas que no el tinguem, el creem. Ens dirigim a l'enllaç a on es troba:

https://github.com/beta-robots/webcam_capture.git

Seguidament anem a l'opció "Fork", que es troba a dalt a la dreta. D'aquesta manera, l'afegim a nostre repositori del GitHub.

Un cop fet aixó, clicquem a clonar i copiem l'enllaç. Hauria de ser una cosa així:
https://github.com/my_github_name/webcam_capture.git

### Compliació codi
Per fer el següent pas hem de tornar a utilitzar el nostre terminal, i seguim els següent passos:
> git clone https://github.com/my_github_name/webcam_capture.git
* Entrem a dins la carpeta creada mitjançant la comanda
> cd webcam_capture
* I executem amb el Cmake per tal de crear l'executable:
> cmake .

> make
* Un cop tenim l'executable, podem fer doble clic dins de la carpeta a on es troba, o executant la següent comanda a la terminal:
> ./webcam_capture
