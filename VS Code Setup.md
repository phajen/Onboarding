# Visual Studio Code Setup and Install

Visual Studio Code is Microsoft's integrated development environment (IDE) for all things programming. An IDE is a software application that facilitates software development with a focus on team work. Within this tutorial you will walk through the installation process for Visual Studio Code. This is platform agnostic, so it will run on Windows, Linux, and even Mac.

## Downloading Visual Studio Code

Make sure you are on a good internet connection. Open a web browser and navigate to [https://code.visualstudio.com/](https://code.visualstudio.com/). By default, you can download the Windows version.

If you click on the arrow pointing downward, you have other options for Linux and macOS. Only select the `"Stable"` Build (should be default).

Install the program like you would any other, accepting the defaults.

## Installing and Integrating Python

For those of you who are familiar with using IDE environments (e.g. Visual Studio, Eclipse, NetBeans) you can use Visual Studio Code to program Python natively. This allows you to code and run Python from directly within Visual Studio Code. Note, you must have an interpreter in order to run the code.

The following webpage provides a guide to install Python and integrate it with Visual Studio Code for Windows, Linux, and macOS [https://code.visualstudio.com/docs/python/python-tutorial](https://code.visualstudio.com/docs/python/python-tutorial). Please take note of the following:

* Windows: You will need to download Python from [python.org](https://www.python.org/downloads/).
* macOS: You cannot install a system-wide version of Python. Instead, you must use Homebrew instead (see the documentation for more details).
* Linux: By default, all mainstream Linux distros (e.g. Ubuntu, Debian) come with Python 3 installed.

## Install Extensions in Visual Studio Code

Now that Python is on your system, you need to integrate a Python interpreter in VS Code. Prior to this, install these extensions. You can search for the extension names within VS Code, or use the links provided below:

* [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
* [Pylance](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance)
* [Visual Studio IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)

To install an extension, click on the icon on the left-hand side that looks like four boxes. This will open the extensions window pane. You can use the search box to search for the extensions. When it appears, click on the extension; this will bring up a more focused window on the right-hand side displaying details about the extension. Simply click the button to install it.

## Configuring Visual Studio Code

Once all the extensions are installed, you need to configure a few options. From within VS Code, select a Python 3 interpreter by opening the `Command Palette` (Ctrl+Shift+P in Windows), start typing `Python: Select Interpreter` command to search, then select the command.

More than likely you will only have a single interpreter available. If you have more than one, select the version of Python you just installed. Additionally, as you hover over each one, the directory location will be shown at the top. This can be useful if you need to ever find the location on your computer.

The last adjustment we need to do is ensure `Pylance` is the `Python Language Server` of choice. You can find this setting by navigating to `File`, `Preferences`, `Settings`, `Extensions`, `Python`, then `Language Server` (just keep scrolling down, you’ll find it listed alphabetically). In the drop-down list, select Pylance (you may see other options such as Jedi, JediLSP, None, etc.).

That's it! You are ready to use Visual Studio Code for Python programming.