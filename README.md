
# SocialNetworkSimulator
A software that enable spatio-temporal social network analysis and simulation.
Currently, social media has been playing an important role in the process of information diffusion. Exploring the pattern of message propagation on social network help us better prepare for natural disasters or human crises. So, we developed models, algorithms, and tools to generate simulated networks, analyze simulated networks, and simulate information diffusion on social network over time.


## GETTING STARTED
In **software_and_packages** folder: 
1) Python 2.7 64 version is required

     * a. Double click *python-2.7.13.amd64.msi* to install python 2.7 64 version.
     * b. Follow steps below to set the path variables in the environment variables.
          - (1) Right-click This PC, and then click Properties.
          - (2) Click Advance system setting.
          - (3) Click Environment variables.     
          - (4) Go to the above location and change the Path variable.
          - (5) If you install python at C:\Python27, add the following paths to Path variable. Otherwise you need to change the path according your actual path.
               * i. C:\Python27\
               * ii. C:\Python27\Lib\
               * iii. C:\Python27\Scripts\
     
2) Double click *PyQt4-4.11.4-gpl-Py2.7-Qt4.8.7-x64.exe* to install PyQt package.
3) Double click *vcredist_x64.exe* to install it.
4) Install module *numpy*, *matplotlib*, *Snap*, and *xlrd*.
     - a. Open command prompt and change path to the location where packages are. Here you are supposed to extract the tool file to C:\SocialNetworkSimulator. Use the command:
	     ```	
	    cd C:\SocialNetworkSimulator\softwares_and_packages
	    ```
	     to change the path.
	     
     - b. Execute the following commands using command prompt.
          ```
	          Pip install numpy-1.13.1-cp27-none-win_amd64.whl
	          Pip install matplotlib-2.0.2-cp27-cp27m-win_amd64.whl
	          Pip install snap-4.0.0-4.0-Win-x64-py2.7.zip
          ```
5) To start this software, please use the command for command prompt, for example:    			```Python C:\SocialNetworkSimulator\ SocialNetworkSimulator.py```
## Menu

After starting the software tool, you can see there is a menu bar on the top of the main window. Below is the summary of the functions in the menu:


| Menu | Description |
|---|---|
| **File**->Exit|Exit the software|
| **Network**->Generate Single Simulated network | Generate a simulated network based on a single model.|
| **Network**->Generate Complex Simulated network | Generate a complex network based on one or more network model. The complex network is constructed by adding edges among several smaller networks|
| **Network**->Save Network | Save the current network as a txt file|
| **Network**->Load Network | Load a network from a txt file|
| **Analysis**->Network Analysis | Perform network analysis|
| **Community**->CNM | Conduct community detection with CNM algorithm|
| **Community**->GirvanNewman |Conduct community detection with GirvanNewman algorithm  |
| **Simulator**->User Level |Simulate information diffusion on the user level |
| **Simulator**->City Level |Simulate information diffusion on the city level |
| **Data** |Provide some functions to prepare the data used in the software|
