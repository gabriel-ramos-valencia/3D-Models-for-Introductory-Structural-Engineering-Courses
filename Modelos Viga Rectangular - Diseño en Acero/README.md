# Curso Diseño en acero: Vigas en Voladizo

## Archivos Autodesk Fusion 360 (.f3d)

* En esta base archivos están los modelos de diseño propuestos para el curso análisis estructural.

* Las características del perfil de las vigas no se pueden modificar debido a la singularidad de los modelos diseñados.

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

# Dimensiones esquema de la Viga en Voladizo

En la siguiente figura se muestra el esquema de la viga en voladizo de perfil rectangular:

<p align="center">
  <img src="https://github.com/user-attachments/assets/f13ecbee-9ffe-4ec3-8d0a-711d39641188" alt="Diseño de la viga de perfil rectangular con perforación" width="600"/>
</p>
<p align="center"><em>Figura 1: Diseño de la viga de perfil rectangular con perforación.</em></p>

En la siguiente tabla se especifican las medidas de la viga:

<p align="center">Tabla 1: Características de la viga de perfil rectangular.</p>

| Modelos  | $h_a$ [mm] | b [mm] | L [mm] | D [mm] |
|:---------|:----------:|:------:|:------:|:------:|
| Diseño 1 | 15         | 1      | 150    | 6      |

Las características de las componentes del modelo general para la viga en voladizo de perfil rectangular, se exponen en la siguiente tabla:

<p align="center">Tabla 2: Componentes de la viga de perfil rectangular.</p>

| Cantidad | Componentes         | Descripción | Tiempo  | Masa [g] |
|:--------:|:--------------------|:------------|:--------:|:----------:|
| 1        | Base Eje            |             | 3h1m    | 21         |
| 1        | Perfil Rectangular  |             | 2h14min | 20         |
| 1        | Imán Neodimio Gancho|             | -       | -          |
