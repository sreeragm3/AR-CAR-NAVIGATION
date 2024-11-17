## AR CAR NAVIGATION


The Project
---

The purpose of this project is to create an AR navigation system for cars. In this system we aim to create a sytem which takes destination as input, it will then calculate the gps coordinates between the current location and destination, create an AR arrow overlay which will superimpose on windsheild for navigation.

## Usage:

### 1. Set up the environment 
`conda env create -f environment.yml`

To activate the environment:

Window: `conda activate carnd`

Linux, MacOS: `source activate carnd`

### 2. Run the pipeline:
```bash
python main.py INPUT_IMAGE OUTPUT_IMAGE_PATH
python main.py --video INPUT_VIDEO OUTPUT_VIDEO_PATH
```
