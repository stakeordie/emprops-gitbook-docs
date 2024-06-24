---
description: Using Variables in EmProps Studio
---

# 📄 Using Variables in EmProps Studio

Introduction

One of the core features in the Studio is 'Variables'.

Variables in EmProps Studio offer a way to introduce diversity, precision, and control in the image generation process. This guide will take you through the steps of creating, editing, and applying variables to your projects.

### Accessing the Variables Editor <a href="#h_eadc84c78d" id="h_eadc84c78d"></a>

<figure><img src="../../.gitbook/assets/image (4).png" alt="" width="286"><figcaption><p>Select "Manage" to edit your Variables.</p></figcaption></figure>

1. Open your project in Studio.
2. Navigate to the “Variables” section on your project page.
3. Click on the “MANAGE” button to open the Variables Editor.

## Creating Variables <a href="#h_32c7242767" id="h_32c7242767"></a>

### Character Strings <a href="#h_efcef9ec41" id="h_efcef9ec41"></a>

1. Click on “ADD ANOTHER” under the Character Strings section.
2. Enter a name for your variable, for example, ‘color’.
3. Choose 'Weighted Pick' as the Type if you want certain values to be more likely than others.
4. Enter the values you want to assign (e.g., red, blue, green), and assign weights to them if necessary.
5. Click on “SAVE CHANGES” to keep your new variable.

### Image Variables <a href="#h_1849c8a266" id="h_1849c8a266"></a>

1. In the Images section, click “ADD ANOTHER” or “ADD MULTIPLE” if you wish to upload several images.
2. Name your image variable, such as 'Image Variable Group 2'.
3. Use the "CHOOSE IMAGE" button to upload images from your device.
4. Once uploaded, they will be available for selection during image generation.

### Number Variables <a href="#h_e0e781ad70" id="h_e0e781ad70"></a>

1. Select “ADD ANOTHER” in the Numbers section.
2. Input a name for your variable, like ‘seeds’.
3. Set the variable type to 'Pick' for random selection.
4. Enter the numerical values you want to include.

### Applying Variables to Your Prompt <a href="#h_a873140a6d" id="h_a873140a6d"></a>

1. Return to your project editor where your prompt is configured.
2. Double-click on the variable in the Variables section to add it to the prompt.
3. Your chosen variables will now influence the image generation according to the parameters you set.

### Best Practices for Variables <a href="#h_9f7352ec96" id="h_9f7352ec96"></a>

* Use meaningful names for variables to keep track of their use in different projects.
* When using weighted picks, ensure the weights reflect the desired frequency of the values in the generated images.
* For number variables like 'seeds', consider using values that significantly alter the output for distinct results.
* If you write a \{{variable\}} within your variables, it will not parse the nested variable. At the moment, variables can only contain a text string; no infinite variable loops allowed!

### Managing and Editing Variables <a href="#h_589e7a5afd" id="h_589e7a5afd"></a>

* To edit a variable, click the “Edit” button next to it in the Variables Editor.
* Adjust the values, weights, or type as needed and save your changes.
* You can delete a variable by selecting the “Delete” option.

### Importing and Exporting Variables <a href="#h_7abdeecb9e" id="h_7abdeecb9e"></a>

* Use the "IMPORT FROM CSV" function to bulk add variables from a CSV file.
* To export your variables for use in another project or for backup, select the "DOWNLOAD AS CSV" which will contain your current variable settings.

### Conclusion <a href="#h_beb847c841" id="h_beb847c841"></a>

Variables are a potent feature in EmProps Studio, giving you the ability to customize and randomize your creative outputs extensively. Experiment with different variable types and values to find the best combination for your projects.
