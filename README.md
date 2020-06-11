# MIR

## TODO

- read and try [this](https://musicinformationretrieval.com/magnitude_scaling.html)

## terms

- tuning system
  - equal temperament
    - all semitones have the same width $2^{1\over12}$ which is 100 cents.
    - 1 octave is 1200 cents
  - just intonation
    - 5-limit just tuning
      - {2,3,5}
    - 7-limit just tuning
      - {2,3,5,7}
  - pythagorean tuning
    - 3:2
    - 3-limit just tuning
- harmonic
  - a wave with a frequency that is a positive integer multiple of the frequency of the original wave
  - known as the fundamental frequency.
  - overtones
    - harmonics excluding itself
- filters
  - Low filter
  - FIR
    - moving average
  - IIR
    - has recursive term
- tuning system
  - equal temperament
    - the ratios of the frequencies of any adjacent pair of notes is the same
    - https://en.wikipedia.org/wiki/Equal_temperament
  - pythagorean tuning
    - 3:2
    - easy to tune with ear
    - we don't use this

## References

- [Notes on Music Information Retrieval¶](https://musicinformationretrieval.com)
- [A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network](https://zenodo.org/record/1492353/files/141_Paper.pdf)
- [TECHNICAL REPORT:TEMPO AND METER ESTIMATION FOR GREEK FOLK MUSIC USINGCONVOLUTIONAL NEURAL NETWORKS AND TRANSFER LEARNING](http://www.tagtraum.com/download/2018_SchreiberGreekFolkTempoMeter.pdf)
- [Musical Tempo and Key Estimation using Convolutional Neural Networks with Directional Filters](https://arxiv.org/abs/1903.10839)
- [tempo-cnn github](https://github.com/hendriks73/tempo-cnn)
- [tempo dataset](http://www.marsyas.info/tempo/)
- [music data files](https://ccrma.stanford.edu/workshops/mir2014/audio/)
- [torchaudio Tutorial](https://pytorch.org/tutorials/beginner/audio_preprocessing_tutorial.html)
- [A Tutorial on Deep Learning for Music Information Retrieval](https://arxiv.org/abs/1709.04396)
