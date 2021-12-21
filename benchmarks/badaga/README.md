# CoRePooL-Badaga


## Download - Repo
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

## Download Corpus
```
cd benchmarks/badaga/
gdown --id 1nOeEsCAqwDbjJVMeT8rvHRs8u4yfozrO
unzip Badaga_Corpus-v.0.1.0.zip
rm -r Badaga_Corpus-v.0.1.0.zip
```

## Benchmarking

| Task | Fine Tuning<br>Notebook | Pre-trained<br>Models |
|:---:|:---:|:---:|
| Text-to-Speech | [Link](notebooks/text-to-speech.ipynb) | [Male](https://drive.google.com/file/d/1ivBb1o2D41sBTLaUo-fRBHf4LylKIE3u/view?usp=sharing)<br>[Female](https://drive.google.com/file/d/1s6keRTHgp_Wuzh3pxArSk3BngFWPOp0D/view?usp=sharing) |
| Speech-to-Text | [Link](notebooks/speech-to-text.ipynb) | [Link](https://drive.google.com/file/d/1zL7JBttmErqXeTd75AL6LnoULaq3r30e/view?usp=sharing) |
| Gender-Identification | [Link](notebooks/gender-identification.ipynb) | [Link](https://drive.google.com/file/d/1WEgfm59Wi7qMt1dclQcRedaJyYDJg9tv/view?usp=sharing) |
| Speaker-Identification | [Link](notebooks/speaker-identification.ipynb) | [Link](https://drive.google.com/file/d/1Cz2w_Gdmup4FF2zHdFZv6-k0tX4QxlsT/view?usp=sharing) |
| Translation | [Link](notebooks/text-translation.ipynb) | [Badaga to English](https://drive.google.com/file/d/1oM8ODJTTz8866MheAJbjoggaCNhQriwM/view?usp=sharing)<br>[English to Badaga](https://drive.google.com/file/d/1gXRXfAx3f1mrd3y0eMg-9OYSdJjS6H5S/view?usp=sharing) |