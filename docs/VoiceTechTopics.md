# ASR
Deep Speech (Baidu - Silicon Valley AI Lab)
---
* Deep Speech: Scaling up end-to-end speech recognition - [arxiv](http://arxiv.org/abs/1412.5567), [blog](https://devblogs.nvidia.com/parallelforall/deep-speech-accurate-speech-recognition-gpu-accelerated-deep-learning/)
* Deep Speech2: End-to-End Speech Recognition in English and Mandarin - [arxiv](http://arxiv.org/abs/1512.02595)
* Deep Speech3: 
  * Even more end-to-end speech recognition - [research.baidu.com](http://research.baidu.com)
  * Cold Fusion: Training Seq2Seq Models Together with Language Models - arxiv.org/abs/1708.06426

Notable Papers
---
* SpecAugment(2019): A New Data Augmentation Method for Automatic Speech Recognition
* Google AI Blog(2019): An All-Neural On-Device Speech Recognizer - [blog](https://ai.googleblog.com/2019/03/an-all-neural-on-device-speech.html)
* All-Neural (ICASSP2017) : Advances in All-Neural Speech Recognition 
* A2W Model (ICASSP2018): Building competitive direct acoustics-to-word models for English conversational speech recognition - [arxiv](https://arxiv.org/abs/1712.03133)
* Gram-CTC (ICML2017) : Gram-CTC: Automatic Unit Selection and Target Decomposition for Sequence Labelling
* KALDI-ANDROID(interspeech2016): KALDI GOES ANDROID, - [paper](https://www.semanticscholar.org/paper/KALDI-GOES-ANDROID-Gaida-Petrick/bd4a9d6f288875be4de97b3dff20bcba6f6910dc)

Open Source (Libs/Github)
---
  * [kaldi-asr.org](https://kaldi-asr.org/) / [github](https://github.com/kaldi-asr/kaldi)
    * Compile Kaldi for Android(2017) - [github.io](http://jcsilva.github.io/2017/03/18/compile-kaldi-android/)
  * NeuralSP: Neural network based Speech Processing - https://opensourcelibs.com/lib/neural_sp
    * Key features: [giters](https://giters.com/hirofumi0810/neural_sp) (End-to-End ASR/LM implementation with PyTorch, including Conformer) 
  * https://github.com/mozilla/DeepSpeech, https://github.com/PaddlePaddle/DeepSpeech
  * https://github.com/sooftware/openspeech 
  * Hugging Face - [Dataset:librispeech_asr](https://huggingface.co/datasets/librispeech_asr), [wav2vec](https://huggingface.co/facebook/wav2vec2-base), [wav2vec2-base](https://huggingface.co/facebook/wav2vec2-base-960h)


# TTS 
* Deep Voice: Real-time Neural Text-to-Speech - [research.baidu.com](http://research.baidu.com/deep-voice-production-quality-text-speech-system-constructed-entirely-deep-neural-networks/), [arxiv](https://arxiv.org/abs/1702.07825)
* Deep Voice 2: Multi-Speaker Neural Text-to-Speech - [research.baidu.com](http://research.baidu.com/deep-voice-2-multi-speaker-neural-text-speech), [arxiv](https://arxiv.org/abs/1705.08947)
* Deep Voice 3: 2000-Speaker Neural Text-to-Speech - [research.baidu.com](http://research.baidu.com/deep-voice-3-2000-speaker-neural-text-speech/), [arxiv](https://arxiv.org/abs/1710.07654), [reddit](https://www.reddit.com/r/MachineLearning/comments/78goi8/r_deep_voice_3_2000speaker_neural_texttospeech/)
* github 
  * http://carpedm20.github.io/tacotron/
  * https://github.com/devsisters/multi-speaker-tacotron-tensorflow
  * https://github.com/Kyubyong/deepvoice3


SPSS (Statistical Parametric Speech Synthesis) 
---
* Heiga Zen - http://research.google.com/pubs/HeigaZen.html
* Statistical Parametric Speech Synthesis(June 9th, 2014@Google) - [slide](http://static.googleusercontent.com/media/research.google.com/ko//pubs/archive/42624.pdf)
* Acoustic Modeling for Speech Synthesis(Dec. 14th, 2015@ASRU) - [slide](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/44630.pdf)

WaveNet (DeepMind) 
---
* https://deepmind.com/blog/wavenet-generative-model-raw-audio/
* https://redd.it/51sr9t (@hardmaru it takes 90 minutes to synthesize one second of audio) 
* generative models for speech - https://github.com/igul222/speech
* wave2letter - End-to-End ConvNet-based SR system : http://arxiv.org/pdf/1609.03193v2.pdf

Speaker Recognition
---
* ALIZE(opensource platform) - http://alize.univ-avignon.fr
* Deep Speaker: an End-to-End System for Large-Scale Speaker Recognition - [research.baidu](http://research.baidu.com/deep-speaker-end-end-system-large-scale-speaker-recognition)
* github
  * https://github.com/ALIZE-Speaker-Recognition
  * https://github.com/philipperemy/deep-speaker
  * https://github.com/astorfi/3D-convolutional-speaker-recognition
  * https://github.com/ibillxia/VoicePrintReco
  * https://github.com/ina-foss/inaSpeechSegmenter (CNN-based audio segmentation toolkit)
* dataset
  * http://www.robots.ox.ac.uk/~vgg/data/voxceleb (VoxCeleb: a large-scale speaker identification dataset)
  
  
Voice Conversion 
---
* github 
  * https://github.com/andabi/deep-voice-conversion 
  
  
### STM(Speech-to-Meaning)
* SoundHound's Houndify 
  * System and method for performing dual mode speech recognition : US8972263 / US9691390 / US9330669
  * Systems and Methods for Generating and Using Shared Natural Language Libraries : US20140019483
  * Systems and methods for enabling natural language processing : US8694537
  * Method for embedding voice mail in a spoken utterance using a natural language processing computer system : US9601114
  * Method for combining a query and a communication command in a natural language computer system : US20150149152
  
### Outstanding term 
* Confusion2Vec - [arXiv:1811.03199](https://arxiv.org/abs/1811.03199), [arXiv:1904.03576](https://arxiv.org/abs/1904.03576)
