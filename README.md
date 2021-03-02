Conde environment YAML files

$ wget https://raw.githubusercontent.com/lukegriffiths/conda-environments/master/{env_name}.yml -O environment.yml
$ conda env create -f environment.yml # first install
$ conda env update -f environment.yml #to update
$ source activate {env_name}

Or in same folder
$ conda env create -f environment.yml