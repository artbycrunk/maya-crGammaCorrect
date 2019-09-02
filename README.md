# maya-crGammaCorrect

[![Version](https://img.shields.io/badge/version-1.5.0-green.svg)]()
[![MIT](https://img.shields.io/badge/license-MIT-green)]()

[![](https://img.shields.io/badge/TWITTER-%40artbycrunk-blue.svg?logo=twitter&style=flat)](https://twitter.com/artbycrunk)
[![Average time to resolve an issue](https://isitmaintained.com/badge/resolution/artbycrunk/maya-crGammaCorrect.svg)](https://isitmaintained.com/project/artbycrunk/maya-crGammaCorrect "Average time to resolve an issue")
[![Percentage of issues still open](https://isitmaintained.com/badge/open/artbycrunk/maya-crGammaCorrect.svg)](https://isitmaintained.com/project/artbycrunk/maya-crGammaCorrect "Percentage of issues still open")

A useful little script for using GammaCorrection on File Nodes.

<!-- Images -->
[crgammacorrect_screen01]: images/crgammacorrect_screen01_02.jpg "crgammacorrect_screen01"
[crgammacorrect_screen02]: images/crgammacorrect_screen02.jpg "crgammacorrect_screen02"

![crgammacorrect_screen01][crgammacorrect_screen01]

## **Features** :

* Adds/ Removes Gamma Correction Node to Multiple Selected File Nodes.
* Can add gamma correction node to all file nodes in scene simultaneously.
* Now works on connected FileNodes only. Filenodes without connections are ignored.
* Automatically Calculates the equivalent of the gamma input.
* Can updates existing GammaCorrection nodes with a new gamma value.
* Support for both GammaCorrect and Mip_Gamma_Gain Node (MR).
* Can Toggle between GammaCorrect and Mip_Gamma_Gain Node if required.


## **Usage** :

1. Just Source this script, it should open the crGammaCorrect Window.

2. Input the Gamma that u want to minus. 

3. Select the File Node that u want to add the gamma correction on. 

4. Select the type of gamma Shader that u want to use. 

5. Click Update Selected. 

**Note:** When updating of deleting the Gamma Node, u can select either the file node or the gammaNode whichever is convenient :)
