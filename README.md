# hamr-orchestra
Fun Project for HAMR@ISMIR 2017

## Usage

    conda env create -f environment.yml    # setting up environment
    source activate hamr2017               # activating environemnt
    jupyter notebook hamr-orchestra.ipynb  # starting notebook

## Contribution

**If you want to contribute to this repository, please install the [nbstripout pre-commit hook](https://github.com/kynan/nbstripout)!** Otherwise version control with Jupyter notebooks is no fun!

    conda install -c conda-forge nbstripout nbconvert
    nbstripout --install
