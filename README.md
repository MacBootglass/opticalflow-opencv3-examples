# opticalflow-opencv3-examples
Quelques exemples d'applications sur les flux optiques avec OpenCV3 et Python 2.7

## Utilisation
* Tracking video:
```bash
$ cd submodules/tracking
$ python tracking6.py
```

* Horn Schunck:
```bash
$ cd submodules/LucasKanade-HornSchunck
$ python HornSchunck.py data/box/box
```

* Farneback
```bash
$ cd scripts
$ python farneback.py
```

* Lucas Kanade
```bash
$ cd scripts
$ python lucas_kanade.py
```

## Sources
* [Tracking video](https://github.com/akshaychawla/Optical-Flow-Tracking----OpenCV)
* [Farneback et Lucas Kanade](https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_video/py_lucas_kanade/py_lucas_kanade.html)
* [Horn Schunk](https://github.com/scienceopen/Optical-Flow-LucasKanade-HornSchunck.git)


## Note
N'oubliez pas de récupérer les submodules à l'aide des commandes:
```
$ git submodule init
$ git submodule update
```
