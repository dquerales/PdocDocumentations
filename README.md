# pdoc_documentations

An example for create documentations using pdocs libraries 

## Installation

```
pip install pdoc3
```
   
## Usage
1. Create the documentation using the following:

```
python -m pdoc --html <path to code> --output-dir <path to documentation>
```

## Example

1. Create documentation:

```
python -m pdoc --html src --output-dir docs
```

2. Create a html for githubpages to redirect the new src/index.html

```
<!DOCTYPE html>
<html>

<head>
    <meta http-equiv="refresh" content="0; url=./src/index.html">
</head>

</html>
```

3. Deploy a github pages using the folder <code>/docs</code> as root:

- [Github Page](https://dquerales.github.io/pdoc_documentations/)


## Contact

Daniel Querales - d.querales@gmail.com