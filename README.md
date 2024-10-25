<h1 align="center">
lensegua-dataset
</h1>

<p align="center">Conjunto de datos de lengua de señas de Guatemala</p>
<p align="center">Autor: Luis Diego Santos Cúellar</p>

<hr />

## Uso
El dataset se encuentra en formato pickle, para cargarlo se puede utilizar el siguiente código:

```python
import pickle

with open('LELNSEGUA.pkl', 'rb') as f:
    dataset = pickle.load(f)
```

## Variantes
El dataset cuenta con dos variantes, una que contiene los datos con cierto preprocesamiento y otra que contiene los datos sin preprocesar. Las variantes se encuentran en los archivos `LELNSEGUA.pkl` y `LELNSEGUA_RAW.pkl` respectivamente. 

Ambos archivos contienen la misma información, la cual se extrajo de un conjunto de 960 videos de lengua de señas de Guatemala. Cada video contiene una palabra en lengua de señas.

