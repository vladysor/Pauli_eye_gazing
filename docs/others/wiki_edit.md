# Wiki Contents Editing
When hosting the wiki locally, the local webpage automatically reloads to reflect any changes you make without the need to create a commit and waiting for GitHub Pages deployment. This makes it easy to see your updates in real-time. Refer to the [previous section](wiki_hosting.md) for instructions on how to achieve that.

## Website Appearance
The appearance of the website can be customized by editing the `./mkdocs.yml` configuration file. This file allows you to modify themes, colors, fonts, and other visual elements of your wiki. 

!!! tip
    For a full list of customization options, visit the official [Setup](https://squidfunk.github.io/mkdocs-material/setup/) Guide.

![appearance](../assets/images/wiki_editing1.png)

## Navigation Structure
First of all you need to define file structure inside `./mkdocs.yml` file. This way you define:

* Which Markdown files correspond to each page
* The page order
* The page titles

Editing this file allows you to control the overall organization and hierarchy of your wiki content.

![structure](../assets/images/wiki_editing2.png)

## Page Editing
To edit a specific page in the wiki, open the corresponding Markdown (`.md`) file. You can then add or modify content directly in the file. Material for MkDocs syntax provides plenty of options to format text, create code blocks, insert annotations, add links, or include other interactive elements.

!!! tip
    For a comprehensive list of all available syntax and features, refer to the official [Material for MkDocs Reference](https://squidfunk.github.io/mkdocs-material/reference/). This page includes detailed documentation on everything you can do within your Markdown files.

