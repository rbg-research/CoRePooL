# CoRePooL-Badaga


## Getting the Repo
```
git clone https://github.com/rbg-research/CoRePooL.git
cd CorePool
```


## Environment Setup

```
sudo apt-get install python3.8
sudo apt-get install python3.8-dev
wget https://bootstrap.pypa.io/get-pip.py
python3.8 get-pip.py
rm -r get-pip.py
pip3.8 install -U pip
mkdir $HOME/environments
pip3.8 install -U virtualenv
virtualenv ~/environments/corepool
source ~/environments/corepool/bin/activate
pip install -r requirements.txt
```

## Getting Corpus
```
cd benchmarks/badaga/
gdown --id 1nOeEsCAqwDbjJVMeT8rvHRs8u4yfozrO
unzip Badaga_Corpus-v.0.1.0.zip
rm -r Badaga_Corpus-v.0.1.0.zip
```

## Benchmarking

| Task | Fine Tuning<br>Notebook | Pre-trained<br>Models |
|:---:|:---:|:---:|
| Text-to-Speech | [Link](notebooks/text-to-speech.ipynb) | [Male]()<br>[Female]() |
| Speech-to-Text | [Link](notebooks/speech-to-text.ipynb) | [Link]() |
| Gender-Identification | [Link](notebooks/gender-identification.ipynb) | [Link]() |
| Speaker-Identification | [Link](notebooks/speaker-identification.ipynb) | [Link]() |
| Translation | [Link](notebooks/text-translation.ipynb) | [Badaga to English]()<br>[English to Badaga]() |