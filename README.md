# MiniTorch Module 3

## Simple
![Simple_CPU](img/simple_cpu.png "Simple CPU")

![Simple_GPU](img/simple_gpu.png "Simple GPU")


## Split
![Split_CPU](img/split_cpu.png "Split CPU")

![Split_GPU](img/split_gpu.png "Split GPU")


## XOR
![XOR_CPU](img/xor_cpu.png "XOR CPU")

![XOR_GPU](img/xor_gpu.png "XOR GPU")


## Bigger XOR
![Bigger_XOR_CPU](img/bigger_xor_cpu.png "Bigger XOR CPU")

![Bigger_XOR_GPU](img/bigger_xor_gpu.png "Bigger XOR GPU")

<img src="https://minitorch.github.io/minitorch.svg" width="50%">

* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module3.html


You will need to modify `tensor_functions.py` slightly in this assignment.

* Tests:

```
python run_tests.py
```

* Note:

Several of the tests for this assignment will only run if you are on a GPU machine and will not
run on github's test infrastructure. Please follow the instructions to setup up a colab machine
to run these tests.

This assignment requires the following files from the previous assignments. You can get these by running

```bash
python sync_previous_module.py previous-module-dir current-module-dir
```

The files that will be synced are:

        minitorch/tensor_data.py minitorch/tensor_functions.py minitorch/tensor_ops.py minitorch/operators.py minitorch/scalar.py minitorch/scalar_functions.py minitorch/module.py minitorch/autodiff.py minitorch/module.py project/run_manual.py project/run_scalar.py project/run_tensor.py minitorch/operators.py minitorch/module.py minitorch/autodiff.py minitorch/tensor.py minitorch/datasets.py minitorch/testing.py minitorch/optim.py