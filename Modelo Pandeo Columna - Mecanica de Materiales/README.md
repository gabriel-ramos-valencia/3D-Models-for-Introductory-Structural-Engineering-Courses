# Curso Mecánica de Materiales: Sistema Pandeo Columnas

## Archivos Autodesk Fusion 360 (.f3d)

* En esta base archivos están los modelos de diseño propuestos para el curso análisis estructural.

* En la sección **“Modificar”**, **“cambiar parámetros”**, se pueden cambiar las siguientes dimensiones de la estructura y las columnas:
    * Ancho de la estructura.
    * Altura de la columna.
    * Espesor de la columna.
    * Ancho de la columna.

* Finalizado el proceso de diseño, se debe exportar el modelo como un archivo STL.

## Archivos STL (.stl)

* Son un formato de archivo estándar para la impresión 3D y pueden ser abiertos y utilizados en la mayoría de los programas de impresión 3D.

* Para el caso de la investigación se utilizó el programa **Ultimaker Cura** para definir los parámetros de impresión de los modelos.

## Archivos Ultimaker Cura (.3mf)

* Estos archivos a partir de los modelos STL y la configuración de impresión seleccionada, que para el caso de la investigación contienen la configuración preestablecida para la impresora **Ender Creality Pro-3**, optimizada para filamento **PLA** de la marca **Hellbot**.

* Se especifican los parámetros:
    * Tipo de filamento.
    * Patrones de relleno.
    * Uso de soportes.

* Puedes ajustarse a las especificaciones del usuario, dependiendo del tipo de impresora y/o experimentación para el análisis del comportamiento ante diferentes parámetros.

* Al terminar el proceso de ajustes en la impresión del modelo, se codifica en el archivo de impresión.

## Códigos Gcode (.gcode)

* Los archivos Gcode son las instrucciones específicas que la impresora 3D utiliza para crear los modelos.

* Generado el Gcode, no son modificables.

## Dimensiones Modelo Mecánica de Materiales

En la siguiente figura se muestra el esquema de la columna diseñada:

<p align="center">
  <img src="URL_DE_TU_IMAGEN_DE_ESQUEMA_COLUMNA_AQUI.png" alt="Diseño del Marco Plano para Mecánica de Materiales" width="250"/>
</p>
<p align="center"><em>Figura 1: Diseño del marco plano para Mecánica de Materiales.</em></p>

A continuación, se especifican las medidas de los modelos impresos:

<p align="center">Tabla 1: Características de la columna.</p>

| Modelos  | h [mm] | b [mm] | $e_b$ [mm] | $e_c$ [mm] | D [mm] |
|:---------|:------:|:------:|:----------:|:----------:|:------:|
| Diseño 1 | 190    | 38.5   | 2.00       | 1.00       | 5.30   |

Las características de las componentes del modelo general de la Figura 1 los tiempos de impresión e instrumentos para una columna de ancho de 1mm, se exponen en la siguiente tabla:

<p align="center">Tabla 2: Componentes del modelo del pandeo de columna.</p>

| Cantidad | Componentes Estructura Pandeo Columna | Descripción | Tiempo  | Masa [g] |
|:--------:|:---------------------------------------|:------------|:--------:|:----------:|
| 1        | Base Inferior                          | 6h53min     | 51       |
| 1        | Base Superior                          | 5h35min     | 40       |
| 1        | Columna                                | 59 min      | 6        |
| 1        | Soporte                                | 2h25min     | 16       |
| 1        | Recipiente                             | 3h11min     | 27       |
| 1        | Carril                                 | 6h53min     | 51       |
| 9        | Tornillos 3/16" x 1 ½"                 | -           | -        |
| 9        | Tuercas 3/16"                          | -           | -        |
| 2        | Tornillos 5/32" x 1 ½"                 | -           | -        |
