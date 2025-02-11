.. _top_125_14:

##############
STEMlab 125-14
##############

*******
Pinout
*******

.. figure:: img/Red_Pitaya_pinout.jpg
    :alt: Red Pitaya pinout
    :width: 700

************************
Technical specifications
************************

.. table::
    :widths: 10 18

    +------------------------------------+------------------------------------+
    | **Basic**                                                               |
    +====================================+====================================+
    | Processor                          | DUAL CORE ARM CORTEX A9            |
    +------------------------------------+------------------------------------+
    | FPGA                               | FPGA Xilinx Zynq 7010 SOC          |
    +------------------------------------+------------------------------------+
    | RAM                                | 512 MB (4 Gb)                      |
    +------------------------------------+------------------------------------+
    | System memory                      | Micro SD up to 32 GB               |
    +------------------------------------+------------------------------------+
    | Console connection                 | Micro USB                          |
    +------------------------------------+------------------------------------+
    | Power connector                    | Micro USB                          |
    |                                    |                                    |
    +------------------------------------+------------------------------------+
    | Power consumption                  | 5 V, 2 A max                       |
    +------------------------------------+------------------------------------+

|

.. table::
    :widths: 10 18


    +------------------------------------+------------------------------------+
    | **Connectivity**                                                        |
    +====================================+====================================+
    | Ethernet                           | 1 Gbit                             |
    +------------------------------------+------------------------------------+
    | USB                                | USB 2.0                            |
    +------------------------------------+------------------------------------+
    | Wi-Fi                              | requires Wi-Fi dongle              |
    +------------------------------------+------------------------------------+

|

.. table::
    :widths: 10 18

    +------------------------------------+------------------------------------+
    | **RF inputs**                                                           |
    +====================================+====================================+
    | RF input channels                  | 2                                  |
    +------------------------------------+------------------------------------+
    | Sample rate                        | 125 MS/s                           |
    +------------------------------------+------------------------------------+
    | ADC resolution                     | 14 bit                             |
    +------------------------------------+------------------------------------+
    | Input impedance                    | 1 MΩ / 10 pF                       |
    +------------------------------------+------------------------------------+
    | Full scale voltage range           | ±1 V (LV) and ±20 V (HV)           |
    +------------------------------------+------------------------------------+
    | Input coupling                     | DC                                 |
    +------------------------------------+------------------------------------+
    | Absolute max. Input voltage range  | 30 V                               |
    |                                    |                                    |
    +------------------------------------+------------------------------------+
    | Input ESD protection               | Yes                                |
    +------------------------------------+------------------------------------+
    | Overload protection                | Protection diodes                  |
    +------------------------------------+------------------------------------+
    | Bandwidth                          | DC - 60 MHz                        |
    +------------------------------------+------------------------------------+

|

.. table::
    :widths: 10 18

    +------------------------------------+------------------------------------+
    | **RF outputs**                                                          |
    +====================================+====================================+
    | RF output channels                 | 2                                  |
    +------------------------------------+------------------------------------+
    | Sample rate                        | 125 MS/s                           |
    +------------------------------------+------------------------------------+
    | DAC resolution                     | 14 bit                             |
    +------------------------------------+------------------------------------+
    | Load impedance                     | 50 Ω                               |
    +------------------------------------+------------------------------------+
    | Voltage range                      | ±1 V                               |
    |                                    |                                    |
    +------------------------------------+------------------------------------+
    | Short circuit protection           | Yes                                |
    |                                    |                                    |
    +------------------------------------+------------------------------------+
    | Connector type                     | SMA                                |
    +------------------------------------+------------------------------------+
    | Output slew rate                   | 2 V / 10 ns                        |
    +------------------------------------+------------------------------------+
    | Bandwidth                          | DC - 50 MHz                        |
    +------------------------------------+------------------------------------+

|

.. table::
    :widths: 10 18

    +------------------------------------+------------------------------------+
    | **Extension connector**                                                 | 
    +====================================+====================================+
    | Digital IOs                        | 16                                 |
    +------------------------------------+------------------------------------+
    | Analog inputs                      | 4                                  |
    +------------------------------------+------------------------------------+
    | Analog inputs voltage range        | 0-3.5 V                            |
    +------------------------------------+------------------------------------+
    | Sample rate                        | 100 kS/s                           |
    +------------------------------------+------------------------------------+
    | Resolution                         | 12 bit                             |
    +------------------------------------+------------------------------------+
    | Analog outputs                     | 4                                  |
    +------------------------------------+------------------------------------+
    | Analog outputs voltage range       | 0-1.8 V                            |
    +------------------------------------+------------------------------------+
    | Communication interfaces           | I2C, SPI, UART, CAN                |
    +------------------------------------+------------------------------------+
    | Available voltages                 | +5 V, +3.3 V, -4 V                 |
    +------------------------------------+------------------------------------+
    | External ADC clock                 |  Yes                               |
    +------------------------------------+------------------------------------+

|

.. table::
    :widths: 10 18

    +------------------------------------+------------------------------------+
    | **Synchronisation**                                                     |
    +====================================+====================================+
    | Trigger input                      | Through extension connector        |
    +------------------------------------+------------------------------------+
    | Daisy chain connection             | Over SATA connection               |
    |                                    | (up to 500 Mbps)                   |
    +------------------------------------+------------------------------------+
    | Ref. clock input                   | N/A                                |
    +------------------------------------+------------------------------------+

.. note::
    
    For more information, please refer to the :ref:`Product comparison table <rp-board-comp>`.

.. _schematics_125_14:

**********
Schematics
**********

* `Red_Pitaya_Schematics_v1.0.1.pdf <https://downloads.redpitaya.com/doc//Red_Pitaya_Schematics_v1.0.1.pdf>`_

.. note::

    FULL HW schematics for the Red Pitaya board are not available. Red Pitaya has open-source code but not open hardware schematics. Nonetheless, DEVELOPMENT schematics are available. This schematic will give you information about HW configuration, FPGA pin connections, and similar.

****************************************
Mechanical Specifications and 3D Models
****************************************

* `Red_Pitaya_3Dmodel_v1.0.zip <https://downloads.redpitaya.com/doc/Red_Pitaya_3Dmodel_v1.0.zip>`_


***********
Components
***********

* `ADC <https://www.analog.com/en/products/ltc2145-14.html>`_
* `DAC <https://www.analog.com/en/products/AD9767.html>`_
* `FPGA (Zynq 7010) <https://docs.xilinx.com/v/u/en-US/ds190-Zynq-7000-Overview>`_
* `DC-DC converter <https://www.analog.com/en/products/LTC3615.html>`_
* `Oscillator <https://eu.mouser.com/datasheet/2/417/bf-8746.pdf>`_
* `SRAM-DDR3 <https://www.digikey.com/en/products/detail/micron-technology-inc/MT41J256M16HA-125-E/4315785>`_
* `QSPI <https://www.infineon.com/cms/en/product/memories/nor-flash/standard-spi-nor-flash/quad-spi-flash/s25fl128sagnfi001/>`_ (NOT POPULATED - see :ref:`QSPI section <qspi_chip>` for more information)

.. note::

    STEMlab 125-14 Low Noise and STEMlab 125-14 4-Input feature Zynq 7020 instead of Zynq 7010.


**************
Fast analog IO
**************

.. toctree::
   :maxdepth: 6

   fastIO

*********
Extension
*********

.. toctree::
   :maxdepth: 6

   extent


.. _external_125_14:

******************
External ADC clock
******************

The ADC clock can be provided by:

    - On board 125 MHz XO (default)
    - From an external source/through extension connector :ref:`E2 <E2>` (R25, R26 should be moved to location R23, R24)
    - Directly from the FPGA (R25, R26 should be relocated to R27, R28) 

.. figure:: img/schematics/External_clk.png
    :alt: Schematic
    :align: center

    Schematic
    

.. warning::

    We do not advise altering the board because users have reported problems after doing so. Every board made has undergone rigorous testing, which cannot be claimed for modified boards. Any non-Red Pitaya hardware modification will void the warranty, and we cannot guarantee support for modified boards.


.. figure:: img/schematics/External_clock_top.png
    :alt: Top side schematic
    :align: center

    Top side schematic


.. figure:: img/schematics/External_clock_bottom.png
    :alt: Bottom side schematic
    :align: center

    Bottom side schematic

.. figure:: img/schematics/External_clock_bottom_photo.png
    :alt: Bottom side photo
    :align: center
    :width:  400px

    Bottom side photo

.. figure:: img/schematics/External_clock_resistors.jpeg
    :alt: Bottom side all
    :align: center

    Bottom side

.. _qspi_chip:

*********
QSPI 
*********

The QSPI chip is by default not populated on Red Pitaya boards. Please write to support@redpitaya.com or info@redpitaya.com for information regarding board modifications.

.. warning::

    Any non-Red Pitaya hardware modification will void the warranty, and we cannot guarantee support for modified boards.


************
Certificates
************

Besides the functional testing, Red Pitaya passed the safety and electromagnetic compatibility (EMC) tests at an
external |testing and certification institute|.

.. |testing and certification institute| raw:: html

    <a href="http://www.siq.si/?L=3" target="_blank">testing and certification institute</a>

.. toctree::
   :maxdepth: 6

   cets


***************
Cooling options
***************

For additional cooling, we recommend a 30 mm or 25 mm fan. You can use the board's power connector to power the fan, but please note that it supplies only 5 V. The power connector is located between the micro-SD socket and the host USB connector.

.. figure:: img/cooling/cooling-powerPin.jpg
    :width: 50%
    :align: center

    Red Pitaya power connector. Image via `blog <https://rroeng.blogspot.com/2014/03/keep-your-red-pitaya-cool.html>`_ (with permission from Jacek Radzikowski).


.. note::

    The power connector is a standard 2-pin 0.1" connector.
    Supplies only 5 V.


.. toctree::
   :maxdepth: 6

   cooling
