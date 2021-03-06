****
Repositorios: externos
****

.. Repositorios: externos:

JMA, mjo_repo y SERVIMET almacenan figuras descargadas mediante un script simple programado para ejecutarse una vez al día (3 veces en el caso de SERVIMET). ::

  hw_dynamic
  ├── JMA
      └── jma_repo.csh
  ├── mjo_repo
      ├── bom
          ├── RMM_40_days
          └── RMM_90_days
      ├── ncpe
      └── mjo_repo.csh
  └── SERVIMET
      ├── cartas_color
      └── servimet.csh
      
.. warning::

  En estos scripts hay que modificar las siguientes líneas para adecuarlas a la configuración propia..

1. jma_repo.csh

.. code:: bash
  
  cd /home/matlab/hw_dynamic/JMA
  
2. mjo_repo.csh

.. code:: bash

  cd /home/matlab/hw_dynamic/mjo_repo
  
3. servimet.csh

.. code:: bash

  cd /home/matlab/hw_dynamic/SERVIMET

JMA
====

.. figure:: images/main3.gif
   :width: 75%
   :align: center
   :alt: GitHub template for the tutorial

   OLR y función corriente de 200 hPa y el flujo de actividad de onda (anomalía) emitido por la Agencia Meteorológica de Japón (JMA)

mjo_repo
====

.. figure:: images/main4.gif
   :width: 75%
   :align: center
   :alt: GitHub template for the tutorial

   Pronóstico basado en MJO GFS emitido por el Centro de Predicción Climática de la NOAA de EE. UU

SERVIMET
====

.. figure:: images/main5.jpeg
   :width: 75%
   :align: center
   :alt: GitHub template for the tutorial

   Cartas sinóptica emitida por el Servicio Meteorológico de la Armada de Chile (SERVIMET)
