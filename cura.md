# Instructions for Printing with Cura

If you're using the (very excellent) [Cura](https://ultimaker.com/software/ultimaker-cura)
software to slice and print, then these instructions should help you print the PPE Visor.
Please also read the other instructions about printing too though - there's lots of
information in there about safe handling (and safe printing environments), packaging etc.
Since we're trying to prevent the spread of Coronavirus, please make sure you take appropriate
precautions to avoid spreading it on the visor!

## Prepare for Printing

When you open Cura, it should look something like this:

![Cura opening screen](images/cura-initial.png)

I'm assuming you've used Cura before and it's set up for your printer. Next, load the visor
model (File -> Open File -> VISOR.STL). It should look like this:

![Cura model loaded](images/cura-model-loaded.png)

Next, select the printing profile (top right). The default settings for "draft quality" are
ideal for printing the visor (quality isn't that important):

![Select Cura printing profile](images/cura-select-printing-profile.png)

Some changes to the defaults are required:
 * 0.4mm layers
 * 20% infill is the default, but 30% is preferred
 * 60mm/s print speed
 * "skirt" bed adhesion, or no adhesion

Additionally ensure you've selected the correct material to print with (PETG is preferred but
not all printers can print with it, PLA is fine and ABS is also okay). If there are any other
settings you need to use that are specific to your printer then set them now.

The print is big and wide and quite thin - and so very prone to warping. If you have a
heated bed you'll need to use it, otherwise you may need adhesive on the blue painters tape.
Printing with a brim will also avoid warping, but you'll need to remove the brim after
printing (please observe handling precautions!). Ideally print with a skirt or no adhesion
as it means less work after the print is complete, but a warped print is less use than one
that you've had to trim.

Lastly, prepare for printing - press "Slice" (bottom right). You should see something
like this:

![Ready to print](images/cura-ready-to-print.png)

## Printing

In my case I print with Octoprint, but you should use whatever method to print you
normally use.

Each print should take approximately 1 hour 30 minutes, and uses about 4 metres of
3mm filament.
