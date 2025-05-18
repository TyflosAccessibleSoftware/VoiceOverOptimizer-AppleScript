# VoiceOverOptimizerAppleScript

## Description

VoiceOverOptimizerAppleScript is a simple AppleScript utility designed to improve the performance of VoiceOver on macOS by increasing the process priority of the VoiceOver daemon.

VoiceOver is a critical assistive technology for blind and visually impaired users. However, under certain system loads or when using resource-intensive applications, VoiceOver may become less responsive. This script detects the running VoiceOver process and uses the renice command to assign it a higher priority (-20), allowing the system to allocate more resources to it.

When executed, the script will:

* Prompt for administrator privileges (required to adjust process priorities).
* Locate the VoiceOver process using pgrep.
* Apply a renice -20 to ensure maximum scheduling priority.
* Provide audible confirmation through VoiceOver and a system sound.

This tool is especially useful for users who experience lag or delays in VoiceOver feedback and want a quick way to boost responsiveness without restarting the system.

## Copyright and license

Copyright 2025 Tyflos Accessible Software. All rights reserved.

You may incorporate this Tyflos Accessible Software code into your system and 	program(s) without restriction.  

This software has been provided "AS IS" and the responsibility for its operation is yours.  

You are not permitted to redistribute this Tyflos Accessible Software script as "Tyflos 	Accessible Software project" after having made changes.  

If you are going to redistribute the code, we require that you make it clear that the code was 		descended from Tyflos Accessible Software project, but that you've made changes.

If you have any suggestion or petition about this software please send an e-Mail to Tyflos Accessible Software using this e-Mail address:
	[Tyflosaccessiblesoftware@gmail.com](mailto:Tyflosaccessiblesoftware@gmail.com)
