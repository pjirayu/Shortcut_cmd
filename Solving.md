in case of version less than or equal to 0.4
//massage
no module named 'Torch'
//Sol.
I solved the problem - first, "downgrading" python from 3.8.0 to 3.7.3 because I checked in PyTorch's chat environment that PyTorch is not yet compatible with python 3.8.0 - and then, after removing everything already installed, installing the latest version of PyTorch via cunda, as you kindly explained
