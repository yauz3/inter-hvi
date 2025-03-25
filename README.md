# Inter-HVI: Bridging Interpretability and Accuracy in Hypervalent Iodine Reactivity Prediction

# Reference Implementation of Inter-POL algorithm
This readme file documents all of the required steps to run Inter-POL.

Note that the code was implemented and tested on a Linux operating system only.

## How to set up the environment
We have provided an Anaconda environment file for easy setup.
If you do not have Anaconda installed, you can get Miniconda from [here](https://docs.conda.io/en/latest/miniconda.html).
Create the `kat_env-env` environment using the following command:
```bash
conda env create -n kat_env -f environment.yml
conda activate kat_env
```

# In order to install requirement packages
```bash
pip install -r requirements.txt
```

# Step by step files:

1_read_SMILES_to_features: prepare features

2_rulefit_training_and_test: train and test the model


## License

This project is licensed for **academic and research purposes only**. For commercial usage, please connect with s.yavuz.ugurlu@gmail.com
