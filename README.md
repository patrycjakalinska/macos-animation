react-native-macos used depracated funtion which resulted in returning a timestamp of 0. Replacing it with current up-to-date function solves the issue.

To see reproduction please remove patch provided for `react-native-macos`.


Patch for Reanimated needs to be applied, as it adjusts one of our functions to work on macos.
