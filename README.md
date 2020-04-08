# python-machine-learning

## environment
- [macOS 10.15.4](https://www.apple.com/tw/macos/catalina/)
- [PyCharm 2019.3.4](https://www.jetbrains.com/pycharm/)
- [Python 3.7.6](https://www.python.org/)
- [scikit-learn 0.22.2](https://github.com/scikit-learn/scikit-learn)
- [TensorFlow 2.1.0](https://www.tensorflow.org/)

## [Pipenv](https://github.com/pypa/pipenv)
```shell
$ pipenv install
```

## virtual env
```shell
$ python -m venv .venv

# macOS
$ source ./.venv/bin/activate
# Winodws
$ .\.venv\Scripts\activate.bat

$ deactivate
```

### requirements.txt
```shell
$ pip freeze > requirements.txt
$ pip install -r requirements.txt
```