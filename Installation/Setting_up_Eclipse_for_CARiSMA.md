# How to create a Papyrus Project

## Eclipse Modeling Tools
- First, you need to install the Eclipse Modeling Tools. You can find it at : https://www.eclipse.org/downloads/packages/
- If you have problems installing it, check out the installation guide at : https://wiki.eclipse.org/Eclipse/Installation


## BPMN2 Modeler
If you want to model business processes using BPMN models, you need to do the following steps:
- Open Eclipse.
- Navigate to *Help*.
- Select the *Eclipse Marketplace*.
- Search for the *Eclipse BPMN2 Modeler*.
- Install the *Eclipse BPMN2 Modeler*.
- Select at least the required features and confirm your choices.
- Wait for the installation process to finish and restart Eclipse.

## Papyrus
After installing the Eclipse Modeling Tools, you need to install Papyrus. You can find the latest version here : https://www.eclipse.org/papyrus/download.html
- Open Eclipse.
- Navigate to *Help*.
- Click *Install New Software*.
- Add a new repository
- Paste the update site into the *Location* field and name it.
- Press *Add* and choose the features you want to install.
- At least, install ”Papyrus for UML” and ”Papyrus for UML Developer
     Resources”.
- These can be found if you expand the features.
- Wait for the installation to finish and restart Eclipse.


## CARiSMA
Next, you are ready to install the CARiSMA tool. You can find the latest ver- sion here :
https://github.com/CARiSMA-Tool/carisma-tool .
Otherwise, you can also use the update site for the latest version: https://rgse.uni-koblenz.de/carisma/updatesite/ . To install CARiSMA, you need to follow the steps 1 - 4 from the Papyrus installation. Afterwards, you do the following:
- Paste the update site into the *Location* field and name it.
- Press *Add* and choose the features you want to install.
- At least, install ”CARiSMA Checks for UML2".
- These can be found if you expand the features.
- Wait for the installation to finish and restart Eclipse.

Sometimes it can happen that the target platform configuration is broken. To fix this issue, you need to navigate *Preferences* → *Plug-In Development* → *Target Platform*. In the *Target Platform* settings, you can specify the plugins and libraries that should be included in your target platform configuration. You can add, remove, or modify the entries as necessary to ensure that you have the correct dependencies.

