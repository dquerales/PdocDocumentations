# pdoc_documentations

An example for create documentations using pdocs 

## Installation

```
pip3 install pdoc3
```
   
## How to use
1. Create documentation

```
python -m pdoc --html <path to code> --output-dir <path to documentation>
```

```
python -m pdoc --html src --output-dir docs
```
2. Create a html for githubpages to redirect src/index.html
```
<!DOCTYPE html>
<html>

<head>
    <meta http-equiv="refresh" content="0; url=./src/index.html">
</head>

</html>
```
3. Deploy github pages using <code>/docs</code> as root

[Github Page](https://dquerales.github.io/pdoc_documentations/)

## Contact

Daniel Querales - d.querales@gmail.com