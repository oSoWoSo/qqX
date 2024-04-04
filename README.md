# qqX

## " quickemu quickget X terminal project "

1.6.02 introduced a new Custom Boot system that can run Arm64, Risc-V and others.

Release [1.7.01](https://github.com/TuxVinyards/qqX/releases/tag/1.7.0.02) has lots of new interface features and is now good to go :rocket:

It also fixes the minor glitch in the 1.6 installer that some may have noticed. Apologies if you were affected.

However, explanation [Wiki](https://github.com/TuxVinyards/qqX/wiki) pages do need to be added over the next few days before going to general release.

To upgrade from 1.6, make sure 'BetaUpdates' are enabled in the qqX main settings.

## Quickemu Virtual Machine Manager - A Safe and Powerful TUI

- Full process & version controlled wrapping of both Quickemu & Quickget

- Desktop Integrated. Works safely alongside other existing GUI installations

![qqX-vmm](https://github.com/TuxVinyards/qqX/assets/3956806/18e5c495-8072-49a5-8b9c-e1302549efcf)

- Simple translatable interface > [Translation Wiki](https://github.com/TuxVinyards/qqX/wiki/Translation)

## Why quickemu?

[Quickemu](https://github.com/quickemu-project/quickemu) is simply built and easy to use.

It has an active community and is the only virtual machine manager that makes easy work of running Microsoft Windows.

VirtualBox was good in its day.  Developers are now moving to QEMU <https://qemu.readthedocs.io>

Qemu front-ends based on LibVirt can be quite abstract and complex, for example Virt Manager.

Gnome Boxes (with QEMU) has a very polished interface. But even something simple like moving the VM folder has a learning curve. Forget anything more complex unless you wish to become an expert in xml, gnome3 & vala : <https://gitlab.gnome.org/GNOME/gnome-boxes/-/tree/main/src?ref_type=heads>

Quickemu is not without its flaws. But its flaws can be fixed and it can be made to work.

## Why qqX?

qqX offers an alternative menu system to the traditional quickemu interface.

- It has lots of power and functions. More even than quickemu.

- An easy installation with no additional software or dependencies required.

Quickemu works on the command line and traditionally has had a simple menu interface called quickgui.

- qqX is fully compatible with [quickgui](https://github.com/quickemu-project/quickgui) if is already installed on your system.

Safely test out the qqX difference. Give your existing quickgui VM's a power up with qqX's multiple display modes, utilities, optimizers and tools...

### Not just a text interface

Less can be more. By using the same, simple and well-known scripting language that is used by quickemu, qqX is able to achieve complete quickemu script absorption and modding.

![new -vm-selector-qqX](https://github.com/TuxVinyards/qqX/assets/3956806/42a4b480-4d7d-47fe-91f5-0069fa1511a8)

qqX goes far beyond being a simple front-end that is restricted to the basic quickemu API. Anything within quickemu can be easily pulled, shaped and improved.

Release 1.7.01 now has a choice of 5 menu styles and of  [Custom Menus](https://github.com/TuxVinyards/qqX/wiki/Custom-Menus) :rocket:

![vm-small-d](https://github.com/TuxVinyards/qqX/assets/3956806/1a17b7d7-d6e3-471a-a934-e3530f6c9b17)

### Install the latest ISO's at the click of a mouse

![right-click-iso](https://github.com/TuxVinyards/qqX/assets/3956806/23dd984c-8119-4d8a-b486-c26ac7bf21bb)

No need to wait for Quickget to add in the distros you want, or to update its release data.

### Get the latest fixes too

There is no needed to wait for official bug fixes to make their way through the system either. Any new input from the quickemu community activity can be directly accessed and put to work.

Confident Linux users should quickly find themselves at home.

### Work continues

Release 1.1.01 improved the front end machine selector & makes clearer folder organisation:

Release 1.1.03 improved the main menu & added a gtk display option, while 1.5.02 now has GL toggle:

![ubuntu-qqX-zsync](https://github.com/TuxVinyards/qqX/assets/3956806/c3104e5d-c008-4dbc-9666-42d13d2af357)

Earlier releases have added:

- qcow2 repair & resize

- configuration tune-up wizard

![Screenshot at 2023-02-22 12-59-04-1920](https://user-images.githubusercontent.com/3956806/220619057-f63883d2-4d0d-4130-94e1-d444f1567be4.jpg)

Release 1.1.05, added an extra layer of qemu-img disk health checks to the disk info function. Picture of it working lower down, in the release notes section.  Disks can go wrong. 👍 Give it a try.

Plus:

- Quick screen percentage switching (default & individual)

- Easy secondary storage creation

- Multiple snapshot management, including of shared disks.  

Release 1.5.02 added alphabetical zooming into list sections for the Quick Get multi distro menu:

![alpha-zoom-qget](https://github.com/TuxVinyards/qqX/assets/3956806/bfde0aef-9094-443d-a11d-5bd6745e5702)

Easy process controlled, progress reporting, distro downloads. Time reporting on zsync development iso's.  

- Clear fully annotated and Shellcheck linted scripting

- Extra process logging and diagnostics

- Full MSRS controls.

- Guided settings editor and auto-update checker

## How to Install

qqX will work happily alongside quickgui or any quickemu shortcuts. But these are not necessary. 

Start from scratch. Or safely test out the qqX difference on your existing quickgui VM's  

- If you don't already have a standard Quickemu setup, start by installing that, complete with all its components and all its dependencies, as in the instructions on the [quickemu-project pages](https://github.com/quickemu-project/quickemu) . 
  
  You must be able to type `quickemu` at a command prompt and get the quickemu usage screen.

- Download qqX. The latest release is available [here](https://github.com/TuxVinyards/qqX/releases/latest). You can also make your first download via the **code/clone** button. The 'dev' branch may newer and may have the very latest tweaks and bug fixes too ...

  No other software, support structures or dependencies are needed.

Installing qqX will give you new display modes, utilities, optimizers and tools that can be used on any setup that you have already created.

See the Wiki for [more details](https://github.com/TuxVinyards/qqX/wiki)

## FAQs and Help

See Wiki <https://github.com/TuxVinyards/qqX/wiki/FAQs-and-Help>

## Release notes

Testing has been carried out on a variety of mainstream distros.

All scripts have been carefully Shellcheck linted & have full error handling routines.

qqX always makes backups, as is *standard good practice* with *any* software.

More details in the [change log](https://github.com/TuxVinyards/qqX/wiki/Change-Log)

Feedback, positive or constructive, at <https://discord.gg/sNmz3uw>

## Development

You can easily run any new version of qqX directly from the working folder when making clones of the repo to your local machine.  By default, this will pick up the main settings file at `~/.qqX` and automatically locate all your current VMs.

qqX has several layers of backup and fail safe, however do backup critical VMs if tinkering with these systems.

You are recommended to place any development changes to the settings file into a single block so that they can be easily pasted back after carrying out release upgrades to your main qqX installation.

Whilst the release installer will automatically backup your settings file, part of the update procedure is the removal of obsolete and unneeded lines. This will cause a temporary removal of any changes that you may have made.

The code has now been refactored to make readability easier on notebooks and smaller height screens. Release 1.5.02, even with its new added features and script, is more compact and around 500 lines shorter ... :rocket:

## Bash

Learning Bash, or improving your knowledge of it, is always time well spent. Bash is a flexible language of which all Linux users should know at least a little. There are none of steep learning curves that are often involved with GUI's

Use of a clear and well annotated qqX coding style means that even Bash novices should be able to find their feet. Any confident Linux user should find it relatively easy to make simple edits.

## why 'X' ?

More technically speaking qqX runs in a 'terminal emulator' and can also run with Wayland display systems as well as with 'X'

But traditionally Linux uses the X window system from X.org, so 'X term' often gets used as shorthand ...

<https://en.wikipedia.org/wiki/X_Window_System>

<https://en.wikipedia.org/wiki/Wayland_(protocol)>
