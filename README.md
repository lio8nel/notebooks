# Notebooks

Various notebooks on various topics, more to come here:
* [fourier.ipynb](fourier.ipynb): Few audio / fourier explorations, moslty used to re-learn some basics around generating /modifying signals.

## Install

I'm using [pyenv](https://github.com/pyenv/pyenv) for this project, their README is already full of details to install and use it.

Once python is properly setup, just install jupyter using pip:
`pip install jupyterlab`, then run `jupiter lab` and open the ipynb files.

To avoid a few gotchas (especially on MacOS), ensure that your executables are all shimmed by pyenv. Likely, verify that `python`, `pip` and `jupiter` executables are pointing to an `.pyenv` folder in your home directory:

```shell
which jupyter pip python
/Users/yourhomefolder/.pyenv/shims/jupyter
/Users/yourhomefolder/.pyenv/shims/pip
/Users/yourhomefolder/.pyenv/shims/python
```
