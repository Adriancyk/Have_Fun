# Have_Fun

## Setup

Simple console game repo. Please follow the steps below to setup the project. 

Install **Visual Studio 2019**.

Install **SFML Toolbox** using this [link](https://www.sfml-dev.org/download.php), or you can use the SFML code in SFML folder in this repo.

Open the project in VS 2019.

Open "Project Name" **Property** under **Project** in the menu bar.

In the "Project Name" **Property** window, select **All Configurations**, then set the **Additional Include Directories** as **\SFML\include**.

In **Linker\General**, set **Additional Library Directories** as **\SFML\lib**

In **Linker\input**, add following **sfml-graphics-d.lib;sfml-window-d.lib;sfml-system-d.lib;sfml-network-d.lib;sfml-audio-d.lib;** into **Additional Dependencies**.