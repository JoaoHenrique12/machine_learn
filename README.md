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

Exporting cells from notebook

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
- [which image model is the best ? ](https://www.kaggle.com/code/jhoward/which-image-models-are-best).

## Titanic data normalization

- Why there is P_class1 and P_class2 and not P_class3 ?
  - Cause class3 can be achieved by class 1 and 2.
- Why tere is a column with ones ?
  - ????
- Why tere is a column with log(Fare) ?
  - ????
- Why tere is a column with Age_N ?
  - ????
