# End User Documentation Site

A sphinx project used to generate static end user documentation for deployment in a webserver.

## Prerequisites

Building the documentation requires a working sphinx installation.  Developers running a variant of `python_developer_environment.cfg` buildout config have the sphinx environment installed by that buildout.

For most users that will be authoring this content a small virtual environment with  only sphinx installed is preferred.

### Installing Prerequisites

This guide assumes installation on Mac OSX Sierra. 

#### Installing VirtualEnv

VirtualEnv can be easily installed from pip

```bash
[sudo] pip install virtualenv
```
For more details see: https://virtualenv.pypa.io/en/stable/installation/

#### Installing VirtualEnvWrapper

virtualenvwrapper is a set of shell functions defined to make working with virtual environments easier.

First virtualenvwrapper should be installed via pip

```bash
[sudo] pip install virtualenvwrapper
```

Next some lines need to be added into your startup file.

```bash
export WORKON_HOME=$HOME/.virtualenvs >> ~/.bashrc
export PROJECT_HOME=$HOME/Devel >> ~/.bashrc
source /usr/local/bin/virtualenvwrapper.sh >> ~/.bashrc
```

Now source the startup file to pick up your changes

```bash
source ~/.bashrc
```

For more details see: http://virtualenvwrapper.readthedocs.io/en/latest/install.html

#### Creating your virtualenv

Now we need to setup a virtualenv for you sphinx install.  This is the virtualenv you will use to build the project.

First use `mkvirtualenv` to create a virtualenv.

```bash
mkvirtualenv userdocs
```

Now we need to activate our new virutal environment. We do that with the `workon` command.

```bash
workon userdocs
```

**Note:** it is important you activate this virtual environment anytime you need to build the documentation.

#### Installing Sphinx

Now that we have our virtualenv environment setup and avaiable to us we can install sphinx using pip.

```bash
pip install sphinx
```

This will take care of installing sphinx and any dependencies required.

For more details see: http://www.sphinx-doc.org/en/stable/tutorial.html


## Editing Documentation

Documentation and site structure is authored using reStructuredText. In Sphinx source files, you can use most features of standard reStructuredText. ReStructuredText files are plain text files that use an extensible markdown-style format for semantically marking up text.  You can edit reStructuredText (.rst) files in any standard text file that supports plain text editing.

Sphinx provides a [reStructuredText primer](http://www.sphinx-doc.org/en/stable/rest.html#rst-primer) for getting started.  This should be your first stop for learning the basic.  If you want to learn more the authoritative docs for reStructuredText can be found [here](http://docutils.sourceforge.net/rst.html).

Sphinx has also extended reStructedText to provide additional functionality.  A full list of the extended markup constructs can be found [here](http://www.sphinx-doc.org/en/stable/markup/index.html#sphinxmarkup) for those that are interested.

## Building

To generate the site html the `sphinx-build` command can be used.  For simplicity a MakeFile has been provided with this repository.  To build the html site from source run:

```bash
make html
```

This will generate the static site in the `_build` folder.  This can be deployed to a webserver or opened in your web browser.

For more details see: http://www.sphinx-doc.org/en/stable/tutorial.html#running-the-build


