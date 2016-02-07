# AndroidSwissEphemerisExample

This is an example of how to include Thomas Mack's Java Swiss Ephemeris (http://www.th-mack.de/international/download/index.html) .jar file in an Android Studio Project using contributed code http://www.th-mack.de/download/contrib/android_swisseph.zip.

As far as I can tell all you need to do is put the swissephSWI-2.00.00-01.jar file in the app/libs directory.

And the line https://github.com/AaronNGray/AndroidSwissEphemerisExample/blob/master/app/build.gradle#L23 will include the library automatically.

Modified https://github.com/AaronNGray/AndroidSwissEphemerisExample/blob/master/app/src/main/java/org/swissephemeris/swissephemeris/Chartdata.java to give topocentric values.
