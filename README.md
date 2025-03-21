# **I want to use toilet again**  
#### This mod simply shows when you can use the toilet again.

## Manual Installation Guide  

<details>  
<summary>Install Unreal Shimloader</summary>  

1. Copy `dwmapi.dll` into the `GAME/Binaries/Win64` directory. The new path should be `GAME/Binaries/Win64/dwmapi.dll`.  
2. Copy the contents of the `UE4SS` folder from the package into `GAME/Binaries/Win64`.  

`GAME/Binaries/Win64` should now contain the following *new* files and folders:  
- `GAME-Win64-Shipping.exe`  
- `ue4ss.dll`  
- `UE4SS-settings.ini`  
- `dwmapi.dll` ← *This is the Unreal Shimloader binary. It will load UE4SS for you.*  
- `Mods/`  
</details>  

<details>  
<summary>Install VoidMod-2.1.0</summary>  

1. Copy `VoidMod2.pak` from the `pak` folder to the `GAME/Content/Paks/LogicMods` directory.  
</details>  

<details>  
<summary>Install IWantToUseToiletAgain</summary>  

1. Copy `IWantToUseToiletAgain.pak` from the `pak` folder to the `GAME/Content/Paks/LogicMods` directory.  
2. Copy the contents of the `mod` folder to `GAME/Binaries/Win64/Mods/Alekzum-IWantToUseToiletAgain`.
   - You have to create the `Alekzum-IWantToUseToiletAgain` folder manually.  
</details>
