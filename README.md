# Mycelia docs

## Requirements

- Python 3.8

## Setup

It's recommended to create a [virtualenv](https://pypi.org/project/virtualenv/)
inside the project folder:

    $ python -m venv env
    $ source env/bin/activate

Make sure **pip** is up to date:

    $ (env) python -m pip install -U pip
    $ (env) pip install -r requirements.txt

## Add content

The source files can be found in the './source.' directory. Source files are
written in [MyST](https://myst-parser.readthedocs.io/en/latest/) markdown.

To review the changes locally they can be built with the following command:

    $ (env) make html

Afterwards, the static files can be found in the './build/html' directory.
To review the changes just open the 'index.html' file.

## Publish

Changes are automatically built, pushed to the 'gh-pages' branch and published
after they have been merged into *main*.

The documentation can be found [here](https://mycelia-eco.github.io/docs/).
