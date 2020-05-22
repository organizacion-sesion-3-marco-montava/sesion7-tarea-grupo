# sesion7-tarea-grupo
Tarea 2

Utilitzant VirtualBox, prepara una xarxa interna a la que es conecten dos màquines:

- un servidor Lubuntu 18.04 actuant com a servidor web
- un client Linux/Windows a elecció teua per a actuar com a client del servidor de pàgines web

La xarxa interna té la següent adressa:   33.FilaColumna.0.0/16

L’ IP del servidor acaba en 1, es a dir: 33.FilaColumna.0.1/16
L’ IP del client és a elecció teua

Has d’instalar en la màquina servidora, un servidor web Apache 2, amb la següent configuració: 

- Una lloc web per a cada mòdul que estigues cursant en el cicle (Anglés, AO, XAL, SOM, FOL, …)

- Hauràs de deixar els documents HTML en una carpeta per a cada modul, que estaran en /var/www

- El contingut de la pàgina inicial (index.html) de cada módul serà, com a mínim (pots fer-la tan complicada com vullgues):

	“Benvingut a la pàgina web de Xarxes Locals, creada per Nom Alumne”

- Per a accedir a la pàgina web de cada mòdul, des del client connectat a la xarxa interna, posaràs al navegador: http://IP_del_servidor/XAL, per example:  http://33.13.0.1/XAL
