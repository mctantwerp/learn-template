# Usage

* Make sure you have Python 3 installed
* Install mkdocs (`pip install mkdocs`)
* Install mkdocs-material (`pip install mkdocs-material`)
* Install the required packages (see `Used packages` below)
* Use `mkdocs serve` to view the site locally

## Important!

We use the **Material Insiders** theme, which gives us extra features and options. When testing locally, some visuals may not appear as you would expect based on the kitchen sink. Don't worry! Once this is built and deployed, everything will look correct.

For larger changes or when writing mini courses, an online test environment will always be provided where you can test and properly view all your changes. Contact sam.serrien@kdg.be if you would like to use this.

# Used packages

pip install mkdocs-git-committers-plugin-2
pip install mkdocs-git-revision-date-localized-plugin
pip install mkdocs-git-authors-plugin

# Interesting features / settings

## No toggles but sections for the first level of navigation

```md
features
    - navigation.sections
```

# Useful links

* [Icons from Font Awesome with their codes](https://squidfunk.github.io/mkdocs-material/reference/icons-emojis/)
