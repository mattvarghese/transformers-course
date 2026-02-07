# Transformers Course

## Setup
As done on Ubuntu 25.10

**Course link**  
https://huggingface.co/learn/llm-course/chapter0/1

### Environment setup

```bash
$ mkdir transformers-course
$ cd transformers-course

$ sudo apt install python3-venv
$ python3 -m venv .env
$ source .env/bin/activate

$ which python
```

### Install dependencies
```bash
$ pip install --upgrade pip
$ pip config set global.extra-index-url https://download.pytorch.org/whl/cpu
$ pip install "transformers[sentencepiece]" torch
```

### Start JupyterLab
```bash
$ pip install ipywidgets jupyterlab
$ jupyter lab
```

### Closing out of JupyterLab
1. Close the Browser
2. CTRL+C and confirm to exit the `jupyter lab` command
 
### Exiting the virtual environment
```bash
$ deactivate
```
