# Genesis & IASA Data Science Champ

## Task
Train robust interoperable model for product and marketing teams that predicts month user lifetime value.

## Project structure
Source code contains code for [exploratory data analysis](./src//EDA.ipynb) and
model [training](./src/train.ipynb).
[Model directoty](./model/) contains pre-trained model and its weights.
[Data directory](./data/) contains dataset.

## Project tree

 * [data](./data)
 * [model](./model)
     * [model.pkl](./model/model.pkl)
 * [src](./src)
     * [EDA.ipynb](./src/EDA.ipynb)  
     * [train.ipynb](./src/train.ipynb)
 * [LICENSE](./LICENSE)
 * [README.md](./README.md)
 * [requirements.txt](./requirements.txt)
 * [.gitignore](./.gitignore)
 * [.gitattributes](./.gitattributes)

## Installation

### Clone project
```bash
git clone https://github.com/Dichik/TestTask_IASA_DataScience_Champ
```

### Create virtual environment
```bash
python -m venv venv
```

### Activate it (depends on the OS)
```bash
venv\\Scripts\\activate
```

### Install dependencies
```bash
pip install -r requirements.txt
```
