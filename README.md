# Pipsi-HSR

A clean and simple, no threads internal game hack for Honkai: Star Rail with GUI.

<p align="center"><img width="710" height="380" alt="image" src="https://github.com/user-attachments/assets/b8fb2698-81f6-43a7-b426-91197ee8b4c6" /></p>

# Disclaimer
This project is for educational and research purposes only.

# Features

- Battle Speed Changer
- Dumb Enemies
- FOV Changer
- FPS Indicator
- FPS Unlocker
- Free Camera
- Global Speed Changer
- Hide UI
- Noclip
- Peeking

# Step-by-step Build Guide

1. Clone the repository

```bash
git clone https://github.com/Z4ee/Pipsi-HSR.git
cd Pipsi-HSR
```

2. Create include folder structure and clone AnimeSDK

```bash
mkdir -p include/global
git clone -b honkai-star-rail https://github.com/Z4ee/animesdk include/global
```

3. Compile the project

- Open the `.sln` solution file in **Visual Studio 2022**
- Set configuration to **Release** and platform to **x64**
- Build the solution (`Ctrl + Shift + B`)

# How to Use
Inject the DLL as early as possible (before the game window is created)
