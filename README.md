# MusicVAE

Groove MIDI Dataset과 MusicVAE 모델을 활용하여 midi data generation

dataset : https://magenta.tensorflow.org/datasets/groove
paper : https://arxiv.org/pdf/1803.05428.pdf

# Code Structure
```
MusicVAE
├── groove : train data(.mid)
├── tfrec : preprocessed data(.tfrec)
├── train : trained checkpoints
├── sample.mid : generated midi file
└── musicVAE.ipynb
```
