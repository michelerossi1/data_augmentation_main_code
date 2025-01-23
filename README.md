This repository contains the main code used for generating and evaluating 11 dataset augmentation techniques for music emotion recognition. The code was written in Python using Google Colab. Additionally, this repository includes code from preliminary phases and testing that were not included in the final version of the paper.


### Data Augmentation Techniques and Their Corresponding Parameter Settings

| **Augmentation** | **Module/Tool** | **Range of Values** |
|-----------------|----------------|---------------------|
| Compressor      | pedalboard      | Ratio: 1 to 4       |
| High Pass       | pedalboard      | Cutoff frequency: 200 to 2000 Hz |
| Low Pass        | pedalboard      | Cutoff frequency: 500 to 5000 Hz |
| Noise Addition  | numpy           | Percentage factor: 0 to 0.05 |
| Pitch Shift     | librosa         | Semitones: -3 to 3  |
| Random Gain     | Python          | Gain: 0.8 to 1.2    |
| Resampling      | pedalboard      | Sampling rate: 11025 to 22050 Hz |
| Reverb          | pedalboard      | Room size: 0 to 0.1 |
| Saturation      | pedalboard      | Saturation level: 0 to 20 |
| Time Shift      | Python          | Time shift: 0 to 1.5 seconds |
| Time Stretch    | librosa         | Stretch ratio: 0.97 to 1.03 |


If you have any questions regarding the code, feel free to contact me at: michele.rossi-2@unitn.it.

For the code related to the listening test app developed as part of this work, please refer to the following repository: [listening_test_webAPP](https://github.com/michelerossi1/listening_test_webAPP).
