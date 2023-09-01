# BEST Robotics 2020 Code - Outbreak
Robot code and other tools created for the 2020 BEST Robotics competition "Outbreak"

⚠️ Code is not well documented. ⚠️

## Files

#### recording.c

The robot code used for recording user inputs to be played back for the autonomous task.

(Output can be found in RobotC under `Robot > Debugger Windows > Debug Stream`. If you don't see this option, check that the menu level is set to Super User under `Window > Menu Level`.)

#### data_parser.html

Converts the output from the debug stream recording into usable code to be pasted into `playback.c`. Open in web browser.

#### playback.c

The robot code used for playing back the user inputs for the autonomous task and used for the BEST competition.

## Areas To Improve

- Documentation is non-existant.
- Recording and playback being separated into multiple files is a hassle to maintain and any changes to one must be manually reconciled with the other.
- Code could be greatly simplified, especially if statements in robot code.
- The HTML file is very poorly written with inline JavaScript that should be moved to functions.
