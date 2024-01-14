# Sampling Signal Using MATLAB GUI 
## SAMPLING
In signal processing, sampling is reducing a continuous-time signal to a discrete-time signal. A common example is the conversion of a sound wave (a continuous signal) to a sequence of samples (a discrete-time signal).  
A sample is a value or set of values at a point in time and/or space.  
A sampler is a subsystem or operation that extracts samples from a continuous signal.  
![image](https://github.com/izmanaveed/Sampling-Signal-Using-MATLAB-GUI/assets/59065717/ca48bd3f-3f67-4cad-bf4f-27d2665a0651)  

Sampling can be done for functions varying in space, time, or any other dimension, and similar results are obtained in two or more dimensions. For functions that vary with time, let s(t) be a continuous function (or “signal”) to be sampled, and let sampling be performed by measuring the value of the continuous function every T seconds, which is called the sampling interval or the sampling period. Then the sampled function is given by the sequence:  
s(Nt),   for integer values of n.  
The sampling frequency or sampling rate, fs, is the average number of samples obtained in one second (samples per second), thus fs = 1/T.  
In practice, the continuous signal is sampled using an analog-to-digital converter (ADC), a device with various physical limitations.

## Sampling theorem
A continuous-time signal can be represented in its samples and can be recovered back when sampling frequency fs is greater than or equal to twice the highest frequency component of the message signal. i. e. fs≥2fm.  
![image](https://github.com/izmanaveed/Sampling-Signal-Using-MATLAB-GUI/assets/59065717/8032afea-4f91-48dd-b9b2-be88c889ef76)  
NOTE: Aliasing Effect  
The overlapped region in the case of under-sampling represents an aliasing effect.  
Proof: Consider a continuous-time signal x(t). The spectrum of x(t) is limited to fm Hz. A sampling of input signal x(t) can be obtained by multiplying x(t) with an impulse train δ(t) of period Ts. The output of the multiplier is a discrete signal called the sampled signal which is represented with y(t) in the following diagrams:  
![image](https://github.com/izmanaveed/Sampling-Signal-Using-MATLAB-GUI/assets/59065717/ff71575b-3758-41d8-bb50-f5b62ef114f7)  

## IMPLEMENTATION OF SAMPLING USING MATLAB GUI
The graphical user interface (GUI) allows users to interact with electronic devices through graphical icons and visual indicators such as secondary notation, instead of text-based user interfaces, typed command labels, or text navigation. GUIs were introduced in reaction to the perceived steep learning curve of command-line interfaces (CLIs), which require commands to be typed on a computer keyboard. 

The actions in a GUI are usually performed through direct manipulation of the graphical elements. Beyond computers, GUIs are used in many handheld mobile devices such as MP3 players, portable media players, gaming devices, smartphones, and smaller household, office, and industrial controls. 

Using the same theory, the sampling process done in MATLAB can be implemented through GUI. It will provide a more user-friendly and interactive environment. Also, instead of having to type in commands, the user can do so using virtual tools.

### SOME DETAILS REGARDING GUI OPTIONS USED IN PROJECT:  
1. Edit text allows us to enter values while the GUI runs. It is usually used for input.
2. Static text does not take values, instead it only displays them.
3. Push button allows the user to select the desired event and see its results.

## TESTING SAMPLING CODE ON MATLAB:
Please see Section 1 of the code in code.docx. 

### THE RESULTS OBTAINED WERE
for frequency: 100  
and sample frequency: 10  
Energy_c = 49.3982  
Energy_d = 49.5081  

![image](https://github.com/izmanaveed/Sampling-Signal-Using-MATLAB-GUI/assets/59065717/6948b2f9-7628-4827-b14d-afc75cadad6e)

## PROGRAMMING THE GUI:  
Please see Section 2 of the code in code.docx.  
![image](https://github.com/izmanaveed/Sampling-Signal-Using-MATLAB-GUI/assets/59065717/ca9cbf7d-dbfd-4d3f-a9e4-5c459c196095)  

![image](https://github.com/izmanaveed/Sampling-Signal-Using-MATLAB-GUI/assets/59065717/130be0f8-35a3-46fb-a750-7c0c8a362f4d)  

![image](https://github.com/izmanaveed/Sampling-Signal-Using-MATLAB-GUI/assets/59065717/95216a94-d1d0-44aa-9bfb-2226a3b9134a)  

![image](https://github.com/izmanaveed/Sampling-Signal-Using-MATLAB-GUI/assets/59065717/cfec20df-b332-4c00-bebe-ca8c61f0bdcc)



