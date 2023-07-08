# Blog

A source code for my personal blog.

## Getting Started

Make sure you have these prerequisites:
- [Python3](https://www.python.org/downloads/)
- [Quatro](https://quarto.org/docs/get-started)

Install dependencies:

```shell
. venv/bin/activate
pip3 install -r requirements.txt
```

## Jupyter Notebook
### Useful Jupyter Commands

```shell
jupyter lab <path-to-ipynb>
```

## Quarto
### Useful Quarto Commands

#### Preview Website Locally

```shell
quarto preview
```

```shell
quarto preview path-to-ipynb
```

#### Build Website Locally

```shell
quarto render
```

### Useful Quarto Docs

- https://quarto.org/docs/websites/website-blog.html
- https://quarto.org/docs/publishing/github-pages.html
- https://quarto.org/docs/output-formats/html-themes.html#theme-options
- https://quarto.org/docs/websites/website-about.html
- https://quarto.org/docs/websites/website-listings.html

## Useful Python/Pip Commands
### Make a Venv

```shell
python3 -m venv venv
```

### Activate Venv

Activate `venv`

```shell
. venv/bin/activate
```

### Upgrade Pip

```shell
pip3 install --upgrade pip
```

### Install a Package

```shell
pip3 install <package-name>
```

### Freeze Dependencies

```shell
pip3 freeze > requirements.txt
```

