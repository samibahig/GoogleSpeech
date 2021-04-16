Google Speech Command v0.02 Dataset

This folder contains recipes for command recognition with Google Speech Command Dataset. The recipes supports 12 or 35 commands. To run it, please type:

python train.py hparams/xvect.yaml --data_folder=/path_to_/GSC (V12 task)

python train.py hparams/xvect.yaml --data_folder=/path_to_/GSC --seed=1234 --number_of_commands=35 --percentage_unknown=0 --percentage_silence=0 (v35 task)

The Dataset can be downloaded at the following drop-box link: https://www.dropbox.com/s/js7jo5ydz4os34s/covidData.tar.gz?dl=0, we will make modifications to our selections of data. Right-now we only use 2400 covid postive samples and 2400 covid negative samples. More techniques to follow.
