pyenv local 3.7.2
python -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install

npm install -g git+ssh://git@github.com/nearbydelta/itypescript.git#e1997b1307f02f30ad5d09eaae9ba27d56f63f20
