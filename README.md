# ComfyUI - quadmoon's Nodes

## Introduction

This is a repository of all the nodes I wanted to have but couldn't find anywhere. I am quite happy with them and will update this repo as I fix bugs and create new nodes. Enjoy!

## Features

### Existing Nodes
* **The BUTTON** - A one-stop-shop for cancelling your queue or rebooting ComfyUI entirely. Something gone wrong with your setup? Hit ***The BUTTON***. It will take care of everything for you. Use responsibly.

![image](https://github.com/traugdor/ComfyUI-quadMoons-nodes/assets/6344355/304fb3ab-d363-4809-8d31-901d4c842bb2)

* **CLIP External Text Encoder** - Your regular `CLIP Text Encoder` node but the text to encode with CLIP defaults to an input instead of a text box. No more right-clicking and converting the text widget to an input! This node works best when used with wildcard selectors and other dynamic output nodes for creating rich and dynamic prompts for your images.

![image](https://github.com/traugdor/ComfyUI-quadMoons-nodes/assets/6344355/e69d37a7-55d1-4d8d-a53a-406ab5ea36a9)

* ***Converters***
    * **X to String Converters** - Need to incorporate a value into a string? Maybe a filename input automation? Need to do some math and output the result into a text display? Convert it to a string and easily output it to whatever nodes you need. It even works with the [ComfyMath](https://github.com/evanspearman/ComfyMath) nodes by [evanspearman](https://github.com/evanspearman) so you can easily use a generic `NUMBER` value as an input!
 
    ![image](https://github.com/traugdor/ComfyUI-quadMoons-nodes/assets/6344355/d2c8be0e-f66b-48bb-bdd8-f8b0fa7ce06c)

    * **Normalize Image Dimensions** - Choose between SD1.5 and SDXL image dimension normalization. This node will quickly calculate which input is the largest and normalize both inputs to be the same size or smaller than the base image for the chosen platform.

    ![image](https://github.com/traugdor/ComfyUI-quadMoons-nodes/assets/6344355/4b2d8208-599c-4eb2-8bf6-42cded26cadf)

* **INT Conditional Operation** - Choose between two integer inputs on the fly using conditional logical operators to compare them. Works great for returning the largest or smallest input depending on your needs.

![image](https://github.com/traugdor/ComfyUI-quadMoons-nodes/assets/6344355/fc4ce451-a5f7-4151-b81d-c219b8f6fba0)

* **KSampler - Extra Outputs** - Need to use the same seed value between nodes? Want to cleanup your workflow so you don't have to reuse the same node everywhere. `KSampler - Extra Outputs` may just be what you need to incorporate into your workflow!

![image](https://github.com/traugdor/ComfyUI-quadMoons-nodes/assets/6344355/96a65456-184e-4558-8ea2-b67651de645e)


### Planned Nodes
* **Smart Negative** - Save common negative prompts that are used with the model of your choice. (***WIP***)
* **Smart Template** - Save common prompt templates that are used with the model of your choice. (***WIP***)

## Installation

Install is currently only supported through ComfyUI Manager by use of the `Install via GIT URL` option. If you wish to install manually, instead, open the terminal program of your choosing and navigate to your ComfyUI installation. Enter the following commands:
1. `cd custom_nodes`
2. `git clone https://github.com/traugdor/ComfyUI-quadMoons-nodes.git`

Any time you change the ComfyUI software or custom nodes you will need to reboot ComfyUI to see the changes.

### Uninstallation
To uninstall **ComfyUI-quadMoons-nodes**, browse to your `custom_nodes` folder and delete the `\ComfyUI-quadMoons-nodes` folder. Reboot ComfyUI.

## Support and Contribution

For support, suggestions, or contributions, please visit the [GitHub repository](https://github.com/traugdor/ComfyUI-quadMoons-nodes), submit an issue/pull request, or contact me on Discord (@quadmoon). I value your feedback greatly!

---

*quadMoon's Nodes* is part of the ComfyUI ecosystem. It is my hope that you are able to incorporate most, if not all, of my nodes into your workflows. Enjoy!

