
# Laboratorio 5 - Inteligencia Artificial
## CC3045 - Semestre I - 2024

### Descripción
Este laboratorio se centra en la aplicación de algoritmos de búsqueda en grafos para resolver laberintos. La tarea involucra recibir una imagen de un laberinto, discretizarla, y aplicar algoritmos de búsqueda para encontrar la solución, destacando BFS, DFS, y A*.

### Tareas
- **Task 1.1:** Discretización de la imagen del laberinto.
- **Task 1.2:** Creación de un framework de problemas utilizando POO para definir el laberinto.
- **Task 1.3:** Implementación de algoritmos de búsqueda en grafos: BFS, DFS, y A* con dos heurísticas distintas.
- **Task 1.4:** Construcción de la salida gráfica de la solución del laberinto.

### Entregables
- Código fuente en un repositorio de GitHub.
- Video demostrativo del funcionamiento de la solución.

### Evaluación
- La evaluación se basará en la correcta implementación de las tareas, con un total de 10 puntos disponibles, más un punto adicional por la presentación del video.


## Requisitos Previos (Usamos CONDA !! :D)

- Anaconda o Miniconda instalado en su sistema. Si no tiene Anaconda o Miniconda, puede descargarlo desde [aquí](https://www.anaconda.com/products/individual) o [aquí](https://docs.conda.io/en/latest/miniconda.html), respectivamente.

## Configuración del Entorno

Siga estos pasos para configurar el entorno Conda necesario para ejecutar el notebook:

1. **Clonar el Repositorio**

Primero, clone el repositorio a su máquina local usando Git:

```bash
git clone https://github.com/AndresQuinto5/IA_LAB5.git
cd repositorio
```

2. **Crear el Entorno Conda**

Cree un entorno Conda utilizando el archivo `environment.yml` incluido en el repositorio. Esto instalará todas las dependencias necesarias.

```bash
conda env create -f environment.yml
```

3. **Activar el Entorno**

Una vez creado el entorno, actívelo con:

```bash
conda activate nombre_del_entorno
```

Reemplace `nombre_del_entorno` con el nombre del entorno especificado en el archivo `environment.yml`.

## Ejecutar el Jupyter Notebook

Con el entorno activado, inicie Jupyter Notebook o JupyterLab o abrir en VisualStudio Code:

```bash
jupyter notebook
# o
jupyter lab
```

Navegue hasta el notebook que desea ejecutar y ábralo. Ahora debería ser capaz de ejecutar todas las celdas sin problemas.

### VIDEO:

[VIDEO](https://youtu.be/7hwH3c9_qew)

### Autores
- [Andres Quinto - 18288](https://github.com/AndresQuinto5)
- [Marlon Hernández - 15177](https://github.com/ivanhez)
