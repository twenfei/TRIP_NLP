# Final Project for EECS 595: Natural Langurage Processing
Wenfei Tang, Juejue Wang

Please see the uploaded EECS595_Final_Project.pdf for a detailed report.
Please see the link below for the original paper and code by Shane Storks:
https://github.com/sled-group/Verifiable-Coherent-NLU

### Setting up the environment

#### Part 1: use requirements.txt to create a conda environment
```
conda create --name test_env --file requirements.txt
conda activate test_env
python -m spacy download en_core_web_sm
pip install smart-open mkl-random torch huggingface-hub smart-open mkl-fft
```

#### Part 2: install the environment into jupyter (http://echrislynch.com/2019/02/01/adding-an-environment-to-jupyter-notebooks/)
```
pip install ipykernel
ipython kernel install --user --name=test_env
```
#### Part 3: activate your conda environment
```
conda activate test_env
```

#### Description
See Verifiable-Coherent-NLU.ipynb and Visualization folder for our code.
