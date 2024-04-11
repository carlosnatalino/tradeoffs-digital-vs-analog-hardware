# Performance Tradeoffs of General-Purpose Digital Hardware and Application-Specific Analog Hardware

Data and plots used in the publication and presentation at the 2024 SPIE Photonics Europe (EPE24).

__Authors:__ Carlos Natalino, Dan Li, Oskars Ozolins, Xiaodan Pang, and Francesco Da Ros

## References and sources of data

The data used for general-purpose GPUs has been colected from https://epochai.org/blog/trends-in-machine-learning-hardware

Data from neuromorphic processors has been collected from https://github.com/areuther/ai-accelerators/blob/main/peak_2023.md

The complete list of references can be found in the manuscript. The authors' version will be published soon.

## Plots

The code used to generate the plots can be found in the [plots.ipynb](plots.ipynb) file.

## Installation

To reproduce the results, you need to install the dependencies following the instructions:

1. Create a virtual environment

```bash
python3.12 -m venv .venv
```

2. Activate the virtual environment

```bash
source .venv/bin/activate
```

3. Update and install pip-tools

```bash
pip3 install -U pip pip-tools
```

4. Compile the list of dependencies

```bash
pip-compile requirements.in
```

5. Install the dependencies

```bash
pip install -r requirements.txt
```

The version with which the results were created is available in the `requirements.txt` file.
