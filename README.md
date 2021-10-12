# SlicerCryoablationMonitoring



# Installation

The module depends on the folloing python modules:

- MONAI

If Slicer fails to load the module due to missing python moduels, install them using the following command from the Python interactor:

~~~~
>>> import os
>>> os.system('PythonSlicer -m pip install <module name>')
~~~~

The MONAI depends on several other python modules. To install all required modules, run the following commands from the terminal:

~~~~
$ cd <working directory>
$ git clone https://github.com/Project-MONAI/MONAI.git
~~~~

Then, from the Python interactor in 3D Slicer:

~~~~
>>> import os
>>> os.system('PythonSlicer -m pip install -r <working directory>/requirements-dev.txt')
~~~~

