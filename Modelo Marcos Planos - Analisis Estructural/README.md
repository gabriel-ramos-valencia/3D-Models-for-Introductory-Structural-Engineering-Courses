# Curso Análisis Estructural: Marcos Planos

## Archivos Autodesk Fusion 360 (.f3d)

* En esta base archivos están los modelos de diseño propuestos para el curso análisis estructural.

* En la sección **“Modificar”**, **“cambiar parámetros”**, se pueden cambiar las siguientes dimensiones de los marcos planos:
    * Altura del Marco Plano.
    * Ancho Base.
    * Espesor Columna.

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

## Esquema del Modelo

<p align="center">
  <img src="https://github.com/user-attachments/assets/951a0c31-40b0-46d-ab2b-0c00a5fa0e96" alt="Diseño de Marco Plano" width="300"/>
</p>
<p align="center"><em>Figura 1: Diseño de Marco Plano.</em></p>

En la siguiente tabla se especifican las medidas de los modelos impresos:

<p align="center">Tabla 1: Dimensiones de los marcos planos.</p>

| Modelos  | $h_c$ [mm] | $b_v$ [mm] | $b_b$ [mm] | $h_v$ [mm] | $e_1$ [mm] | $e_2$ [mm] | D[mm] |
|:---------|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:-----:|
| Diseño 1 | 100        | 39.6       | 50         | 13.5       | 5.2        | 2.00       | 5.30  |
| Diseño 2 | 150        | 39.6       | 50         | 13.5       | 5.2        | 2.00       | 2.00       | 5.30  |
| Diseño 3 | 200        | 39.6       | 50         | 13.5       | 5.2        | 2.00       | 2.00       | 5.30  |

En caso de utilizar los parámetros del modelo propuesto de la Tabla 1, los tiempos de impresión y los materiales para su funcionamiento se exponen en la siguiente tabla:

<p align="center">Tabla 2: Características Marco Plano Ancho 5mm.</p>

| Cantidad | Componentes – Marco Plano Ancho 5mm | Descripción                    | Tiempo    | Masa [g] |
|:--------:|:-------------------------------------|:-------------------------------|:----------:|:----------:|
| 1        | Base Marco                           | 4h9min                         | 27         |
| 1        | Marco Plano - Altura 10cm            | 1h6min                         | 6          |
| 1        | Marco Plano - Altura 15cm            | 1h17min                        | 7          |
| 1        | Marco Plano - Altura 20cm            | 1h27min                        | 9          |
| 6        | Tornillos 3/16" x 1 ½"               | -                              | -          |
| 6        | Tuercas 3/16"                        | -                              | -          |
| 1        | Imán Neodimio Gancho                 | -                              | -          |
| 1        | Mosquetón Con Destorcedor Metálico   | -                              | -          |
| 1        | Prensa Sargento Carpintero De 150 Mm | -                              | -          |
