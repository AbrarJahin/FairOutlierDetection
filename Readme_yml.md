# Comment Classifire

## Install Required Packages in Virtual Environment

```console

conda env remove -n outlier -y
conda env create -f environment.yml
conda env update --file environment.yml
activate outlier
#deactivate
```

If any error occures-

    conda install -y -n outlier -c conda-forge  scikit-learn==0.22.0 pandas==1.0.3 numpy=1.14.6
    conda install -y -n outlier -c pytorch pytorch==1.7.0 torchvision==0.8.0 torchaudio==0.7.0 cudatoolkit=10.1

## Run The Python Version-

Activate the environment by running any of the commands-

    C:\tools\miniconda3\envs\outlier\python.exe

or

    conda activate outlier
    python

After activation, to deactivate, run this command-

    conda deactivate
