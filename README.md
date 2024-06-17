# llama3fun

This project requires python >= 3.10. 
* You can install it on Ubuntu with: `$ sudo apt install python3.10`

* or on Mac with: `$ brew install python@3.10`

Once this is done, clone the repo and cd into it:

`$ git clone https://github.com/dlob6/llama3fun.git && cd llama3fun`

Create a python virtual environment:

`$ python3 -m venv .venv`

Activate it:

`$ source .venv/bin/activate`

Go to https://pytorch.org/get-started/locally/ and select the pytorch version compatible with your machine.
* E.G. using GPU on Linux: `$ pip3 install torch torchvision torchaudio`

* Using a CPU on Linux: `$ pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cpu`

* Using a Macbook:  `$ pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cpu`

Install other libraries used in this repo

`$ pip install notebook transformers peft huggingface_hub`

Go to https://huggingface.co/meta-llama/Meta-Llama-3-8B-Instruct, create an account, and request access to the Llama3 weights to Meta.

Go to https://huggingface.co/settings/tokens to get your api key, enter it in huggingface_hub via

`$ huggingface-cli login` 

Launch jupyter notebook:

`$ jupyter notebook`

Then open the notebook `llama3fun.ipynb` and enjoy.





