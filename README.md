# Gapless Play: Installation and Usage Guide

This Python script allows users to loop audio files without any gaps between the loops. This guide will walk you through the prerequisites, installation, and usage of the script on an OS X machine.

## Prerequisites

Before proceeding, make sure that you have Python 3 and Pygame installed on your system. If not, you can follow the steps below to install them.

### Step 1: Install Homebrew

Homebrew is a package manager for macOS that simplifies the installation of software. 

1. Open Terminal. You can do this by searching for Terminal in Spotlight (the magnifying glass at the top right of your screen) and pressing Enter.
2. Copy the following command into the Terminal and press Enter. You might be prompted to enter your password:

    `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

3. Once the installation completes, you can confirm the installation by typing:

    `brew --version`

You should see the Homebrew version in the output.

### Step 2: Install Python 3

With Homebrew installed, Python 3 can be installed using the command:

    `brew install python3`

After the installation completes, confirm the Python version by typing:

    `python3 --version`

You should see the Python 3 version in the output.

### Step 3: Install Pygame

Pygame is a Python library designed for video game development, but it's also great for sound and graphics. It can be installed using pip, which is the package installer for Python.

To install Pygame, type the following command:

    `python3 -m pip install pygame`

This will install the pygame module.

## Install the Gapless Play Script

1. Open TextEdit, found in the Applications folder.
2. Go to TextEdit > Preferences (or press Command+,) and select "Plain text" under Format.
3. Copy the code of the "gapless_play" script into the TextEdit window.
4. Save the file with the ".py" extension (for example, "gapless_play.py") to your preferred directory.

## How to Use the Script

1. Place your audio file (either .wav or .mp3) in the same directory as the "gapless_play" script.
2. Open Terminal and navigate to the directory where the "gapless_play" script is saved.
3. Run the script by typing:

    `python3 gapless_play.py`

The script will play the audio file in a loop without gaps. By default, the script is set to loop 5 times. You can adjust this by changing the value of the "loops" variable in the script.
