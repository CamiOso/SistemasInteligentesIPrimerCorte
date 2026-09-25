# Sistemas Inteligentes I — Primer Corte

Trabajo final del primer corte de la asignatura Sistemas Inteligentes I (Universidad de Caldas).

## Integrantes

- Cristian Camilo Osorio Granada

## Descripción

Solución de los talleres propuestos al final de los notebooks trabajados durante las clases del primer corte, sobre estrategias de búsqueda:

1. Búsqueda no informada: BFS y DFS.
2. Búsqueda informada: Costo Uniforme, A* y Beam Search.
3. Búsqueda adversarial: Minimax.
4. Búsqueda adversarial: poda Alfa–Beta.

## Notebooks

- `Resolucion_Problemas_Busqueda_NoInformada_CristianCamiloOsorioGranada.ipynb` — Búsqueda no informada: BFS y DFS aplicados a grafos, laberintos, el problema de los recipientes de agua y el 8-puzzle.
- `Resolucion_Problemas_Busqueda_Informada_CristianCamiloOsorioGranada.ipynb` — Búsqueda informada: Costo Uniforme, A*, Beam Search y reto del 8-puzzle.
- `Resolucion_Problemas_Busqueda_Adversarial_Minimax_CristianCamiloOsorioGranada.ipynb` — Búsqueda adversarial: algoritmo Minimax aplicado a árboles de juego, al juego de las piedras y a Tres en raya.

## Cómo ejecutar

1. Clonar el repositorio:

   ```bash
   git clone https://github.com/CamiOso/SistemasInteligentesIPrimerCorte.git
   cd SistemasInteligentesIPrimerCorte
   ```

2. Instalar las dependencias (Python 3.10+):

   ```bash
   pip install -r requirements.txt
   ```

3. Abrir el notebook:

   ```bash
   jupyter notebook
   ```

   O abrir la carpeta en VS Code y correr el notebook desde ahí (requiere la extensión Jupyter).

4. Ejecutar todas las celdas en orden (Kernel → Restart & Run All).

### Dependencias

- `matplotlib` — visualización de mapas y caminos.
- `notebook` — para abrir y ejecutar los `.ipynb`.

El resto del código usa solo la librería estándar de Python (`heapq`, `itertools`, `math`, `collections`, `time`).
