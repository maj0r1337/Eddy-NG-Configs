## Eddy-NG-Configs

## Some basic but working Configs for Vlads Eddy NG App for Sovol SV08

---------------------------------------------------------------------

[ALL CREDITS TO VLAD AND HIS GREAT PROJECT!](https://github.com/vvuk/eddy-ng). PLZ SUPPORT HIM AND HIS ALIEXPRESS HABITS ;)

My Project includes my Configs that i've costumized from Rappetor's [Mainline Klipper Repo](https://github.com/Rappetor/Sovol-SV08-Mainline).

I've merged Nadirs Eddy NG Macros in to my Configs. You'll find  [Nadirs original Post on Printables](https://www.printables.com/model/1269473-btt-eddy-ng-macro-my-print-start-on-my-sv08).

## I'd like to thank Vlad, Rappetor and Nadir for their great Work!

[![Sovol SV08 Eddy NG Tap installieren [GER]](https://i3.ytimg.com/vi/4r2YzVSAbks/maxresdefault.jpg)](https://youtu.be/4r2YzVSAbks)

----------------------------------------------------------------------
## Klipper Fix for the Z-Offset Issue with the SV08

- Download the Z-offset Python script from the folder (Z-Offset Fix) above and save it to your desktop.
- Connect to your SV08 via FTP. The FTP port is 22, the username and password are "biqu".
- Go to the eddy-ng directory (/home/biqu/eddy-ng) and back up the original probe_eddy_ng.py file safely to your PC.
- Now, drag and drop my probe_eddy_ng.py file into the open directory on the FTP Client (/home/biqu/eddy-ng), overwrite the existing file.
- Reboot the printer, done!

Congratulations! Your SV08 will now lower his print head from over 7 cm down to just above the build plate again, correctly calculating the true zero position.

### This fix is not my work! All credits are going to [RagDollino](https://github.com/vvuk/eddy-ng/issues/146#issuecomment-4628777151) and [Lupolima](https://github.com/vvuk/eddy-ng/issues/153#issuecomment-5376480786)
