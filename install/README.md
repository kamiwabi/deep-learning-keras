# Instalasi Keras

```
» pip install keras
Collecting keras
  Downloading https://files.pythonhosted.org/packages/5e/10/aa32dad071ce52b5502266b5c659451cfd6ffcbf14e6c8c4f16c0ff5aaab/Keras-2.2.4-py2.py3-none-any.whl (312kB)
    100% |████████████████████████████████| 317kB 528kB/s
Collecting scipy>=0.14 (from keras)
  Using cached https://files.pythonhosted.org/packages/a8/0b/f163da98d3a01b3e0ef1cab8dd2123c34aee2bafbb1c5bffa354cc8a1730/scipy-1.1.0-cp36-cp36m-manylinux1_x86_64.whl
Collecting numpy>=1.9.1 (from keras)
  Downloading https://files.pythonhosted.org/packages/ff/7f/9d804d2348471c67a7d8b5f84f9bc59fd1cefa148986f2b74552f8573555/numpy-1.15.4-cp36-cp36m-manylinux1_x86_64.whl (13.9MB)
    100% |████████████████████████████████| 13.9MB 379kB/s
Collecting keras-preprocessing>=1.0.5 (from keras)
  Downloading https://files.pythonhosted.org/packages/fc/94/74e0fa783d3fc07e41715973435dd051ca89c550881b3454233c39c73e69/Keras_Preprocessing-1.0.5-py2.py3-none-any.whl
Collecting keras-applications>=1.0.6 (from keras)
  Downloading https://files.pythonhosted.org/packages/3f/c4/2ff40221029f7098d58f8d7fb99b97e8100f3293f9856f0fb5834bef100b/Keras_Applications-1.0.6-py2.py3-none-any.whl (44kB)
    100% |████████████████████████████████| 51kB 466kB/s
Collecting pyyaml (from keras)
Collecting six>=1.9.0 (from keras)
  Using cached https://files.pythonhosted.org/packages/67/4b/141a581104b1f6397bfa78ac9d43d8ad29a7ca43ea90a2d863fe3056e86a/six-1.11.0-py2.py3-none-any.whl
Collecting h5py (from keras)
  Downloading https://files.pythonhosted.org/packages/8e/cb/726134109e7bd71d98d1fcc717ffe051767aac42ede0e7326fd1787e5d64/h5py-2.8.0-cp36-cp36m-manylinux1_x86_64.whl (2.8MB)
    100% |████████████████████████████████| 2.8MB 256kB/s
Installing collected packages: numpy, scipy, six, keras-preprocessing, h5py, keras-applications, pyyaml, keras
Successfully installed h5py-2.8.0 keras-2.2.4 keras-applications-1.0.6 keras-preprocessing-1.0.5 numpy-1.15.4 pyyaml-3.13 scipy-1.1.0 six-1.11.0
```

Install back-end (TensorFlow):

```
» pip install tensorflow                                                                          (/opt/software/python-dev-tools/py36) 
Collecting tensorflow
  Downloading https://files.pythonhosted.org/packages/22/cc/ca70b78087015d21c5f3f93694107f34ebccb3be9624385a911d4b52ecef/tensorflow-1.12.0-cp36-cp36m-manylinux1_x86_64.whl (83.1MB)
    100% |████████████████████████████████| 83.1MB 268kB/s 
Collecting tensorboard<1.13.0,>=1.12.0 (from tensorflow)
  Downloading https://files.pythonhosted.org/packages/e0/d0/65fe48383146199f16dbd5999ef226b87bce63ad5cd73c840cf722637969/tensorboard-1.12.0-py3-none-any.whl (3.0MB)
    100% |████████████████████████████████| 3.1MB 1.1MB/s 
Requirement already satisfied: six>=1.10.0 in /opt/software/python-dev-tools/py36/lib/python3.6/site-packages (from tensorflow) (1.11.0)
Collecting protobuf>=3.6.1 (from tensorflow)
  Downloading https://files.pythonhosted.org/packages/c2/f9/28787754923612ca9bfdffc588daa05580ed70698add063a5629d1a4209d/protobuf-3.6.1-cp36-cp36m-manylinux1_x86_64.whl (1.1MB)
    100% |████████████████████████████████| 1.1MB 927kB/s 
Collecting absl-py>=0.1.6 (from tensorflow)
  Downloading https://files.pythonhosted.org/packages/0c/63/f505d2d4c21db849cf80bad517f0065a30be6b006b0a5637f1b95584a305/absl-py-0.6.1.tar.gz (94kB)
    100% |████████████████████████████████| 102kB 1.5MB/s 
Collecting termcolor>=1.1.0 (from tensorflow)
  Downloading https://files.pythonhosted.org/packages/8a/48/a76be51647d0eb9f10e2a4511bf3ffb8cc1e6b14e9e4fab46173aa79f981/termcolor-1.1.0.tar.gz
Collecting gast>=0.2.0 (from tensorflow)
  Downloading https://files.pythonhosted.org/packages/5c/78/ff794fcae2ce8aa6323e789d1f8b3b7765f601e7702726f430e814822b96/gast-0.2.0.tar.gz
Collecting grpcio>=1.8.6 (from tensorflow)
  Downloading https://files.pythonhosted.org/packages/0e/4f/e9e84e4600c43cae7ce58489c6e73ff4c864557bc4d4d0f0029c79e07f31/grpcio-1.16.1-cp36-cp36m-manylinux1_x86_64.whl (9.7MB)
    100% |████████████████████████████████| 9.7MB 723kB/s 
Requirement already satisfied: wheel>=0.26 in /opt/software/python-dev-tools/py36/lib/python3.6/site-packages (from tensorflow) (0.32.3)
Requirement already satisfied: keras-applications>=1.0.6 in /opt/software/python-dev-tools/py36/lib/python3.6/site-packages (from tensorflow) (1.0.6)
Requirement already satisfied: numpy>=1.13.3 in /opt/software/python-dev-tools/py36/lib/python3.6/site-packages (from tensorflow) (1.15.4)
Collecting astor>=0.6.0 (from tensorflow)
  Downloading https://files.pythonhosted.org/packages/35/6b/11530768cac581a12952a2aad00e1526b89d242d0b9f59534ef6e6a1752f/astor-0.7.1-py2.py3-none-any.whl
Requirement already satisfied: keras-preprocessing>=1.0.5 in /opt/software/python-dev-tools/py36/lib/python3.6/site-packages (from tensorflow) (1.0.5)
Collecting werkzeug>=0.11.10 (from tensorboard<1.13.0,>=1.12.0->tensorflow)
  Using cached https://files.pythonhosted.org/packages/20/c4/12e3e56473e52375aa29c4764e70d1b8f3efa6682bef8d0aae04fe335243/Werkzeug-0.14.1-py2.py3-none-any.whl
Collecting markdown>=2.6.8 (from tensorboard<1.13.0,>=1.12.0->tensorflow)
  Downloading https://files.pythonhosted.org/packages/7a/6b/5600647404ba15545ec37d2f7f58844d690baf2f81f3a60b862e48f29287/Markdown-3.0.1-py2.py3-none-any.whl (89kB)
    100% |████████████████████████████████| 92kB 1.4MB/s 
Requirement already satisfied: setuptools in /opt/software/python-dev-tools/py36/lib/python3.6/site-packages (from protobuf>=3.6.1->tensorflow) (40.6.2)
Requirement already satisfied: h5py in /opt/software/python-dev-tools/py36/lib/python3.6/site-packages (from keras-applications>=1.0.6->tensorflow) (2.8.0)
Building wheels for collected packages: absl-py, termcolor, gast
  Running setup.py bdist_wheel for absl-py ... done
  Stored in directory: /home/bpdp/.cache/pip/wheels/18/ea/5e/e36e1b8739e78cd2eba0a08fdc602c2b16a4b263912af8cb64
  Running setup.py bdist_wheel for termcolor ... done
  Stored in directory: /home/bpdp/.cache/pip/wheels/7c/06/54/bc84598ba1daf8f970247f550b175aaaee85f68b4b0c5ab2c6
  Running setup.py bdist_wheel for gast ... done
  Stored in directory: /home/bpdp/.cache/pip/wheels/9a/1f/0e/3cde98113222b853e98fc0a8e9924480a3e25f1b4008cedb4f
Successfully built absl-py termcolor gast
Installing collected packages: werkzeug, grpcio, protobuf, markdown, tensorboard, absl-py, termcolor, gast, astor, tensorflow
Successfully installed absl-py-0.6.1 astor-0.7.1 gast-0.2.0 grpcio-1.16.1 markdown-3.0.1 protobuf-3.6.1 tensorboard-1.12.0 tensorflow-1.12.0 termcolor-1.1.0 werkzeug-0.14.1
```
