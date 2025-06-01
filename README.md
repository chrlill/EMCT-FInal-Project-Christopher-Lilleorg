# Friction(less) - BSc Electronic Music, Computing and Technology final project by Christopher Lilleorg

Goldsmiths, University of London

Instructed by: Charles Hutchins

Student ID: 33772935

----------------------------------------------------------------------------------------
Project Overview
----------------------------------------------------------------------------------------

Friction(less) is an interactive audio-visual installation that combines live sound synthesis and real-time AI-generated imagery. This project integrates Max/MSP with the FluCoMa and ODOT packages for audio synthesis, and TouchDesigner with the custom StreamDiffusionTD component by DotSimulate for the visuals.

This installation is normally controlled with a touch interface, but the code has been adjusted to be controlled with a mouse for testing purposes.

----------------------------------------------------------------------------------------
Software & Libraries
----------------------------------------------------------------------------------------
Max/MSP

FluCoMa package for Max/MSP

ODOT package for Max/MSP

TouchDesigner

StreamDiffusionTD custom component by DotSimulate (Requires NVIDIA GPU, CUDA 12.8, and Python 3.10.6)

----------------------------------------------------------------------------------------
Hardware Requirements
----------------------------------------------------------------------------------------

NVIDIA GPU (for CUDA support)

CUDA 12.8

Python 3.10.6

----------------------------------------------------------------------------------------
Setup Instructions
----------------------------------------------------------------------------------------
------------------------------------
1. Install Required Software
----------------------------
Install Max/MSP from cycling74.com

Install FluCoMa and ODOT packages from the Package Manager within Max.

Install TouchDesigner from derivative.ca.

Install StreamDiffusionTD by DotSimulate (follow the installation guide provided with the component).
------------------------------------
2. Install CUDA and Python
--------------------------
This project requires an NVIDIA graphics card compatible with CUDA 12.8. If needed, install the required CUDA version and Python 3.10.6.
Make sure you have the necessary drivers installed for your GPU.
------------------------------------
3. Audio Setup in Max/MSP and TouchDesigner
-------------------------------------------
Connect the audio output from Max/MSP to the Audio Device In operator in TouchDesigner using an audio routing software (such as Soundflower on macOS or Jack Audio on Windows/Linux). 

Set the audio output device in the Audio Device Out operator to hear sound output.
------------------------------------
4. Load and Slice Samples in Max/MSP
------------------------------------
Open the Max/MSP patch and connect the synthesizer to the path of the provided sample folder.

To load and slice the samples, click on the message box containing the file path.

Start the Drone2.wav file and set it to play on loop in Max/MSP.
------------------------------------
5. Visual Setup in TouchDesigner
--------------------------------
Open the TouchDesigner project.

Set up the StreamDiffusionTD component as per the provided instructions by DotSimulate.
------------------------------------
6. Interaction
--------------

Click on the Window operator within the project file. Open the project in Presentation mode. Press 5 on the keyboard to start the introductory sequence and then use your mouse to click within the TouchDesigner window to begin drawing and generating real-time AI imagery and control the synthesiser. 

------------------------------------------------------------------------------------
Acknowledgements
------------------------------------------------------------------------------------

FluCoMa – Developed by FluCoMa Team, providing a comprehensive framework for computational music analysis and composition. https://www.flucoma.org/

ODOT – Developed by Jack Armitage and David Bowden, offering a flexible environment for live coding and algorithmic composition in Max/MSP. https://odot.systems/

TouchDesigner – Created by Derivative, offering a node-based visual programming environment used for real-time interactive multimedia content. https://www.derivative.ca/

StreamDiffusionTD – Custom component by DotSimulate, used to generate AI imagery in real time.
DotSimulate StreamDiffusionTD Component

------------------------------------------------------------------------------------
License
------------------------------------------------------------------------------------
This project is for educational purposes and is not for commercial use. All third-party libraries and components are credited in the acknowledgements section.

