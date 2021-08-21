# Welcome MKDocs Edgar's Custom Material-template

This is a custom setup based on [mkdocs.org](https://www.mkdocs.org) and [MKDocs Material](https://squidfunk.github.io/mkdocs-material/)  that contains the basic project documentation config, including, README, code of conduct, contributing and licece


## Project layout

    mkdocs.yml    # The configuration file.
    README.md     # Repository explanation
    CODE_OF_CONDUCT.md    # 
    LICENSE
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.


## Install

MkDocs requires a recent version of Python and the the Python package manager, pip, to be installed on your system.

You can check if you already have these installed from the command line:

``` shell
$ python --version
    Python 3.8.2
$ pip --version
    pip 20.0.2 from /usr/local/lib/python3.8/site-packages/pip (python 3.8)
```

If you don't have them make sure to install both. After that: 


``` shell
pip install mkdocs
pip install mkdocs-material 
# Configure cool material extensions
pip install mkdocs-material-extensions  
# For adding git-revision-upadte to your documentation site 
pip install mkdocs-git-revision-date-plugin

# This is just required to create documenation from jsdocs
npm i jsdoc-to-markdown 
```

or simply do:

``` shell
# Install the nwe pacakge
npm i nwe 
# Setup the MKDocs + Materila and clone the tempalte into your repo
nwe docs -m 
```


## MKDocs Commands 

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.


## More documentation

- For custom docs documentation: [MKDocs Material](https://squidfunk.github.io/mkdocs-material/)

- For writting quality documentation code [Typora](https://typora.io)

- For more information about project documentatino [Project documentation tools](https://www.altexsoft.com/blog/business/technical-documentation-in-software-development-types-best-practices-and-tools/)

- For easy convertion between JSDoc and MKDocs check the **nwe docs** command: [nwe npm](https://www.npmjs.com/package/nwe)


## Contact info 

You can contact me on LinkedIn

[Edgar Gago Carrillo](https://www.linkedin.com/in/edgargagocarrillo/)

or at:

> edgargc.upc@gmail.com

## Licence 

[MIT](https://opensource.org/licenses/MIT)
