react-native-macos used depracated funtion which resulted in returning a timestamp of 0. Replacing it with current up-to-date function solves the issue.

To see reproduction please remove patch provided for `react-native-macos`.


Patch for Worklets needs to be applied, as it adjusts one of our functions to work on macos.


sorry for the commit mess, repro commited without .gitignore ;)
