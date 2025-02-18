# Digital-Audio-Signal-Processing


# **Introduction**

In this project, we will explore some methods of digital audio signal processing. Specifically, we will examine the application of a bandpass filter on an audio signal, how to generate an echo, and how to convert a voice into a robotic voice. For writing the code, it is preferred to use the MATLAB environment.



### **Project Steps**

#### **1. Recording Audio**

- Record your voice counting from "one" to "ten".




#### **2. Signal Manipulation and Analysis in MATLAB**

**Loading the Signal and Initial Specifications:**

- Load the `counting_to_ten.wav` file. Ensure that the audio file duration is 10 seconds. Extract the two audio channels.

**Time Domain Analysis:**

- Plot the amplitude of each channel over time.

**Frequency Domain Analysis:**

- Plot the magnitude spectrum for each channel (magnitude vs. frequency).



#### **3. Filter Design**

**Implement a Bandpass Filter with the Following Parameters:**

- **Lower Cutoff Frequency:** 500 Hz
- **Upper Cutoff Frequency:** 2000 Hz

In this project, the lower and upper cutoff frequencies refer to two specific frequencies used to design the bandpass filter. The bandpass filter allows only sounds within the range between these two frequencies to pass, while other sounds are removed.

- **Lower Cutoff Frequency:** This is the minimum frequency that the filter allows to pass. In this project, it is set to 500 Hz, meaning frequencies below 500 Hz are removed.
- **Upper Cutoff Frequency:** This is the maximum frequency that the filter allows to pass. In this project, it is set to 2000 Hz, meaning frequencies above 2000 Hz are removed.


#### **4. Filtering and Comparison**

**Task:**

- Apply the bandpass filter to both audio channels. Plot the original and filtered signals in the time domain.


#### **5. Spectral Analysis After Filtering**

**Task:**

- Calculate and plot the magnitude spectrum of the filtered audio for both channels and compare it with the original spectrum.


#### **6. Echo Effect**

**Task:**

- Apply an echo effect with the following parameters:
  - **Delay:** 0.2 seconds
  - **Attenuation:** 0.5


#### **7. Robotic Voice Conversion**

**Amplitude Modulation:**

- First, study amplitude modulation.



#### **8. Output Files**

**Task:**

- Save the echo-processed audio in `effect_echo.wav` and the robotic voice in `effect_robot.wav`.

