# reinforcement-learning-demos

# ERRORS during installations or runing 

# 1: ModuleNotFoundError: No module named 'tensorflow.contrib'
    this is because tensorfow version 2 not contain tenserflow.contrib

    solved : you have to run command `pip install "tensorflow>=1.15,<2.0"`


# 2: ImportError: cannot import name 'PPO1'
    if you rum ppo agent you need some pacages cmake and etc you can check here
    https://stable-baselines.readthedocs.io/en/master/guide/install.html

    if you are on linux you these commands

    $ sudo apt-get update && sudo apt-get install cmake libopenmpi-dev python3-dev zlib1g-dev

    $ pip install stable-baselines[mpi]
    
