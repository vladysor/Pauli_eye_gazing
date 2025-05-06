# Wiki Local Hosting
For proper editing it is much recommended to host the wiki locally. You need to do these steps only once for the setup.

## Python Installation
MkDocs is a python package, so first of all you need to instal [Python and pip](https://www.python.org/downloads/).

Confirm Python installation with the next two commands. If you see versions then everything is installed correctly
```powershell
python --version
```
```powershell
pip --version
```

![python installation](../assets/images/wiki_hosting1.png)

## MkDocs Installation
Now that you have pip, you can download MkDocs with the next pip command.

```powershell
pip install mkdocs
```

Confirm succesful installation by running mkdocs version command. Like previously if you see the message with version, you are good to go.
```powershell
mkdocs --version
```

!!! info
    Additional [MkDocs Installation Reference](https://www.mkdocs.org/user-guide/installation/#installing-mkdocs)


## Material for MkDocs Installation
We use Material Theme for MkDocs, you can install it buy running another pip command.

```powershell
pip install mkdocs-material
```

!!! info
    Additional [Material Reference](https://squidfunk.github.io/mkdocs-material/getting-started/)


## Running the Webpage locally
Now you can run the webpage with the `serve` command and see it locally by going to [localhost:8000](http://localhost:8000/) page.

```powershell
mkdocs serve
```

!!! warning
    Make sure to be in main repo folder in terminal

![website local](../assets/images/wiki_hosting1.png)

MkDocs includes live reloading server, if you see your changes, you can immediately see the results on the local page.

!!! info
    Additional [Hosting Reference](https://squidfunk.github.io/mkdocs-material/creating-your-site/)

## Publishing
Website is configured to automatically rebuild and deployed via GitHub pages on every new commit to master or main branch. Then it is accessible via github.io link.

Deployment logic is stored inside `./.github/workflows/ci.yml` file.
