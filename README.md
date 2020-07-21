# cookcrosshair - A very simple FiveM crosshair editor
Let's being honest, a lot of people have an ingame crosshair, it's even available in some screens... 
So ! to make it fairplay to everyone i made a very simple script to edit and use a built-in crosshair into FiveM.
It's not perfect, but it should do the job.

- [FiveM Forums](waiting for the url)
- [Video Preview](https://streamable.com/41qq12)

## Installation Instructions
- Download **cookcrosshair** from GitHub
- **Edit** your **server.cfg** and add ``ensure cookcrosshair``
- People **will already be able** to edit and use the crosshair **using the commands using the console** :
- - **cross :** To **display** the crosshair
- - **crosse :** To **edit** the crosshair
- - **crossr :** To **reset** the crosshair
- To add the options in your menus, You might want to **trigger the events** from your own scripts :
- ``TriggerEvent("cookcrosshair:active")``
- ``TriggerEvent("cookcrosshair:reset")``
- ``TriggerEvent("cookcrosshair:edit")``
- Add, remove anything you want, **from now on that is your script !**
