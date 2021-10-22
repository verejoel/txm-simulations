## Installation
Guidance given for MacOS and Homebrew - install [homebrew](https://brew.sh/) if you
don't already have it. For other systems, consult the installation guides for Pyenv and
Direnv.

See [here](https://www.digitalocean.com/community/tutorials/how-to-manage-python-with-pyenv-and-direnv)
for more on managing Python with Pyenv and Direnv.

Start by cloning this repo and working in the repo base directory.

1. Install Pyenv and Direnv.
```
brew install pyenv
brew install direnv
```
2. Get the latest version of Python 3.8.
```
pyenv install 3.8.3
```
3. Set the local Python version.
```
pyenv local 3.8.3
```
4. Activate direnv.
```
direnv allow
```
5. Install Python dependencies.
```
pip install -r requirements.txt
```

This will setup your environment with the correct Python version and package
dependencies.

