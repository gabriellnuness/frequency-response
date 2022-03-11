# Frequency Response

This LabVIEW code is used to automate and obtain a frequency response of any given actuator.

The input signal (frequency and amplitude) is controlled by the Function generator HP 33120A.
The output signal is acquired by the Digital Oscilloscope Agilent MSO6034A.

In this particular case, the experiment was designed to obtain the frequency response of optical phase modulators in an optical fiber Michelson interferometer. The modulators were piezoelectric cylinders with optical fiber wound on them.
The output was the interferometer measurement. It was limited to have a total harmonic distortion (THD) of 3 %, since the frequency response should be a linear relation between input and output in different frequencies.
