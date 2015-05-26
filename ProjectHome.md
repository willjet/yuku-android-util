Android utility and widget libraries for our projects, not really meant to be open source,  hence the commits are very arbritrary, but they MIGHT be useful for your projects or for your reference.

Projects as of Feb 2013:

  * `ATree` TreeView for Android, based loosely on Java Swing's JTree, but without TreeModel. This can be used to implement a tree for browsing folders, etc.
  * `AmbilWarna` Color picker dialog. Main page: http://code.google.com/p/android-color-picker/
  * `AndroidCrypto` supposed to be crypto lib but oh well.
  * `BintexReader` and `BintexWriter` read/write binary data and for serializing various types.
  * `EasyBilling` Put in-app billing on your app SUPER EASILY!!! (But now a better and easier API has been released by Google)
  * `FileChooser` Activities for opening/saving files, and choosing folders using tree view. Similar to `OpenFileDialog`, `BrowseForFolder`, etc.
  * `FlowLayout` A layout that fills in controls until it can't fit in a single line, then it wraps to the second line, etc. Based on devoxx code with modifications (the devoxx codes are buggy!)
  * `IconContextMenu` Why can't we have icons in a context menu? With this you can. Main page: http://code.google.com/p/android-icon-context-menu/
  * `MultiGestureDetector` Detect the following gesture easily: drag, rotate, pinch, tap, double-tap, flick. Based on deadpixel.ca.
  * `Salsa20` Implementation of [Salsa20](http://cr.yp.to/salsa20.html) cipher (seems to be better and faster than AES) in pure Java and native code.
  * `SdkSearchBar` Search bar stolen from private resources of Android 2.2. Added OnSearchListener etc. Also contains SearchWidget, that transforms to a grey search bar on Android < 3.0, and the nice SearchView otherwise. Please take a look at `ActionBarSherlock`'s `SearchView` too, it is better.
  * `Snappy` Implementation of Snappy fast compression library created by Google in pure Java and native code. https://code.google.com/p/snappy/  Based on 3rd-party codes [pure Java](https://github.com/xerial/snappy-java) and [C89](https://github.com/andikleen/snappy-c) with modifications.
  * `SimpleTrove` A modification of [GNU Trove](http://trove.starlight-systems.com/) for less footprint. Retained only int and long primitives. Removed decorators, synced and unmodifiable variations, and custom-hash related classes.

This repository also contains (some original, some patched) free 3rd party codes which I don't claim ownership or authorship to.