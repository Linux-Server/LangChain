# How to Activate conda in MAc M1
- source ~/.zshrc
- conda --version

1. Activate Conda
 - conda init zsh
 - source ~/.zshrc
 - conda info

2. Create a New Environment with diffrenet python version:
 - conda create -n myenv python=3.11
 - conda activate myenv
 - conda deactivate

3. Lits all condas
 - conda env list

4. Save all dependeies to requirements.txt file
 - conda env export > environment.yml
5. The environment.yml file can later be used to recreate the exact environment
 - conda env create -f environment.yml





