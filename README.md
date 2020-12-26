# DisplayBrightnessConsole

You will need the Microsoft .NET Framework 2.0 or greater for the app to work.

To use the console app, the following parameters are allowed:
DisplayBrightnessConsole.exe This will return the current brightness level.

DisplayBrightnessConsole.exe -getlevels This will return all possible brightness levels accepted by the display, separated by a new line.

DisplayBrightnessConsole.exe 20 (or some other brightness level number) This will set the brightness level of the display to the parameter given, in this case, 20.

The code currently only works on single-display systems. If your system has more than one display, it will only work on the first (generally primary) display. It should be fairly easy to modify it to support more.
