# onnx_examples
Sample onnx files for testing ezkl libraries.  

If you want to add a model to `examples`, open a PR creating a new folder within `examples` with a descriptive model name. This folder should contain: 
- a `.json` input file, with the fields expected by the  [ezkl](https://github.com/zkonduit/ezkl) cli. 
- a `.onnx` file representing the trained model 
- a `.py` file for generating the `.json` and `.onnx` files following the general structure of `examples/tutorial/tutorial.py`.


TODO: add associated python files in the onnx model directories. 