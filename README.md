# colorForth
Native colorForth for 32-bit PCs, at least compilable on Linux and runnable on both Bochs and Qemu.
It is adapted from http://sourceforge.net/projects/colorforth.

Purpose of this fork
--------------------

This fork aims to run colorForth under qemu (limbo) on Android.  
For now, the only change is to use the B key as an Alt Gr alternative.

![colorForth](https://raw.githubusercontent.com/pbrochard/colorForth/master/screenshots/colorForth_Android_Qemu_Limbo.png "colorForth on Android - Qemu")
![colorForth](https://raw.githubusercontent.com/pbrochard/colorForth/master/screenshots/colorForth_Android_Qemu_Limbo_Details.png "colorForth on Android - Qemu")

Running
-------

Get sources:

    $ git clone https://github.com/narke/colorForth.git

Compile:

	$ make

Run on Bochs:

	$ make bochs

On Bochs prompt type 'c' to continue the execution.

Or run on Qemu:

    $ make qemu

On Bochs:
![colorForth](https://raw.githubusercontent.com/narke/colorForth/master/screenshots/colorforth_bochs.png "colorForth on Bochs")

On Qemu:
![colorForth](https://raw.githubusercontent.com/narke/colorForth/master/screenshots/colorforth_qemu.png "colorForth on Qemu")

# License

It's in public domain.
