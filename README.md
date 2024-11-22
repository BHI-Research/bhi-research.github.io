# BHI research site

See the site live at [https://bhi-research.github.io/](https://bhi-research.github.io/)

## Related Links

* [MkDocs: Project documentation with Markdown](https://www.mkdocs.org/)
* [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)
* [Deploying your docs](https://www.mkdocs.org/user-guide/deploying-your-docs/)
* [Custom domains and GitHub Pages](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/about-custom-domains-and-github-pages)

## Setup and Run

Linux instructions:

```bash
(base) $ conda create -n mkdocs-env python=3.12 
(base) conda $ activate mkdocs-env
(mkdocs-env) $ pip install -r requirements.txt
(mkdocs-env) $ mkdocs new .

# Updating packages before updating
(mkdocs-env) $ pip install --upgrade -r requirements.txt

# run
(mkdocs-env) $ mkdocs serve 

# deploy
(mkdocs-env) $ mkdocs gh-deploy
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
