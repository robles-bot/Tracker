Notes obtained from: [Materials for MkDocs](https://squidfunk.github.io/mkdocs-material/)

# Installation
- Can be installed using pip:
  ```bash
  pip install mkdocs-material
  ```
  - Automatically installs compatible versions of all dependencies
- Can be install using git:
  - cloning the repo:
  ```bash
  git clone https://github.com/squidfunk/mkdocs-material.git
  ```
  - Install the themes and its dependencies:
  ```bash
  pip install -e mkdocs-material
  ```

# Creating site
- Go to the directory where you want your project to be located and enter:
```bash
  mkdocs new .
```

## Configuration
- [Minimal Configuration](https://squidfunk.github.io/mkdocs-material/creating-your-site/#minimal-configuration)
- [Advances Configuration](https://squidfunk.github.io/mkdocs-material/creating-your-site/#advanced-configuration)
- They also provide templates found [here](https://squidfunk.github.io/mkdocs-material/creating-your-site/#templates)

## Previewing
- Run:
  - mkdocs serve
to run the server after saving
- Run:
  - mkdocs serve --dirtyreload
to see only the current page (assuming you have a lot of files that need to be rebuilt)

## Building Site
- After editing you can build a static version of your site from your markdown files:
  - mkdocs build

# Publishing
- Suggests hosting code on GitHub
- Suggests using GitHub Actions to automate the deployment of the project documentation *This is what I need to learn now*
- Create a new GitHub Actions and copy [this](https://squidfunk.github.io/mkdocs-material/publishing-your-site/#with-github-actions):
  - when a new commit is pushed to either master or main, the site is built and deployed
- Using MkDocs:
  - From within the directory containing mkdocs.yml run:
  ```bash
  mkdocs gh-deploy --force
  ```



