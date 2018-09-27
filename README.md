# cookiecutter-latex-ieeeconf

A cookie cutter for latex manuscript used for IEEE conferences (ICASSP, WASPAA, etc).

To quickly get started on this new ICASSP paper, do the following

    # if not done yet, install cookie cutter
    pip install cookiecutter
    
    # create the new paper draft
    cookiecutter https://github.com/fakufaku/cookiecutter-latex-ieeeconf

## Compile the document

The template uses [scons](https://scons.org/) to automate the latex compilation.

    # if not done yet, install scons
    pip install scons
    
    # compile document (i.e. make)
    scons
    
    # clean up and delete all files (i.e. make clean)
    scons -c
