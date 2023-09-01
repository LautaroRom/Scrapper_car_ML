# Scrapper_cars_ML
Scrapper construido mediante Python para extraer información sobre automoviles publicados en Mercado Libre. Esta información corresponde a la marca, modelo, año de fabricación y kilometraje.

Al ejecutar el codigo en primera instancia importara las librerias de Selenium y otras necesarias para su funcionamiento. Luego se solicitara que se indique la marca, el modelo y el periodo de años de fabricación deseados para que despues se proceda a armar la URL de Mercado Libre correspondiente a los datos indicados. Despues se ejecutara el Driver necesario para la interaccion con el codigo Javascript de la web. En este punto es necesario remarcar que se debe instalar el Driver correspondiente al navegador que se tiene instalado. Asi, posteriormente, se ejecutara la funcion que realizara el scrapping, guardando los datos en la variable info_autos y cuya información se exportara en un archivo .csv.


