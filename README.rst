admin-cfdi
==========

:Autores:
    Ver archivo contributors.txt

:Fecha:
    07/12/2015

:Ultima Versión:
    0.3.0


Descripción
-----------
Administrador de CFDIs / Proyecto de colaboración con PythonCabal_

Pequeño sistema para administrar CFDIs; facturas electrónicas de México. Entre sus funcionalidades están:

* Descarga facturas del SAT, tanto emitidas como recibidas.
* Descarga facturas de correos electrónicos.
* Organiza las facturas en carpetas y las puede renombrar.
* Valida las facturas en el SAT y valida los sellos.
* Generar los PDF de las facturas.
* Reportea directamente de las facturas.


Requerimientos
--------------
* Python 3.2+
* Tk si usas Linux. Si usas Windows, ya lo integra Python.
* Firefox para la automatización de la descarga del SAT.
* Selenium para la automatización de la descarga del SAT.
* PyGubu para la interfaz gráfica.
* LibreOffice si usas la plantilla ODS.
* Extensiones win32 para Python si usas Windows.

Instalación
-----------
Si tienes instalado correctamente Python 3.2+, puedes instalar con Pip.

GNU & LInux
###########

::

    sudo python setup.py install
    admin-cfdi


Linux Mint
__________

::

    sudo apt-get install python3-pip python3-tk
    sudo python setup.py install
    admin-cfdi


Windows
#######

Si usas Windows, asegúrate de abrir el script con el ejecutable pythonw.exe localizado en la carpeta de instalación de Python.

::

    python setup.py install


Ligas
-----
Mauricio Baeza
    https://github.com/mauriciobaeza

PythonCabal
    http://wiki.cabal.mx/wiki/PythonCabal


.. Links
.. _Mauricio Baeza: https://github.com/mauriciobaeza
.. _PythonCabal: http://wiki.cabal.mx/wiki/PythonCabal
