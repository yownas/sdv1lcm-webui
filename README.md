sdv1lcm-webui

Minimal webui for SDv1 models with the LCM LoRA

# Installation

Create a venv and install requirements.

Install python from here (https://www.python.org/downloads/) (Tested with version 3.10). Download this repo with git (recommended) or as a 
zip file (links in the green "Code" button at the top of the page). Open a cmd (Windows) or bash (Linux) prompt and go to the folder contai
ning the webui and create a virtual env for python.

`python -m venv venv`

Activate it.

`source venv/bin/activate` (Linux) or `source venv\Scripts\activate.bat` (Windows)

Install pytorch from (https://pytorch.org). Select Stable, your OS, Pip, Python and compute platform that match your computer.

Install the rest of the requirements.

`pip install -r requirements.txt`

# Launch

Activate venv if you haven't done it.

`source venv/bin/activate` (Linux) or `source venv\Scripts\activate.bat` (Windows)

`python webui.py --model <path to model, ckpt or safetensors>`

Go to (http://localhost:7860)

