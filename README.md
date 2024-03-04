# Algoritmo de Detección y Recuperación de Fallos

## Descripción

El programa simula un conjunto de nodos en una red distribuida que pueden detectar fallos en otros nodos y recuperarlos según sea necesario. Algunas características clave incluyen:

- Los nodos pueden enviar mensajes entre sí para detectar fallos y coordinar la recuperación.
- Se utiliza un hilo separado para el proceso de detección de fallos (heartbeat) y replicación de datos.
- El nodo con el ID 0 actúa como nodo primario y gestiona la replicación de datos.
- Los nodos pueden fallar, recuperarse y sospechar de otros nodos en función de ciertas condiciones aleatorias.

## Funcionamiento

- Ejecutar el programa `fault_detection.py`.
- Se crean nodos simulados, cada uno con su propio ID y estado.
- Se inician threads para cada nodo, que ejecutan los métodos de detección de fallos y replicación.
- Los nodos envían mensajes entre sí para detectar fallos, coordinar la replicación y recuperarse según sea necesario.
- Al finalizar la ejecución, se determina y muestra el nodo líder elegido.

## Requisitos

- Python 3.x

![dog-computer](https://github.com/LuisRosado/Algoritmo_de_Detecci-n_y_Recuperaci-n_de_Fallos/assets/140114139/03d9ceea-8ef2-477d-8eaa-9c7dc9b0dac1)
