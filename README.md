# pyiron publication template

This template is forked from the official pyiron template and adapted for my own research projects.
In particular, it is assumed that there is custom `.py` code that should have unit tests.

## Step by step

* Create a new project with this template.
* Update the `environment.yml` to the basic resources you will need.
* Refactor --> Rename `pyiron_src` to something sensible for your project.
* Update `example.ipynb` to run something simple using your new pyiron library.
* Develop and science your heart out.
    * Everything in the `projects` folder is gitignored, so put your projects there 
    * The notebook `scratch.ipynb` is also ignored
    * Be mindful about the volume of data (e.g. calculation results) you push and pull;

## mybinder

Is not yet working for me at all.
I left these parts as-is from the orginal template.

## jupyterbook

Worked when I went to the GitHub settings and created the book there.
Nonetheless, I haven't changed anything here relative to the official tempalte.

## Everything else

E.g. how to import existing data?
Go look at the README for the official template.


## License
pyiron, the pyiron publication template, and this fork of it are all licensed under the BSD-3-Clause license which is included in the `LICENSE` file. 
In addition an `CODE_OF_CONDUCT.md` file is included to foster an open and welcoming environment.
