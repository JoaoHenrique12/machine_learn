# Machine Learn

## Installing requirements

```bash
$ sudo apt install python3-virtualenv

$ virtualenv env
$ source env/bin/activate
$ pip3 install requirements.txt
```

### Jupyter

```bash
$ jupyter-lab
```

## Into the notebook.

```
?, ?? -> show what the function do.
doc() -> documentation.
%time -> return the time to execute that cell.

!ls -> execute a comand in terminal.
```

Exporting cells of notebook

```
#|default_exp app

#|export

from nbdev.export import notebook2script
notebook2script('app.ipynb')
```

Repository for Fast AI course.

## Lesson

### 01

Predictive model to find out if the image is a cat or a dog.

### 02

- Clean data.
- Putting your model in production.

### 03

- .pkl -> DataLoaders/DataBlocks and the trained model.
