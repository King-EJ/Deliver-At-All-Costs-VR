# Deliver-At-All-Costs-VR
VR mod for Deliver At All Costs "test build not full release"

<img width="1024" height="1536" alt="Deliver At All Costs" src="https://github.com/user-attachments/assets/dc48cb53-ace5-46b6-b780-6e213a232037" />


DELIVER AT ALL COSTS VR  -  VR mod (Unity 2021.3.42f1, IL2CPP x64, URP, BepInEx 6 be.788)
=========================================================================================
Version 0.1.9 (test build)

INSTALL
  unzip to game folder, only tested with virtual desktop XR

  **[Nefarius ViGEmBus](https://github.com/nefarius/ViGEmBus/releases) support - with the driver installed (ViGEmBusSetup_x64.msi in the zip) the VR
        controllers are a real virtual Xbox 360 controller ([Controls] InputMethod = Auto / ViGEm / InputSystem).**

VIEW
  * First person (default): you are the courier - his head is hidden, his body and hands stay visible, and his
    hands follow your controllers (while carrying a box, climbing, getting in / out of the car or ragdolling the
    game's own arm pose is used: [Arms] HandsWhileCarrying). The left stick walks where you look, the right stick
    turns you (snap 30 degrees).
    In the car: you sit in the driver's seat and your view turns with the car. If the game hides the courier in the
    car you sit at [View] CarSeat (adjust it in the VR settings menu: "car seat").
  * Third person: you follow behind the courier (or the car) - [View] ThirdPersonStyle = GameCamera puts you where
    the game's own (high, top-down) camera is instead.
  * RIGHT STICK CLICK = switch first / third person (on foot and in the car).
  * RIGHT STICK UP (flick) = switch third person Follow / GameCamera.
  * GameCamera mode: hold LEFT GRIP + right stick up / down = move your view forward / back; also hold the RIGHT
    TRIGGER = higher / lower (saved; also in the VR settings menu, much bigger range now).
  * First person in the car: the game's minimap is on the dashboard (VR settings menu: "minimap ..." to move /
    resize it, "minimap upside down fix" if needed).
  * Menus / pause / notebook / title screen: the game's picture on a screen in front of you, plain Xbox controls.

CONTROLS (the VR controllers are an Xbox 360 controller for the game)

  Left stick ............ left stick 
  
  Right stick ......... turn (menus / game camera: the right stick
  
  ([Controls] SwapXB swaps X and B)
  
  X + Y together ........ START
  
  Left grip + B ....... BACK
  
  Left grip HELD + left stick ... D-PAD
  
  Right stick click ..... first / third person (in menus: R3)
  
  Right stick DOWN ...... the game's R3 (in play)
  
  Right stick UP ........ third person Follow / GameCamera (in play)
  
  Left grip + right stick  **GameCamera mode: move your view (with right trigger: up / down)**
  
  PUSH the right controller forward (first person, on foot) ... right grip button (RB\melee)
  
  Left grip + Y ......... VR SETTINGS MENU  Left grip + X ....... re-centre the view
  
  BOTH grips held 1 s ... LIVE HAND ADJUST: left stick moves the left hand, right stick the right hand
                          (left / right, forward / back; hold that hand's trigger = up / down). Let go to keep it.
                          

  A real Xbox controller works as normal at the same time (L3 + R3 held 1 s = VR settings menu).
  Every button can be changed in the config ([Controls.Pad]).

Issues
-
* Performace (may work well for you mot my PC side note i have on HHD :( )
* remove hat\hair in 3rd persson you can reenable it in VR settings

Disable: to disable Mod rename winhttp.dll to winhttp.dll.bak

[VR Mod Manager](https://github.com/King-EJ/VR-Mod-Manager/releases/tag/VRModManager)

LICENSES
-
Uses Astien's OpenXR bridge. Free, non-commercial.
