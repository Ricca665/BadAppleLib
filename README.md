# BadAppleLib
A python library specifically made to just play bad apple!

# How to install
In your terminal, simply run these commands in order:
```
python -m pip install blessed
python -m pip install BadAppleLib
```
# How to use
Simple snippet:
```
import BadApple
BadApple.Play()
```
> This will just play the video like normal

```
import BadApple
BadApple.Play(True)
```
> This will ignore the checks that are done when the
> console is too small

```
import BadApple
BadApple.Play(False, 1/60)
```

> This will NOT ignore the checks that are done when the
> console is too small and plays the video at 60 fps

When it finishes playing without interruptions, it returns ```True```, if the user presses CTRL + C it returns ```False```
It also returns ```False``` when the console window is too small

# Features
- [x] Add basic functionality
- [x] Add FPS and checks
- [ ] Add audio

# Contribuiting
This project is built under the MIT License
Feel free to contribuite!