# Curso Mecánica de Materiales: Vigas en Voladizo

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

En la siguiente figura se muestra la Viga de Perfil Ángulo:

<p align="center">
  <img src="https://github.com/user-attachments/assets/fb103aaf-1990-4d0b-84c0-247dc1abbeea" alt="Diseño de la viga de perfil ángulo" width="600"/>
</p>
<p align="center"><em>Figura 1: Diseño de la viga de perfil ángulo.</em></p>

En la siguiente tabla se especifican las medidas del modelo impreso:

<p align="center">Tabla 1: Características de la viga de perfil ángulo.</p>

| Modelos  | $h_a$ [mm] | espesor [mm] | L [mm] | Ixx [mm4] | Iyy [mm4] |
|:---------|:----------:|:------------:|:------:|:---------:|:---------:|
| Diseño 1 | 15         | 1            | 150    | 1017      | 257       |

En la siguiente figura se muestra la Viga de Perfil doble T:

<p align="center">
  <img src="https://github.com/user-attachments/assets/ada70ba2-2052-4ac8-bf83-29cd8108caef" alt="Diseño de la viga de perfil doble T" width="600"/>
</p>
<p align="center"><em>Figura 2: Diseño de la viga de perfil doble T.</em></p>

En la siguiente tabla se detallan las medidas del modelo impreso:

<p align="center">Tabla 2: Características de la viga de perfil doble T.</p>

| Modelos  | $h_a$ [mm] | b [mm] | L [mm] | Ixx [mm4] | Iyy [mm4] |
|:---------|:----------:|:------:|:------:|:---------:|:---------:|
| Diseño 1 | 13         | 10     | 150    | 1165      | 168       |

En la siguiente figura se muestra la Viga de Perfil Canal:

<p align="center">
  <img src="https://github.com/user-attachments/assets/c8737b41-ecc0-4e6d-a9ab-bbfa36822095" alt="Diseño de la viga de perfil canal" width="600"/>
</p>
<p align="center"><em>Figura 3: Diseño de la viga de perfil canal.</em></p>

En la siguiente tabla se detallan las medidas del modelo impreso:

<p align="center">Tabla 3: Características de la viga de perfil canal.</p>

| Modelos  | $h_a$ [mm] | b [mm] | L [mm] | Ixx [mm4] | Iyy [mm4] |
|:---------|:----------:|:------:|:------:|:---------:|:---------:|
| 15       | 15         | 5      | 150    | 374       | 45        |
| Perfil   | 15         | 10     | 150    | 1165      | 327       |
| Canal    | 15         | 15     | 150    | 1656      | 1008      |
|          | 15         | 20     | 150    | 2146      | 2220      |

Los tiempos de impresión y las componentes del modelo general para las vigas en voladizo están detalladas en la siguiente tabla:

<p align="center">Tabla 4: Componentes de las vigas en voladizo.</p>

| Cantidad | Componentes         | Descripción | Tiempo  | Masa [g] |
|:--------:|:--------------------|:------------|:--------:|:----------:|
| 1        | Base eje            |             | 3h1m    | 21         |
| 1        | Perfil Ángulo Rotado |             | 4h16min | 31         |
| 1        | Perfil Doble T      |             | 4h32min | 35         |
| 1        | Perfil Canal Ala 5mm |             | 3h41min | 28         |
| 1        | Perfil Canal Ala 10mm|             | 4h15min | 33         |
| 1        | Perfil Canal Ala 15mm|             | 4h39min | 37         |
| 1        | Perfil Canal Ala 20mm|             | 5h14min | 42         |
