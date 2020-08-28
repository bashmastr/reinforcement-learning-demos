# reinforcement-learning-demos

# ERRORS during installations or runing 

# 1: ModuleNotFoundError: No module named 'tensorflow.contrib'
    this is because tensorfow version 2 not contain tenserflow.contrib

    solved : you have to run command `pip install "tensorflow>=1.15,<2.0"`
