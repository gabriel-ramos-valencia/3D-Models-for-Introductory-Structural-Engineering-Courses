## Estructura del Repositorio

El conjunto de carpetas de este repositorio corresponde a los cursos de ingeniería estructural y cada una contiene 4 tipos de archivos principales:

* **Archivos `.f3d`**: Contienen los modelos 3D para su réplica o edición del diseño inicial dentro del programa Autodesk Fusion 360.
* **Archivos `.3mf`**: Incluyen las características de impresión, como el material o configuraciones específicas de la impresora utilizada.
* **Archivos `.STL`**: Contienen la geometría del modelo 3D.
* **Archivos `.g-code`**: Contienen las instrucciones de impresión del modelo 3D.
* **Archivos `.PDF`**: Proporcionan información detallada respecto al modelo, el concepto que se busca representar y su aplicación.

Para los modelos impresos se utilizó la impresora **Creality Ender Pro-3** con filamento **PLA** de la marca **Hellbot**.

---

## Modelos 3D por Curso

### Modelo Análisis Estructural

El diseño está compuesto por dos componentes: la base y el marco plano. La base está diseñada para rotar el marco y facilitar la aplicación de cargas a la estructura. La segunda componente, el marco plano, son estructuras básicas compuestas por columnas y vigas unidas rígidamente. Permiten representar el concepto de rigidez estructural al visualizar el distinto comportamiento de los marcos planos ante la aplicación de cargas verticales.

Se diseñaron tres conjuntos de marcos planos de 5, 10 y 20 milímetros de ancho y alturas de 10, 15 y 20 centímetros.

<p align="center">
  <img src="https://github.com/user-attachments/assets/6ec36e3a-8a9a-4d78-8159-c9795a07464d" alt="Modelo Análisis Estructural" width="250"/>
</p>
<p align="center"><em>Figura: Registros fotográficos del Modelo de Análisis Estructural</em></p>

### Modelo Dinámica de Estructuras

El diseño está compuesto por tres marcos planos, un pasador y tres receptáculos. El pasador cumple dos funciones: fijar las bases de los marcos planos en la estructura y, a su vez, permitir la transmisión de las cargas dinámicas a la estructura. El receptáculo permite integrar un acelerómetro en el sistema para registrar la aceleración aplicada al modelo.

Este modelo permite visualizar el concepto de frecuencias naturales para los marcos planos ante cargas dinámicas. Se diseñaron tres marcos planos de 10 milímetros de ancho y alturas de 10, 15 y 20 centímetros.

<p align="center">
  <img src="https://github.com/user-attachments/assets/50e78ddd-97ef-4fd9-baf8-b4e9fa7e4e8a" alt="Modelo Dinámica de Estructuras" width="250"/>
</p>
<p align="center"><em>Figura: Registros fotográficos del Modelo de Dinámica de Estructuras</em></p>

### Modelo Mecánica de Materiales (Pandeo de Columna)

El diseño está compuesto por un sistema de pandeo de columna. Este sistema permite aplicar cargas de compresión a una columna para las condiciones de borde de apoyo simple y empotrado, representando visualmente los conceptos del efecto de la esbeltez, las condiciones de apoyo y la carga crítica.

<p align="center">
  <img src="https://github.com/user-attachments/assets/d7031269-62a8-477f-b136-55199230ad15" alt="Modelo Mecánica de Materiales" width="250"/>
</p>
<p align="center"><em>Figura: Registros fotográficos del Modelo de Mecánica de Materiales (Pandeo)</em></p>

### Modelo Mecánica de Materiales (Vigas)

El diseño está compuesto por un conjunto de vigas con tres tipos de perfiles (ángulo rotado, canal y doble T) y una base para las vigas. El conjunto de perfiles de vigas permite demostrar las distintas respuestas estructurales (flexión y torsión) que presentan ante cargas de corte. La base permite su rotación para visualizar el comportamiento en el eje fuerte como en el eje débil.

<p align="center">
  <img src="https://github.com/user-attachments/assets/e6b37868-8a1c-49e1-80eb-370345731d78" alt="Modelo Mecánica de Materiales - Vigas" width="350"/>
</p>
<p align="center"><em>Figura: Registros fotográficos del Modelo de Mecánica de Materiales (Vigas)</em></p>

### Modelo Diseño en Acero

El diseño está compuesto por una viga de perfil rectangular con un corte de sección circular y una base para la viga. Mediante la aplicación de carga de corte en el corte de la sección circular, permite demostrar el pandeo lateral torsional.

<p align="center">
  <img src="https://github.com/user-attachments/assets/66747b36-af32-4e63-ae19-c64a58b0d701" alt="Modelo Diseño en Acero" width="200"/>
</p>
<p align="center"><em>Figura: Registros fotográficos del Modelo de Diseño en Acero</em></p>
