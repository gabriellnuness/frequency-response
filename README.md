# Frequency Response

* Before running the program go to Tools/Options/Front panel and disable the option "Use localized decimal point*". Otherwise, LabVIEW will consider "," instead of "." depending on Windows language.

This LabVIEW code (version 2018) is used to automate and obtain a frequency response of any given actuator.

The input signal (frequency and amplitude) is controlled by the Function generator HP 33120A.
The output signal is acquired by the Digital Oscilloscope Agilent MSO6034A.

The communication is made via GPIB, the function generator and oscilloscope can be changed to other models by checking the user manual and replacing the commands.   

In this particular case, the experiment was designed to obtain the frequency response of optical phase modulators in an optical fiber Michelson interferometer. The modulators were piezoelectric cylinders with optical fiber wound on them.
The output was the interferometer measurement. It was limited to have a total harmonic distortion (THD) of 3 %, since the frequency response should be a linear relation between input and output in different frequencies.
