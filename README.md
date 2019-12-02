# pygame-osx


# Install pygame on OSX Mojave, Python3 v.3.7.5

```
brew install python3  # TODO double check this
python3 -m pip install virtualenv
python3 -m virtualenv venv
. ./venv/bin/activate

# venvdotapp helps the python be a mac 'app'. So the pygame window can get focus.
python3 -m pip install venvdotapp
venvdotapp

# For time being, install the dev version for the latest OSX versions
python3 -m pip install pygame==2.0.0.dev4
python3 -m pygame.examples.aliens
```

### Links

[GettingStarted - pygame wiki](https://www.pygame.org/wiki/GettingStarted#Mac%20installation)

[pygame/examples at master · pygame/pygame](https://github.com/pygame/pygame/tree/master/examples)
