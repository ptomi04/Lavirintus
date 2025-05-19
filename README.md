# 3D-s Labirintus

HU:
Ez a program egy f# wpf alkalmazás mely 2D-s térben szimulált 3D megjelenítést alkalmaz (raycasting technikával), amely a klasszikus korai 3D-s játékok látványvilágát idézi, mint például a Wolfenstein 3D.

Kezelés:

A programot a jatek mappában található jatek.sln fájl-al lehet elindítani a visual studio programon keresztül (Sajnos az f# bani járatlanságom illetve időhiány miatt nincs szofisztikáltabb mód).

A szoftver Teljesképernyős módban indul el, fontos hogy a megjelenítés FullHD(1920x1080) legyen.

A kalandunk egy belső udvarból indul ahonnan egy kijárat van azon áthaladva felfedezhetjük a pája többi részét.
![Képernyőfelvétel (2109)](https://github.com/user-attachments/assets/3e6aa583-ceb1-4138-95f0-ea6068c91539)

Sajnos szörnyeket illetve kijáratot időhiány miatt nem tudtam csinálni.

Irányítás:
    W - Előre menet
    S - Hátra menet
    A - Balra fordulás
    D - Jobbra fordulás
    
Az escape gomb megnyomásával lehet a programból kilépni.

EN:
Project Description

This program is an F# WPF application that uses simulated 3D rendering in a 2D space via raycasting, reminiscent of classic early 3D games like Wolfenstein 3D.
Usage

To launch the program, open the jatek.sln file located in the jatek folder using Visual Studio.
(Note: Due to my limited experience with F# and time constraints, there is no more sophisticated way to run it.)

The software launches in fullscreen mode, and it is important that the display resolution is Full HD (1920x1080) for proper rendering.

The adventure begins in a small courtyard with a single exit. Passing through it allows you to explore the rest of the level.
![Képernyőfelvétel (2109)](https://github.com/user-attachments/assets/3e6aa583-ceb1-4138-95f0-ea6068c91539)
Unfortunately, due to lack of time, I wasn’t able to implement enemies or an actual exit point.
Controls

    W – Move forward

    S – Move backward

    A – Turn left

    D – Turn right

Pressing the Escape key brings up the menu and allows you to exit the application.
