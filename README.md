<h1>AI/ML Trained Voice Activated Light</h1>

 ### [Code of the Voice Activated Light](https://github.com/jingmainacc/Voice-Activated-Light/blob/main/VoiceActivatedLight.ipynb)

<h2>Description</h2>
Developed a voice-controlled light system that responds to specific voice commands to control lighting. This project involved creating an interactive system capable of understanding and executing commands such as "on," "off," "silence," and "unknown" to manipulate a light's state. The system integrates advanced audio processing and machine learning techniques to achieve accurate voice command recognition.
<br />

<h2>Key Features:</h2>

- Voice Command Recognition: The system effectively recognizes and distinguishes between the keywords "on," "off," "silence," and "unknown."
- Interactive Control: Users can control the light's state through spoken commands, with the system maintaining the light's state unchanged for unrecognized inputs.
- Machine Learning Model: Utilized a custom-trained SimpleCNN model, which was trained and validated on a diverse dataset of audio recordings containing the target keywords.


<h2>Technologies Used:</h2>

- Programming Languages: Python
- Libraries and Tools: PyAudio, Wave, Torchaudio, PyTorch, Tkinter
- Model: Custom SimpleCNN, trained on a dataset of audio recordings with keywords

<h2>Environments Used </h2>

- <b>Visual Studio Code</b> 

<h2>Program walk-through:</h2>

<p align="center">
<br />
<br />
Input "Off": <br/>
<br />
<img src="https://imgur.com/sxPEzYd.png" alt="Disk Sanitization Steps"/>
<br />
<br />
Input "On": <br/>
<br />
<img src="https://imgur.com/THMB2Bw.png" alt="Disk Sanitization Steps"/>
<br />
<br />
No input (Silence):
The state of the bulb should remain the same<br/>
<br />
<img src="https://imgur.com/BvDAycA.png"/>
<br />
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
