# docker-environment-learn

## python の仮想環境

### anaconda

```
conda create -n python310_ws python=3.10
conda activate python310_ws
pip install jupyter ipykernel
ipython kernel install --user --name=python310_ws
pip install -r requirements.txt
```

### venv

```
python -m venv env
source env/bin/activate
# env\Scripts\Activate.ps1
pip install -r requirements.txt
```

### poetry

project 開始

```
pip install poetry
# curl -sSL https://install.python-poetry.org | python3 -
poetry new poetry-sample
```

## docker を使った python 環境構築
