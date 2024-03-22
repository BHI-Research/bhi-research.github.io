# Javier Iparraguirre >> Personal site

See the site live at [https://javierip.github.io/](https://javierip.github.io/)

## Related Links

* [MkDocs: Project documentation with Markdown](https://www.mkdocs.org/)
* [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)
* [Deploying your docs](https://www.mkdocs.org/user-guide/deploying-your-docs/)
* [Custom domains and GitHub Pages](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/about-custom-domains-and-github-pages)

## Setup and Run

Linux instructions:

```bash
$ python3 -m venv --system-site-packages ./venv-mkdocs
$ source ./venv-mkdocs/bin/activate 
(venv-mkdocs) $ pip install --upgrade pip
(venv-mkdocs) $ pip install -r requirements.txt
(venv-mkdocs) $ mkdocs new .

# run
(venv-mkdocs) $ mkdocs serve 

# deploy
(venv-mkdocs) $ mkdocs gh-deploy

# when done
(venv-mkdocs) $ deactivate
```

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs help` - Print this help message.

## Project layout

```
    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
```
