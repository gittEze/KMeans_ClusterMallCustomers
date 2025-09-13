# Clustering - Aprendizaje no supervisado - Clientes de comercio  

En este proyecto se implementó el algoritmo **K-Means** para segmentar clientes de un centro comercial utilizando el dataset **Mall_Customers**.  
El análisis se centró en tres variables:  

- **Age**  
- **Annual Income**  
- **Spending Score**   

## Metodología  
Primero se realizó la carga y limpieza de los datos, donde se transformaron los valores de género a variables numéricas, se eliminaron duplicados y se verificó la existencia de valores nulos. Despues, se aplicó la tecnica de escalado con **StandardScaler** para normalizar las variables seleccionadas, para que todas tuvieran la misma importancia dentro del modelo. Con los datos preparados, se implementó el algoritmo **K-Means**, evaluando distintos valores de *k* y seleccionando finalmente **k = 3**.  

## Visualización  
Para la representación gráfica de los resultados se utilizó la librería **Seaborn**, generando un gráfico de dispersión en el que cada punto representa a un cliente. En dicho gráfico, los ejes corresponden a las variables **Ingreso anual** y **Edad**, mientras que los colores diferencian los grupos formados por el algoritmo K-Means. Esta visualización permite observar patrones claros en la distribución de los clientes, lo cual resulta útil para la gestión de clientes.  

<img width="564" height="432" alt="image" src="https://github.com/user-attachments/assets/9bcb4ff6-b240-4ccc-9a50-3b57a01b95e0" />
