```
brew install python
python3 -m pip install virtualenv
python3 -m virtualenv venv
. ./venv/bin/activate
python -m pip install venvdotapp
venvdotapp
# For time being, install the dev version for the latest OSX versions
python -m pip install pygame==2.0.0.dev4
python -m pygame.examples.aliens
```
