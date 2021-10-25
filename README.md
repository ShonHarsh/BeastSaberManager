# **BeastSaberManager**

```
This is still in early development stages.  The discovery and download are working but will likely still be refactored and documented.
```

This manager serves to make downloading songs for Beat Saber from Beast Saber easier.

##### GETTING STARTED

After making a pull request or downloading the project, open the Main.xaml in UiPath Studio.  The robot can be run with the play button in the ribbon and the result can be seen in output pane.

##### DETAILS

**BeatSaber-Manager-Discovery**

The discovery gets the song title and download URL then adds a column ToDownload.  This column will be used to use for download procedure.

**BeatSaber-Manager-Download**

Download desired songs that have ToDownload set to "TRUE".  True is the default value set in the discovery routine.

**BeatSaber-Manager-Reswizzle**

This is yet to be implemented but the relation to the downloaded folder to the in game file is not always clear.   Some possibilities for enhancement are:

- Get the information from the info.dat file and validate online
- Rename file folder
- Option to remove custom color blocks

- Reformat info.dat file to a structured JSON file

##### NOTES

And error notes, spelling fixes and other comments are very welcome!

### Requirements

[UiPath Studio](https://www.uipath.com/product/studio) is required to run the robot.

### Git Notes

Clone the project to develop or change it.

`git clone https://github.com/ShonHarsh/BeastSaberManager`

### Links

[UiPath: Automation Platform](https://www.uipath.com/)

[UiPath Studio](https://www.uipath.com/product/studio)

[My Website](https://shonharsh.github.io/curriculum-vitae/index.html)

