# Blog
## Install Quatro

https://quarto.org/docs/get-started/

## Install Jupyter Notebook

## Make Venv

```shell
python3 -m venv venv
```

## Installation

Activate `venv`

```shell
. venv/bin/activate
```

Install dependencies

```shell
pip3 install -r requirements.txt
```

## Adding packages

Activate `venv`

```shell
. venv/bin/activate
```

Upgrade `pip3`

```shell
pip3 install --upgrade pip
```

Install your package

```shell
pip3 install <package-name>
```

pip3 install jupyter jupyterlab

Freeze

```shell
pip3 freeze > requirements.txt
```

## Installation

1. create python virtual env
python3 -m venv venv

2. Activate

. venv/bin/activate
. venv/bin/activate.fish
pip3 install --upgrade pip

3. Install jupyter

ipython kernel install --user --name=.venv
pip3 install nbconvert

4. Run jupyter

5. From the top right, select New and choose .venv kernel

jupyter nbconvert --to html someshit.ipynb

## Useful quatro

quarto preview

## Github pages

1. Follow this
https://docs.github.com/en/pages/quickstart

2. Wait 10 minutes

3. Visit Exegetech.github.io


## TODO

How to run jupyter markdown from venv?

To freeze

pip3 freeze > requirements.txt

To install

pip3 install -r requirements.txt
