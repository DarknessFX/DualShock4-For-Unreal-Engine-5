     .----------------.  .----------------.  .----------------. 
    | .--------------. || .--------------. || .--------------. |
    | |  ________    | || |  _________   | || |  ____  ____  | |
    | | |_   ___ `.  | || | |_   ___  |  | || | |_  _||_  _| | |
    | |   | |   `. \ | || |   | |_  \_|  | || |   \ \  / /   | |
    | |   | |    | | | || |   |  _|      | || |    > `' <    | |
    | |  _| |___.' / | || |  _| |_       | || |  _/ /'`\ \_  | |
    | | |________.'  | || | |_____|      | || | |____||____| | |
    | |              | || |              | || |              | |
    | '--------------' || '--------------' || '--------------' |
     '----------------'  '----------------'  '----------------' 

           DarknessFX @ https://dfx.lv | Twitter: @DrkFX

# DualShock4 For Unreal Engine 5.1

<img src="https://repository-images.githubusercontent.com/591609859/efa605da-cf6c-44ba-847e-60d9a043d6f0" width="640px" /> <br/>

DualShock4 For Unreal Engine 5.1 using Raw Input and Enhanced Input. <br/>

## About

Originally to make DualShock 4 work with Unreal Engine 4 was just a list of RawInputWindows Plugin settings and was simpler to describe like in this forum post <a href="https://forums.unrealengine.com/t/tutorial-ue4-using-dualshock4-controller-via-usb-ps4-ds4-gamepad/133314" target="_blank">[Tutorial] UE4 using Dualshock4 controller (via USB, PS4 DS4 Gamepad)</a>. Now that Unreal Engine 5.1 is moving the input system to Enhanced Input there are more files and structures to setup and isn't that simple to explain in a forum post, so this project is the easier way to share this information and give a demostration template working where it can be copied to other projects. <br/>

## Notes

- Only works while DualShock 4 is connected via USB.
- If you have a DualShock4 1st Generation (Product ID 0x05C4) the project will inform you and still work but the DPAD is going to register only one Axis.
- TopDownShooter Template is used for presentation only, there are no game functionality and it doesn't control like a twin-stick shooter.
- Basic Enhanced Input Action setup (only Button and Axis - Pressed and Released), for more information how to expand and create more Input Actions check <a href="https://docs.unrealengine.com/5.1/en-US/enhanced-input-in-unreal-engine/" target="_blank">Enhanced Input - An overview of the Enhanced Input Plugin.</a> and <a href="https://dev.epicgames.com/community/learning/tutorials/eD13/unreal-engine-enhanced-input-in-ue5" target="_blank">Enhanced Input in UE5 - Official Tutorial</a>.

## Credits

Unreal Engine from Epic Games - https://www.unrealengine.com/ <br/>
Playstation DualShock4 by Arks - https://arks.itch.io/ps4-buttons <br/>
CorentinG78 for sharing the initial DS4+EnhancedInput+RawInput - https://forums.unrealengine.com/t/tutorial-ue4-using-dualshock4-controller-via-usb-ps4-ds4-gamepad/133314/54

## License

@Unlicensed - Free for everyone and any use. <br/><br/>
DarknessFX @ <a href="https://dfx.lv" target="_blank">https://dfx.lv</a> | Twitter: <a href="https://twitter.com/DrkFX" target="_blank">@DrkFX</a> <br/>https://github.com/DarknessFX/DualShock4-For-Unreal-Engine-5
