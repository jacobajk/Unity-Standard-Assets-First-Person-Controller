# Unity Standard Assets First Person Controller Bug Fix

This is an updated SimpleActivatorMenu Script for Unity Versions 2017 and above to fix the error as shown below.

Error message: Assets\Standard Assets\Utility\SimpleActivatorMenu.cs(11,16): error CS0619: 'GUIText' is obsolete: 'GUIText has been removed. Use UI.Text instead.'

![image](https://user-images.githubusercontent.com/68107482/90314900-cf322c80-df49-11ea-9e80-10c730110704.png)

Change GUI.Text into Text and add using UnityEngine.UI

![image](https://user-images.githubusercontent.com/68107482/90315001-6f885100-df4a-11ea-9d4c-45e54078ddc8.png)
