## INTRODUCTION

In November 2018, a feature was added to MiSTer to allow the the video scaler to load filter coefficients for arbitary interpolation filters.  This allows MiSTer to scale it's output over HDMI with common image scaling algorithms such as Bicubic as well as other scaling algorithms better suited for enlarging pixel graphics.  Additionally, some special effects such as scanlines and lcd effects can implemented through filter coeffcients.

## HOW TO USE FILTERS WITH MISTER

To use any of the pre-made filter coefficients (or your own) you need

* An updated version of MiSTer.  The first release with support was MiSTer_20181116.
* A supported core.  Most cores released after November 16, 2018 have support for filter coefficients.  This includes SNES, NES, Genesis, Sega Master System/Game Gear, PC Engine/Turbo Grafx 16, and Coleco.   More cores with support will be available in the future.
* At least one set of coefficients in a text file.  Each set of filter coefficients goes in a file with a ".txt" extension.  All of your filters need to be in a /Filters subdirectory of your MiSTer sd card root.

Once you have updated MiSTer and Cores and your filter coefficients in the right place you simply

* Start a supported core
* Go to page 2 of the core's OSD menu and under HDMI Scaler: change the option from "Filter - Internal" to "Filter - Custom"
* The option below "Filter - Custom" should now be enabled and will allow you to choose your filter from the files in your /Filters folder.

## FREQUENTLY ASKED QUESTIONS

Q: Why would I want to use custom filter coefficients?
A: There are many reasons. To get better/different quality than the internal scaler is the main reason. To use scanline or lcd effects is another.

Q: Doesn't MiSTer already have scanlines through the "Scandoubler FX" option in the OSD?
A: Yes, but the scanlines available with "Scandoubler FX" are aligned to the scandoubled image and the scanlines through the filter coefficients are aligned to the original pixels in the scanline.  So you achieve better scanlines with filter coefficients in most cases.

Q: How does this relate to the earlier "coeff.txt" support available in some cores or the "NN" builds that support nearest neighbor scaling?
A: The "NN" builds were hardcoded to perform Nearest Neighbor upscaling only.  Nearest Neighbor scaling is available as a set of filter coefficients.  The "coeff.txt" builds were the frst attempts by Sorgelig to implemment support for custom filter coefficients.  There was no support in the OSD for choosing the filter in these older builds.  These newer builds replace those older builds.

Q: Where do I get sets of Filter Coefficients?
A: Here. Check the Releases folder
