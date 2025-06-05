# Curso Dinámica de Estructuras: Sistema de Marcos Planos

## Archivos Autodesk Fusion 360 (.f3d)

* En esta base archivos están los modelos de diseño propuestos para el curso Dinámica de Estructuras.

* En la sección **"Modificar"**, **"cambiar parámetros"**, se pueden cambiar las siguientes dimensiones de los marcos planos:
    * Altura del Marco Plano.
    * Ancho del Marco Plano.
    * Ancho de la Columna del Marco Plano.
    * Ancho del pasador.
    * Altura del pasador.
    * Largo del pasador.
    * Diámetro de los agujeros del pasador.

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

## Modelo Dinámica de Estructuras

En la siguiente figura se muestra el esquema del marco plano diseñado:

<p align="center">
  <img src="URL_DE_TU_IMAGEN_DE_ESQUEMA_MARCO_DINAMICA_AQUI.png" alt="Diseño del Marco Plano" width="300"/>
</p>
<p align="center"><em>Figura 1: Diseño del marco plano.</em></p>

En la siguiente tabla se especifican las medidas del modelo impreso:

<p align="center">Tabla 1: Dimensiones de los marcos planos</p>

| Modelos  | $h_c$ [mm] | $b_c$ [mm] | $b_v$ [mm] | $e_c$ [mm] | $e_b$ [mm] | D [mm] |
|:---------|:----------:|:----------:|:----------:|:----------:|:----------:|:------:|
| Diseño 1 | 100        | 5.20       | 39.6       | 50         | 2.00       | 2.00   | 5.30   |
| Diseño 2 | 150        | 5.20       | 39.6       | 50         | 2.00       | 2.00   | 5.30   |
| Diseño 3 | 200        | 5.20       | 39.6       | 50         | 2.00       | 2.00   | 5.30   |

Las características de las componentes del modelo general de la Figura 1, para un marco plano de columna de ancho de 5mm, se exponen en la siguiente tabla:

<p align="center">Tabla 2: Características Marco Plano Ancho 5mm</p>

| Cantidad | Componentes - Marco Plano Columna 5mm | Descripción                    | Tiempo     | Masa [g] |
|:--------:|:---------------------------------------|:-------------------------------|:-----------:|:----------:|
| 1        | Base Celular                           | 5h48min                        | 50          |
| 4        | Laterales                              | 2h20min                        | 15          |
| 1        | Base Marco Plano                       | 7h15min                        | 40          |
| 1        | Pasador                                | 2h35min                        | 21          |
| 1        | Marco Plano Altura 10 cm               | 1h46min                        | 10          |
| 1        | Marco Plano Altura 15 cm               | 2h2min                         | 12          |
| 1        | Marco Plano Altura 20 cm               | 2h19min                        | 13          |
| 18       | Tornillos 3/16" X 1 ½"                 | -                              | -           |
| 18       | Tuercas 3/16" X                        | -                              | -           |
| 9        | Tornillos 5/32" X 1 ½"                 | -                              | -           |
| 9        | Tuercas 5/32"                          | -                              | -           |
