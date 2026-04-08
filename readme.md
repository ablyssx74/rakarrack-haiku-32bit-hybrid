### Rakarrack Haiku 32bit hybrid is a port in progress of the great [rakarrack project](https://rakarrack.sourceforge.net/)

Requires: fltk_x86_devel libsample_x86_devel libsndfile_x86_devel libxfont_x86_devel libxfont2_x86_devel libxpm_x86_devel

To configure run ```make -f haiku.makefile config ```

To build run ``` make -f haiku.makefile ``` 

If build goes all okay you will have ./rakarrack in the root directory 

To clean the build run ``` make -f haiku.makefile clean``` 

Known Bugs:

My test env was on virtualbox with the latest Haiku 32bit hybrid
FLTK caused a segfault with my test build.  
Using ```rakarrack --no-gui``` ran with no segfault but I could not hear the audio playback. 


Notes: <br>

Update Input/Output frequency in Haiku Media Preferences to match 48kHz if engine is built to use 48kHz<br><br>


