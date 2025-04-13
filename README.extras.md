# simple-ocrmypdf

Simple GUI for ocrmypdf

## Testar program

```bash
cd src
python3 -m simple_ocrmypdf.program
```

## Upload to PYPI

```bash
pip install --upgrade pkginfo twine packaging

cd src
python -m build
twine upload dist/*
```

## Install from PYPI

The homepage in pipy is https://pypi.org/project/simple-ocrmypdf/

```bash
pip install --upgrade simple-ocrmypdf
```

Using:

```bash
simple-ocrmypdf
```

## Install from source
Installing `simple-ocrmypdf` program

```bash
git clone https://github.com/trucomanx/SimpleOcrMyPdf.git
cd SimpleOcrMyPdf
pip install -r requirements.txt
cd src
python3 setup.py sdist
pip install dist/simple_ocrmypdf-*.tar.gz
```
Using:

```bash
simple-ocrmypdf
```

## Uninstall

```bash
pip uninstall simple_ocrmypdf
```
