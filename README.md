# DEV : CUSTOMISATION ITOP #

## Basics, tools and configuration

Install [Code Editor](https://code.visualstudio.com/) + [Git](https://git-scm.com/downloads) to get the repo
- Find config folder to install Toolkit using Portainer (Linux Command) 
- Coding in .xml && Php

 <!-- - Get [Itop Toolkit](https://manage-wiki.openitop.org/doku.php?id=3_0_0:customization:datamodel#installing_the_toolkit) OR via [private repository](https://github.com/Edumotiv/dev/tree/integration/services/toolkit) 

*NOTES : The module has been integrated in a [private repository](https://github.com/Edumotiv/dev/tree/integration/services/toolkit) with the command "git submodule add". To update the module, enter in a terminal (located in the folder space) git submodule update --remote --merge. 
This will automaticaly updates every exsting Git submodules where you are located.* -->

## How to install Toolkit 

1. Get the link from the [tar.gz](https://github.com/Combodo/itop-toolkit-community/archive/refs/tags/3.0.0.tar.gz) - [Github link](https://github.com/Combodo/itop-toolkit-community/releases)

2. Go to Portainer, install wget if necessary
*apt-get install wget*

3. Go to the iTop folder, and stay at the root, then get the toolkit tar folder by typing the command : *wget <url tar.gz>*

4. Extract it :
*tar cfv <tar.gz file>*
You will obtain a folder called *itop-toolkit-community...* 

5. Create a directory in the iTop root. 
Be sure to be at the root location and type : *mkdir toolkit*

6. Go to your itop-toolkit-community folder, and move the content in the toolkit directory we just created :
*mv <file name 1> <file name 2> <etc.> ../toolkit*

7. Copy paste this URL in your browser : 
*http://<your_itop>/toolkit*


## Customize fields


## Create new CL models


