Visual Boy Advance GX with PS3/PS4 controller support

An unofficial build of Visual Boy Advance GX (VBAGX) for the Wii that adds one thing: wired PlayStation 3 and PlayStation 4 controllers on the Wii's USB ports. Everything else is the original VBAGX 3.0.5.

All the credit for VBAGX goes to its creators. VBAGX is made by Tantric (Daryl Borth, dborth) and its contributors, and is based on VisualBoyAdvance / VBA-M. This build only adds the controller support. For the official VBAGX, go to github.com/dborth/vbagx.

Please don't report problems with this build to the VBAGX developers. Open an issue here instead.

Download and install
Go to Releases and download VBAGX-PS3-PS4-Wii-SD-card.zip.
Unzip it onto your Wii's SD card. It goes into apps/vbagx, replacing your current VBAGX (your settings and saves are kept). You may want to copy your old apps/vbagx/boot.dol somewhere first, as a backup.
Start VBAGX from the Homebrew Channel (or your forwarder channel). The menu shows PS3/PS4 next to the version number.
Controllers

Plug the controller into a USB port on the back of the Wii with its USB cable. You can plug it in before starting VBAGX or while it's running.

Controller	Model
PS3 DualShock 3 / Sixaxis	
PS4 DualShock 4, original	CUH-ZCT1
PS4 DualShock 4, newer (light bar on the touchpad)	CUH-ZCT2

Official Sony controllers only. Clones may not be detected.

The controller works like a Classic Controller for player 1, so the Button Mappings screen and Match Wii Controls work with it:

PS3 / PS4	Classic Controller
Cross (X)	B
Circle	A
Square	Y
Triangle	X
L1 / R1	L / R
L2 / R2	ZL / ZR
Start (PS3) / Options (PS4)	+
Select (PS3) / Share (PS4)	−
PS button	HOME
D-pad, left stick, right stick	D-pad, left stick, right stick
Rumble works on both.
The PS4 controller's light bar turns red.
One USB controller is used at a time. If both a PS3 and a PS4 controller are plugged in, whichever is found first is used.
Wiimotes, Classic Controllers and GameCube controllers work as usual alongside it.
Source code

The full source code of each version is attached to its release (vbagx-3.0.5-ps3-v14-ps4.zip), as the license requires. The new code is in source/drivers/ogc/wii/WiiDS3.cpp (PS3) and WiiDS4.cpp (PS4). The PS3 controller protocol is based on xerpi's SickSaxis library, as used by Snes9xRX.

Also see
Wii Menu PS3/PS4 Controller: a Priiloader hack that lets the same controllers work as the pointer on the Wii Menu (4.3U).
License

VBAGX is free software under the GNU General Public License, version 2 or (at your option) any later version, and so is this build. See LICENSE.
