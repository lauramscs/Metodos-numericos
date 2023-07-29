# Metodos-numericos

Este repositorio fue creado cómo parte del trabajo realizado en el servicio social bajo el programa ``Fronteras en la Cosmología de precisión: de teorías alternativas a la gravedad a cosmoestadística con machine learning''

Los códigos contenidos en este repositorio esploran los siguientes métodos:

Newton-Raphson el cual sirve para encontrar las raíces de funciones reales y de variable real basándose en en la expansión en series de Taylor de la función. 

Runge-Kutta, los cuales son métodos muy utilizados para resolver problemas de ecuaciones diferenciales ordinarias con condiciones iniciales mediante la propagación de una solución a lo largo de un intervalo combinando la información de varios pasos tipo Euler. 

Método de Shooting el cual se basa en transformar un problema de valores a la frontera en un problema de condiciones iniciales para poder ser resuelto con un método tipo Runge-Kutta.

En "Lorenzrk4" se construye un código para implementar el método de Runge-Kutta de orden 4.
<a href=\"https://colab.research.google.com/github/lauramscs/Metodos-numericos/blob/main/Lorenzrk4.ipynb">
   <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>   


En "Shooting_Tiro_parabolico_Amortiguado" se emplea el método de Runge Kutta y además se desarrolla el código para implementar el método de Newton-Raphson en el método de Shooting. 
<a href=\"https://colab.research.google.com/github/lauramscs/Metodos-numericos/blob/main/Shooting_Tiro_parabolico_Amortiguado.ipynb">"
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Finalmente en  "Shooting_Oscilador_Armonico" se emplea el código creado para el método de Shooting para resolver el problema del Oscilador Armónico Cuántico.

<a href="https://colab.research.google.com/github/lauramscs/Metodos-numericos/blob/main/Shooting_Oscilador_Armonico.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>


En cada uno de los códigos se explica con detalle cada paso a seguir para implementar dicho método, esto con el fin de que el lector pueda implementar los códigos para resolver otros problemas del mismo tipo, únicamente cambiando el sistema.
