# Emerald Launcher [![codebeat badge](https://codebeat.co/badges/99f8e462-4277-422f-a077-72769c740a45)](https://codebeat.co/projects/github-com-henridellal-emerald-master)

Emerald is a simple home screen for Android phones. It aims good performance while providing basic customization support.

## Downloads
[F-Droid](https://f-droid.org/packages/ru.henridellal.emerald)

[Google Play](https://play.google.com/store/apps/details?id=ru.henridellal.emerald)

## Features
- Icon pack support;
- App and web search;
- App categories;
- History of last launched apps;
- Resizeable layout.

## To do
- Shortcuts;
- Oreo icons and package service;
- Some bug fixes and improvements.

## How to use
- Swipe left or right to switch categories;
- Tap on category name to see the list of categories.

## How to compile
There are multiple options:
- Gradle;
- In Termux:

Some packages should be installed
`$ pkg install aapt apksigner dx`
If your Android version is 7.0 or higher
`$ pkg install ecj`
Otherwise
`$ pkg install ecj4.6`
Then navigate to the emerald project folder and run the script (it is recommended to edit paths in it first)
`$ chmod u+x termux-build.sh`
`$ ./termux-build.sh`

## Questions and answers
##### Is it possible to use Emerald as an app drawer?
Yes.
##### Will Emerald Launcher support widgets?
The launcher is most likely not to introduce widgets in future updates.