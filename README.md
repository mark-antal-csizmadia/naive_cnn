# naive_cnn
Naive implementation of Convolution Neural Networks (CNNs). Example architecture LeNet5 on MNIST hand-written digits.

# Get it running by following the steps below:
1. Make sure you have Anaconda and Git installed on your machine.
2. Go to your desired directory, open your terminal of choice and clone the directory to your local machine: git clone https://github.com/mark-antal-csizmadia/naive_cnn.git
3. Open the Anaconda prompt in the naive_cnn directory, and recreate the naive_cnn_env virtual environment: conda env create -f naive_cnn_env.yml
5. Still in the Anaconda prompt, make sure that the naive_cnn_env virtual environment has been created: conda info --envs
6. Still in the Anaconda prompt, make the naive_cnn_env virtual environment available for 
Jupyter Notebook as a kernel: python -m ipykernel install --user --name naive_cnn_env --display-name "Python (naive_cnn_env)"
7. Still in the Anaconda prompt, open up the naive_cnn.ipynb: jupyter notebook naive_cnn.ipynb
8. Make sure that the kernel is set to the naive_cnn_env kernel via selecting Kernel>Change kernel...>Python (naive_cnn_env)
9. Happy playing!

# Issues.
None.
