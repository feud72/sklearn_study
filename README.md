# sklearn_study

파이썬 라이브러리를 활용한 머신러닝 학습 자료 정리

## How to Install Jupyter Notebook Environment on Android

```bash
$ pkg install curl

$ curl -L https://its-pointless.github.io/setup-pointless-repo.sh | sh

$ apt install python clang fftw

$ apt install freetype libpng pkg-config

$ apt install libzmq

$ pkg install numpy scipy

$ pip install --upgrade pip # Could probably be omitted

$ pip install pandas matplotlib jupyter
```

And cython and statsmodels are kind of annoying:

```bash
$ LDFLAGS=" -liconv" pip install cython 

$ apt install git 

$ git clone git://github.com/statsmodels/statsmodels.git 
```

You may also install other packages such as scikit-learn via Termux, but need some tricks:

```bash
$ pkg install proot 

$ termux-chroot 

$ pip install scikit-learn
```

