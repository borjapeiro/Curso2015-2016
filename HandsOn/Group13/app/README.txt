Para el desarrollo de esta aplicaci�n se han convertido a formato JSON los archivos CSV extra�dos previamente de Google Refine.

Una vez extra�dos, debido a que en ningunos de los archivos aparec�an las coordenadas de los lugares ni las de las farmacias se decidi� utilizar una API de Google Maps que permite obtener las coordenadas a partir de una direcci�n.

Debido a que la versi�n gratuita de esta API s�lo permite un n�mero determinado de consultas diarias en la aplicaci�n solo se muestran una parte de los resultados, para evitar as� problemas de funcionamiento.

Debido a que se cargan archivos .json, es necesario crear un servidor. Nosotros utilizamos la herramienta SimpleHTTPServer de python.