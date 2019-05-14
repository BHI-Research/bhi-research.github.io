# BHI Research Website

Create a virtualenv and install dependencies:

```
virtualenv --system-site-packages -p python3 ./venv-mkdocs
source venv-mkdocs/bin/activate
(venv-mkdocs) $ pip install --upgrade pip
(venv-mkdocs) $ pip install mkdocs mkdocs-material


```

Run the server:
```
(venv-mkdocs) $ mkdocs serve
```

Generate static site:
```
(venv-mkdocs) $ mkdocs build
```

More info:
- https://www.mkdocs.org/
- https://squidfunk.github.io/mkdocs-material/
