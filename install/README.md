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

Tools:

Jupyter

```
» pip install jupyter                                                                             (/opt/software/python-dev-tools/py36)
Collecting jupyter
  Downloading https://files.pythonhosted.org/packages/83/df/0f5dd132200728a86190397e1ea87cd76244e42d39ec5e88efd25b2abd7e/jupyter-1.0.0-py2.py3-none-any.whl
Collecting jupyter-console (from jupyter)
  Downloading https://files.pythonhosted.org/packages/cb/ee/6374ae8c21b7d0847f9c3722dcdfac986b8e54fa9ad9ea66e1eb6320d2b8/jupyter_console-6.0.0-py2.py3-none-any.whl
Collecting ipywidgets (from jupyter)
  Downloading https://files.pythonhosted.org/packages/30/9a/a008c7b1183fac9e52066d80a379b3c64eab535bd9d86cdc29a0b766fd82/ipywidgets-7.4.2-py2.py3-none-any.whl (111kB)
    100% |████████████████████████████████| 112kB 1.0MB/s
Collecting ipykernel (from jupyter)
  Downloading https://files.pythonhosted.org/packages/d8/b0/f0be5c5ab335196f5cce96e5b889a4fcf5bfe462eb0acc05cd7e2caf65eb/ipykernel-5.1.0-py3-none-any.whl (113kB)
    100% |████████████████████████████████| 122kB 1.8MB/s
Collecting qtconsole (from jupyter)
  Downloading https://files.pythonhosted.org/packages/e0/7a/8aefbc0ed078dec7951ac9a06dcd1869243ecd7bcbce26fa47bf5e469a8f/qtconsole-4.4.3-py2.py3-none-any.whl (113kB)
    100% |████████████████████████████████| 122kB 1.9MB/s
Collecting notebook (from jupyter)
  Downloading https://files.pythonhosted.org/packages/a2/5d/d1907cd32ac00b5ead56f6e61d9794fa60ef105a22ac5da6e7556011580f/notebook-5.7.2-py2.py3-none-any.whl (9.0MB)
    100% |████████████████████████████████| 9.0MB 579kB/s
Collecting nbconvert (from jupyter)
  Downloading https://files.pythonhosted.org/packages/b5/bb/94c493051d60e5b9c0f7f9a368b324201818c1b1c4cae85d1e49a41846c7/nbconvert-5.4.0-py2.py3-none-any.whl (405kB)
    100% |████████████████████████████████| 409kB 946kB/s
Collecting pygments (from jupyter-console->jupyter)
  Downloading https://files.pythonhosted.org/packages/fc/41/4f900a7852e25bb9350b4e3ee8c4aba0ee32abefd401456962b25f954823/Pygments-2.3.0-py2.py3-none-any.whl (845kB)
    100% |████████████████████████████████| 849kB 2.1MB/s
Collecting ipython (from jupyter-console->jupyter)
  Downloading https://files.pythonhosted.org/packages/1b/e2/ffb8c1b574f972cf4183b0aac8f16b57f1e3bbe876b31555b107ea3fd009/ipython-7.1.1-py3-none-any.whl (764kB)
    100% |████████████████████████████████| 768kB 2.8MB/s
Collecting jupyter-client (from jupyter-console->jupyter)
  Using cached https://files.pythonhosted.org/packages/94/dd/fe6c4d683b09eb05342bd2816b7779663f71762b4fa9c2d5203d35d17354/jupyter_client-5.2.3-py2.py3-none-any.whl
Collecting prompt-toolkit<2.1.0,>=2.0.0 (from jupyter-console->jupyter)
  Downloading https://files.pythonhosted.org/packages/d1/e6/adb3be5576f5d27c6faa33f1e9fea8fe5dbd9351db12148de948507e352c/prompt_toolkit-2.0.7-py3-none-any.whl (338kB)
    100% |████████████████████████████████| 348kB 1.1MB/s
Collecting nbformat>=4.2.0 (from ipywidgets->jupyter)
  Using cached https://files.pythonhosted.org/packages/da/27/9a654d2b6cc1eaa517d1c5a4405166c7f6d72f04f6e7eea41855fe808a46/nbformat-4.4.0-py2.py3-none-any.whl
Collecting traitlets>=4.3.1 (from ipywidgets->jupyter)
  Using cached https://files.pythonhosted.org/packages/93/d6/abcb22de61d78e2fc3959c964628a5771e47e7cc60d53e9342e21ed6cc9a/traitlets-4.3.2-py2.py3-none-any.whl
Collecting widgetsnbextension~=3.4.0 (from ipywidgets->jupyter)
  Downloading https://files.pythonhosted.org/packages/8a/81/35789a3952afb48238289171728072d26d6e76649ddc8b3588657a2d78c1/widgetsnbextension-3.4.2-py2.py3-none-any.whl (2.2MB)
    100% |████████████████████████████████| 2.2MB 1.2MB/s
Collecting tornado>=4.2 (from ipykernel->jupyter)
  Downloading https://files.pythonhosted.org/packages/e6/78/6e7b5af12c12bdf38ca9bfe863fcaf53dc10430a312d0324e76c1e5ca426/tornado-5.1.1.tar.gz (516kB)
    100% |████████████████████████████████| 522kB 1.9MB/s
Collecting ipython-genutils (from qtconsole->jupyter)
  Using cached https://files.pythonhosted.org/packages/fa/bc/9bd3b5c2b4774d5f33b2d544f1460be9df7df2fe42f352135381c347c69a/ipython_genutils-0.2.0-py2.py3-none-any.whl
Collecting jupyter-core (from qtconsole->jupyter)
  Using cached https://files.pythonhosted.org/packages/1d/44/065d2d7bae7bebc06f1dd70d23c36da8c50c0f08b4236716743d706762a8/jupyter_core-4.4.0-py2.py3-none-any.whl
Collecting jinja2 (from notebook->jupyter)
  Using cached https://files.pythonhosted.org/packages/7f/ff/ae64bacdfc95f27a016a7bed8e8686763ba4d277a78ca76f32659220a731/Jinja2-2.10-py2.py3-none-any.whl
Collecting Send2Trash (from notebook->jupyter)
  Downloading https://files.pythonhosted.org/packages/49/46/c3dc27481d1cc57b9385aff41c474ceb7714f7935b1247194adae45db714/Send2Trash-1.5.0-py3-none-any.whl
Collecting terminado>=0.8.1 (from notebook->jupyter)
  Downloading https://files.pythonhosted.org/packages/2e/20/a26211a24425923d46e1213b376a6ee60dc30bcdf1b0c345e2c3769deb1c/terminado-0.8.1-py2.py3-none-any.whl
Collecting prometheus-client (from notebook->jupyter)
  Downloading https://files.pythonhosted.org/packages/61/84/9aa657b215b04f21a72ca8e50ff159eef9795096683e4581a357baf4dde6/prometheus_client-0.4.2.tar.gz
Collecting pyzmq>=17 (from notebook->jupyter)
  Downloading https://files.pythonhosted.org/packages/48/93/59592cb294761aaa40589b544eaa5175446d687ff95beeeb666de60f3274/pyzmq-17.1.2-cp36-cp36m-manylinux1_x86_64.whl (998kB)
    100% |████████████████████████████████| 1.0MB 1.3MB/s
Collecting pandocfilters>=1.4.1 (from nbconvert->jupyter)
  Using cached https://files.pythonhosted.org/packages/4c/ea/236e2584af67bb6df960832731a6e5325fd4441de001767da328c33368ce/pandocfilters-1.4.2.tar.gz
Collecting bleach (from nbconvert->jupyter)
  Downloading https://files.pythonhosted.org/packages/d4/0d/4696373c3b714f6022d668fbab619690a42050dbeacede6d10ed97fbd3e2/bleach-3.0.2-py2.py3-none-any.whl (148kB)
    100% |████████████████████████████████| 153kB 2.7MB/s
Collecting defusedxml (from nbconvert->jupyter)
  Using cached https://files.pythonhosted.org/packages/87/1c/17f3e3935a913dfe2a5ca85fa5ccbef366bfd82eb318b1f75dadbf0affca/defusedxml-0.5.0-py2.py3-none-any.whl
Collecting mistune>=0.8.1 (from nbconvert->jupyter)
  Downloading https://files.pythonhosted.org/packages/09/ec/4b43dae793655b7d8a25f76119624350b4d65eb663459eb9603d7f1f0345/mistune-0.8.4-py2.py3-none-any.whl
Collecting entrypoints>=0.2.2 (from nbconvert->jupyter)
  Using cached https://files.pythonhosted.org/packages/cc/8b/4eefa9b47f1910b3d2081da67726b066e379b04ca897acfe9f92bac56147/entrypoints-0.2.3-py2.py3-none-any.whl
Collecting testpath (from nbconvert->jupyter)
  Downloading https://files.pythonhosted.org/packages/be/a4/162f9ebb6489421fe46dcca2ae420369edfee4b563c668d93cb4605d12ba/testpath-0.4.2-py2.py3-none-any.whl (163kB)
    100% |████████████████████████████████| 163kB 1.0MB/s
Collecting jedi>=0.10 (from ipython->jupyter-console->jupyter)
  Downloading https://files.pythonhosted.org/packages/7a/1a/9bd24a185873b998611c2d8d4fb15cd5e8a879ead36355df7ee53e9111bf/jedi-0.13.1-py2.py3-none-any.whl (177kB)
    100% |████████████████████████████████| 184kB 2.4MB/s
Requirement already satisfied: setuptools>=18.5 in /opt/software/python-dev-tools/py36/lib/python3.6/site-packages (from ipython->jupyter-console->jupyter) (40.6.2)
Collecting backcall (from ipython->jupyter-console->jupyter)
Collecting decorator (from ipython->jupyter-console->jupyter)
  Using cached https://files.pythonhosted.org/packages/bc/bb/a24838832ba35baf52f32ab1a49b906b5f82fb7c76b2f6a7e35e140bac30/decorator-4.3.0-py2.py3-none-any.whl
Collecting pexpect; sys_platform != "win32" (from ipython->jupyter-console->jupyter)
  Using cached https://files.pythonhosted.org/packages/89/e6/b5a1de8b0cc4e07ca1b305a4fcc3f9806025c1b651ea302646341222f88b/pexpect-4.6.0-py2.py3-none-any.whl
Collecting pickleshare (from ipython->jupyter-console->jupyter)
  Downloading https://files.pythonhosted.org/packages/9a/41/220f49aaea88bc6fa6cba8d05ecf24676326156c23b991e80b3f2fc24c77/pickleshare-0.7.5-py2.py3-none-any.whl
Collecting python-dateutil>=2.1 (from jupyter-client->jupyter-console->jupyter)
  Using cached https://files.pythonhosted.org/packages/74/68/d87d9b36af36f44254a8d512cbfc48369103a3b9e474be9bdfe536abfc45/python_dateutil-2.7.5-py2.py3-none-any.whl
Collecting wcwidth (from prompt-toolkit<2.1.0,>=2.0.0->jupyter-console->jupyter)
  Using cached https://files.pythonhosted.org/packages/7e/9f/526a6947247599b084ee5232e4f9190a38f398d7300d866af3ab571a5bfe/wcwidth-0.1.7-py2.py3-none-any.whl
Requirement already satisfied: six>=1.9.0 in /opt/software/python-dev-tools/py36/lib/python3.6/site-packages (from prompt-toolkit<2.1.0,>=2.0.0->jupyter-console->jupyter) (1.11.0)
Collecting jsonschema!=2.5.0,>=2.4 (from nbformat>=4.2.0->ipywidgets->jupyter)
  Using cached https://files.pythonhosted.org/packages/77/de/47e35a97b2b05c2fadbec67d44cfcdcd09b8086951b331d82de90d2912da/jsonschema-2.6.0-py2.py3-none-any.whl
Collecting MarkupSafe>=0.23 (from jinja2->notebook->jupyter)
  Downloading https://files.pythonhosted.org/packages/08/04/f2191b50fb7f0712f03f064b71d8b4605190f2178ba02e975a87f7b89a0d/MarkupSafe-1.1.0-cp36-cp36m-manylinux1_x86_64.whl
Collecting ptyprocess; os_name != "nt" (from terminado>=0.8.1->notebook->jupyter)
  Using cached https://files.pythonhosted.org/packages/d1/29/605c2cc68a9992d18dada28206eeada56ea4bd07a239669da41674648b6f/ptyprocess-0.6.0-py2.py3-none-any.whl
Collecting webencodings (from bleach->nbconvert->jupyter)
  Using cached https://files.pythonhosted.org/packages/f4/24/2a3e3df732393fed8b3ebf2ec078f05546de641fe1b667ee316ec1dcf3b7/webencodings-0.5.1-py2.py3-none-any.whl
Collecting parso>=0.3.0 (from jedi>=0.10->ipython->jupyter-console->jupyter)
  Using cached https://files.pythonhosted.org/packages/09/51/9c48a46334be50c13d25a3afe55fa05c445699304c5ad32619de953a2305/parso-0.3.1-py2.py3-none-any.whl
Building wheels for collected packages: tornado, prometheus-client, pandocfilters
  Running setup.py bdist_wheel for tornado ... done
  Stored in directory: /home/bpdp/.cache/pip/wheels/6d/e1/ce/f4ee2fa420cc6b940123c64992b81047816d0a9fad6b879325
  Running setup.py bdist_wheel for prometheus-client ... done
  Stored in directory: /home/bpdp/.cache/pip/wheels/b9/96/bc/e2acadc6bbfe57a1f631a34ca4ce6dd057af059b8d6878202b
  Running setup.py bdist_wheel for pandocfilters ... done
  Stored in directory: /home/bpdp/.cache/pip/wheels/39/01/56/f1b08a6275acc59e846fa4c1e1b65dbc1919f20157d9e66c20
Successfully built tornado prometheus-client pandocfilters
Installing collected packages: pygments, ipython-genutils, decorator, traitlets, parso, jedi, backcall, ptyprocess, pexpect, wcwidth, prompt-toolkit, pickleshare, ipython, python-dateutil, tornado, jupyter-core, pyzmq, jupyter-client, ipykernel, jupyter-console, jsonschema, nbformat, MarkupSafe, jinja2, Send2Trash, terminado, prometheus-client, pandocfilters, webencodings, bleach, defusedxml, mistune, entrypoints, testpath, nbconvert, notebook, widgetsnbextension, ipywidgets, qtconsole, jupyter
Successfully installed MarkupSafe-1.1.0 Send2Trash-1.5.0 backcall-0.1.0 bleach-3.0.2 decorator-4.3.0 defusedxml-0.5.0 entrypoints-0.2.3 ipykernel-5.1.0 ipython-7.1.1 ipython-genutils-0.2.0 ipywidgets-7.4.2 jedi-0.13.1 jinja2-2.10 jsonschema-2.6.0 jupyter-1.0.0 jupyter-client-5.2.3 jupyter-console-6.0.0 jupyter-core-4.4.0 mistune-0.8.4 nbconvert-5.4.0 nbformat-4.4.0 notebook-5.7.2 pandocfilters-1.4.2 parso-0.3.1 pexpect-4.6.0 pickleshare-0.7.5 prometheus-client-0.4.2 prompt-toolkit-2.0.7 ptyprocess-0.6.0 pygments-2.3.0 python-dateutil-2.7.5 pyzmq-17.1.2 qtconsole-4.4.3 terminado-0.8.1 testpath-0.4.2 tornado-5.1.1 traitlets-4.3.2 wcwidth-0.1.7 webencodings-0.5.1 widgetsnbextension-3.4.2
```
