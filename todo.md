
# Install for Tensorflow (2019. 02. 23)
 - python 3.7.2 install : ok 
   -[python and pip3 path update](http://doocong.com/python/python-pip-install/)
 - windows 10 MAX_PATH issue resolve : ok
   run gpedit.msc (Local Group Policy Editor) 
   Computer Configuration -> Admin Templates -> System -> FileSystem: 
   -> Enable Win32 long paths
 - Install bazel 0.22 for windows x86_64 :ok 
 - Install Cuda Toolkit
   check CUDA_PATH : ok
 - Install cuDNN donwload & install :ok
   [install method](https://medium.com/@akshaysin_86681/installing-cuda-and-cudnn-on-windows-10-f735585159f7)

 - Install git for windows 10 : ok
 - cloning tensorflow 
   git clone https://github.com/tensorflow/tensorflow.git
 - configure path for python after install python 3.7.2 : ok
 - Microsoft visual studio 2015 update 3 build tool 설치 


## Use of python in Visual studio code 
 - install python 
 - configure python path and pip3 path 
 - install pylint as follows 

```
  $ pip3 install pylint

```

## install scipy 
 ```
   $ pip3 install scipy
```

## install matplotlib
```
   $ pip3 install matplotlib
```

## install scikit-learn
```
   $ pip3 install -U scikit-learn
```
