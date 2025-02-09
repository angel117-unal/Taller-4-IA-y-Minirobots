  # Taller 4 Programación genética
  
### Presentado por:
- **Ángel Rivera Amortegui**
- **Daniel Echeverry Jimenez**

---

## **Punto 1: Ejemplo de Mepx**
Archivo:

Descripción: 


---

## **Punto 2: utilizar Programación Genética para encontrar el diseño de un circuito lógico, 7 segmentos**
Archivo: [4_2_programación_genética.ipynb](./4_2_programación_genética.ipynb)

Descripción: Este código utiliza la biblioteca DEAP para implementar algoritmos evolutivos en dos problemas diferentes:
1. Diseño de circuitos lógicos en donde se definen funciones lógicas (AND, OR, NOT) para construir árboles sintácticos que simulan un codificador de 7 segmentos.
Los individuos son representaciones de árboles y se evalúan comparando sus salidas con una tabla de verdad esperada.
Se aplican operadores genéticos como cruzamiento, mutación y selección para optimizar la solución.
2. Optimización matemática: El objetivo es minimizar la suma de cuadrados de una lista de números reales. Los individuos son listas de números aleatorios, y se evalúan mediante la función suma de cuadrados. Se aplican operadores genéticos estándar para evolucionar hacia soluciones óptimas.
El código configura estadísticas, un Hall of Fame para almacenar las mejores soluciones y ejecuta los algoritmos con parámetros ajustables como tamaño de población y número de generaciones.
---

## **Punto 3: robot que le entrega galletas al grupo de ingenieros de diseño de robots usando Programación genética.**
Archivo: [PG_RobotGalletas.ipynb](./PG_RobotGalletas.ipynb)

Descripción: Este código implementa un sistema basado en programación genética para optimizar el movimiento de un robot dentro de una sala, con el objetivo de entregar galletas a ingenieros posicionados en ubicaciones aleatorias. El robot utiliza funciones aritméticas y de desplazamiento como operaciones (+, -, UP, DOWN, LEFT, RIGHT) para calcular y ejecutar rutas hacia los ingenieros, penalizando movimientos fuera de límites o recorridos excesivos.
El proceso incluye:
- Definición de funciones y terminales: Representan operaciones y valores para generar árboles sintácticos que describen los movimientos del robot.
- Inicialización aleatoria: Se generan ingenieros y robots con posiciones aleatorias dentro de la sala.
- Evolución genética: A través de una población inicial de cromosomas, el sistema evalúa aptitudes basadas en las galletas entregadas y penalizaciones por ineficiencia. Luego realiza selección, cruce, y mutación para optimizar rutas.
- Evaluación iterativa: Tras varias generaciones, se selecciona el mejor cromosoma como solución óptima.
Este código simula un entorno evolutivo donde el robot mejora progresivamente sus decisiones para maximizar la entrega eficiente de galletas.

## **Punto 4: Programación genética para una máquina despulpadora de café**
Archivos:  Archivo: [PG_máquina_despulpadora_de_café.ipynb](./PG_máquina_despulpadora_de_café.ipynb)

Descripción: Este código implementa un algoritmo de programación genética (PG) para optimizar fórmulas matemáticas que predicen la velocidad ideal basada en parámetros como el peso y los granos. Se define una población inicial de árboles de fórmulas construidos a partir de funciones primitivas (add, sub, mul, div) y terminales (peso, granos, constantes). Las fórmulas se evalúan en un contexto específico, y su desempeño (fitness) se mide comparando las predicciones con valores ideales. El algoritmo evoluciona la población a través de selección, cruzamiento y mutación durante varias generaciones, con el objetivo de encontrar la fórmula más precisa.

### Notas adicionales:
Este repositorio contiene la resolución detallada de los puntos del taller 4 sobre programación genética y conceptos básicos. Cada programa ha sido documentado con descripciones claras para facilitar su comprensión y replicación.
