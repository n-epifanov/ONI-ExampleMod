# ONI-ExampleMod
Sample Visual Studio solution to help you started with a new mod for Oxygen not Included.

Requirements
------------
* .NET Framework 3.5
* Visual Studio 2017

Getting started
---------------
* Copy the following files from ONI's `OxygenNotIncluded_Data\Managed` folder to this mod's `\lib\`:
   * `Assembly-CSharp.dll`
   * `Assembly-CSharp-firstpass.dll`
   * `Assembly-UnityScript-firstpass.dll`
   * `UnityEngine.dll`
   * `UnityEngine.UI.dll`
* Open solution in Visual Studio
* Now there are some renames to be done from `ExampleMod` to your mod's name:
  * Open project's `Properties`:
    * Rename `Assembly name` and `Default Namespace`
    * Click `Assembly Information...` and make renames there too
  * Open .cs file and rename `ExampleMod` class
* Build (.dll will get copied to ONI `Mods` dir);
* Run the game.
