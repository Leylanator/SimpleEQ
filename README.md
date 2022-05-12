# SimpleEQ
A simple EQ plugin I'm using to learn the JUCE Framework and programming DSP in C++

It is a Work in Progress, I intend to add a custom GUI at some point.

The process to install would be to git clone the URL this is hosted on into a sensible folder, open up an up-to-date PROJUCER session by running the .jucer file in the folder to provide the library code. You will want to set the exporter to your what will work on your native OS. You'll then use this to compile it on your device.

On Unix-like OSes, a makefile is used (though you can use Code::Blocks, if you wish); you'll want to build by navigating to the Builds/LinuxMakeFile folder (where the makefile is) in your terminal of choice, issuing a `make` command, and then move the .so file to the folder you keep your vst3 files in. Then update your DAW/plug-in interface to use it.
On macOS or Windows, you'll have to add Xcode or VSCode/Code::Blocks as an exporter to compile the vst.
