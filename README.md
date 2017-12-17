# DeepLeanirngJazz
Artificial Untelligence Lesson Final Project

I  edited it so that it can run in Python3 and edited some parts in algorithm.
Added MidiPlayer4.


### Dependencies


* [tensorflow](https://www.tensorflow.org/install/install_windows)
* [Keras](http://keras.io/#installation)
* [Theano](http://deeplearning.net/software/theano/install.html#bleeding-edge-install-instructions) ("bleeding-edge" version on GitHub)
* [music21](http://web.mit.edu/music21/doc/installing/index.html)

### Instructions

Run on CPU with command:  
```
python generator.py [# of epochs]
```

Run on GPU with command:  
```
THEANO_FLAGS=mode=FAST_RUN,device=gpu,floatX=float32 python generator.py [# of epochs]
```

Note: running Keras/Theano on GPU is formally supported for only NVIDIA cards (CUDA backend).

Note: `preprocess.py` must be modified to work with other MIDI files (the relevant "melody" MIDI part needs to be selected). The ability to handle this natively is a planned feature.

### Author



###----------------------------------------------------------------###

deepjazz was created by Ji-Sung Kim in the spring of 2016.

Original Author:    Ji-Sung Kim
Date of creation:   April 1, 2016
Code license:       Apache License 2.0

###----------------------------------------------------------------###
