# TDT4259 - Applied Data Science

## The process

The notebooks are numbered in roughly the order they were created. This gives the reader a sense of the process we went through when creating the project.

## The data

The data checkpoints are stored in the `data` directory. Raw, cleaned, processed and final data are stored in respective subdirectories.

## Running the code

### Prerequisites for running the code

You can install dependencies however you like. However, it is recommended to use `conda`, as it comes with a lot of useful packages pre-installed. Read more about `conda` [here](https://docs.conda.io/en/latest/).

### Installing dependencies

```sh
# Navigate to the project directory
cd tdt4259-aneo

# Create a new conda environment
conda create --name tdt4259

# Activate the environment
conda activate tdt4259

# Install dependencies
conda install --file requirements.txt
```

### Executing the code

It is recommended to run the Jupyter Notebook in VSCode. Ensure the `tdt4259` conda environment is selected as the Python interpreter.
