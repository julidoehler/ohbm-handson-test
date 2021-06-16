## OHBM Hackathon 2021 TrainTrack Session - Reproducible Workflows

### Context:
What it is about

### How to get this content

### Data description

### How to install the required packages:

It can be useful to install the required packages in a virtual environment (virtualenv, miniconda).

```
conda create -n user-test python=3.6
# some stuff will happen
conda activate user-test
```

First install the packages with 'pip' after navigating to the repo root folder

```
pip install -r requierements.txt
```

Then install the BrainStat package:

```
git clone https://github.com/MICA-MNI/BrainStat.git
cd BrainStat
python3 setup.py build
python3 setup.py install
```

### How to run the analysis

Navigate to the code folder then run:

```
cd code
python3 analysis_01.py
```
