R2D2Soundboard
================
A simple soundboard R2D2 application for Android, based on Caleb Sabatini's "android-SoundBoard" app. 

Here's a link to his repo.

https://github.com/csabatini/android-Soundboard

Usage
----
To add your own audio clips, place them in in the res\raw directory.

Then, update the arrays in res\values\arrays.xml with labels and resource IDs. Example:

```xml
...
<string-array name="labels">
    <item>One</item>
    <item>Two</item>
    <item>Three</item>
    ...
</string-array>

<integer-array name="ids">
    <item>@raw/one</item>
    <item>@raw/two</item>
    <item>@raw/three</item>
    ...
</integer-array>
...
```