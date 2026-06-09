# Introducción al criptoanálisis cuántico con Qiskit

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter%20Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Numpy](https://img.shields.io/badge/-NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Qiskit](https://img.shields.io/badge/IBM_Qiskit-6929C4?style=for-the-badge&logo=qiskit&logoColor=white)
![Mathplotlib](https://img.shields.io/badge/-Matplotlib-000000?style=flat&logo=python)

Este proyecto es una introducción al criptoanálisis cuántico empleando Qiskit, aplicando el agloritmo de Grover sobre instancias pequeñas del problema LWE utilizando un oráculo simplificado. Mediante simulaciones, se analizan las iteraciones necesarias para que el algoritmo encuentre la solución con alta probabilidad.

**Autor**: Alicia Sáenz de Zaítigui Colina

**Tutor**: Francisco Javier Blanco Romero

**Universidad**: Universidad Carlos III de Madrid

**Curso**: 2025-2026

## 📂 Contenido del repositorio

- `grover_lwe.ipynb`: notebook con la implementación del experimento.
- `README.md`
- `requirements.txt`: dependencias del proyecto.

## ⚙️ Requisitos

El proyecto se ha creado utilizando Python 3.12.9. Para ejecutarlo, se necesitan las siguientes dependencias: 

- Qiskit 2.3.1
- Matplotlib 3.10.8
- Numpy 2.4.1
- Notebook 7.3.2

Pueden instalarse con:

```bash
pip install -r requirements.txt
```

## 📝 Metodología

Los experimentos siguen los siguientes pasos:

1. Generación de una instancia LWE pequeña
2. Cálculo del residuo
3. Evaluación del predicado oracular
4. Construcción del oráculo de fase
5. Construcción del operador de Grover
6. Construcción del circuito completo
7. Simulación 
8. Comparación del número de iteraciones óptimo con los resultados experimentales obtenidos

## 💻 Ejecución

1. Abrir `grover_lwe.ipynb`
2. Ejecutar todas las celdas del notebook en orden
3. Comprobar el residuo y la condición que debe de cumplir
4. Observar los circuitos e histogramas de probabilidades obtenidos para los diferentes casos de prueba
5. Observar los resultados en la gráfica comparativa

## 📊 Resultados

En los casos de prueba analizados, el algoritmo de Grover permite encontrar la solución en un número de iteraciones 
que se ajustan a los resultados teóricos esperados.

## 💡Conclusión

Este trabajo muestra cómo representar el problema de búsqueda LWE y cómo implementar un oráculo simplificado para resolverlo con el algoritmo de Grover. Se trata de una prueba de concepto simplificada para estudiar las iteraciones requeridas por el algoritmo de Grover para obtener la solución con la máxima probabilidad posible

## 📖 Referencias

- [Qiskit](https://www.ibm.com/quantum/qiskit)
- [Numpy](https://numpy.org/doc/2.4/)
- [Matplotlib](https://matplotlib.org/3.10.0/)
- [Notebook](https://jupyter-notebook.readthedocs.io/en/v7.3.2/user-documentation.html)