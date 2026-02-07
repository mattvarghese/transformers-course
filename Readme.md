# Transformers Course

## Setup
As done on Ubuntu 25.10

**Course link**  
https://huggingface.co/learn/llm-course/chapter0/1

### Environment setup

```bash
$ mkdir transformers-course
$ cd transformers-course

# ffmpeg is required for speech recognition
$ sudo apt install python3-venv ffmpeg
$ python3 -m venv .env
$ source .env/bin/activate

$ which python
```

### Install dependencies
```bash
$ pip install --upgrade pip
$ pip config set global.extra-index-url https://download.pytorch.org/whl/cpu
$ pip install transformers torch
# pillow is required by image classification tasks
$ pip install pillow
```

### Optionally symlink model_store
```bash
$ ln -s /path/to/model_store ./model_store
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

## Attribution

Portions of this project are based on the
[Hugging Face Course](https://huggingface.co/course) (© 2022 Hugging Face),
licensed under the Apache License 2.0.
