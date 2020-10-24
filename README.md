# ai-talk


## Setup usando Google Colab
En este curso utilizaremos Jupyter Notebooks y el stack Pydata, que incluye las librerías Numpy, Pandas, Matplotlib y Scikit-learn.

**Google Colab** es muy similar en su uso a Google Docs. Puedes ir directamente a su pagina https://colab.research.google.com/ o abrir Google Drive, clickear en el botón “+ Nuevo” y desde ahí elegir la opción “Mas” y clickear en Colaboratory

Un notebook se compone de celdas de codigo y de texto. Una celda de codigo es ejecutable tecleando “Control + Enter”. Para probar que todo esta ok puedes ejecutar el siguiente codigo:

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import sklearn
```

Un solo punto adicional que queda por aclarar es que como estas trabajando en la nube no tienes directamente los archivos de la clase a mano para poder leerlos desde el notebook.

Para poder hacer uso de los datasets:
1. Copiar el link que al seleccionar algún dataset en el repositorio, se encuentra en la carpeta **datasets**
2. Con el link del archivo csv puedes llamar la función de pandas read_csv de la siguiente manera:

```python
import pandas as pd

url="https://raw.githubusercontent.com/garzuzo/ai-talk/master/datasets/peliculas.csv"
pd.read_csv(url)
```