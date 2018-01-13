# AudioEffectsSuite
A Suite of C++ Audio Effects Classes

### Overview
This repository collects together a set of Audio DSP Effects with heavy emphasis on modularity 
and class inheritance coded in a modern C++ style.

### Contributors
The Contributors folder is a space for contributors to the repository to prototype and easily
collaborate on effects under construction.

### AudioIOClasses
The AudioIOClasses allow for easy command line audio file read and write capability and limited playback
fascilities. These are to assist in prototyping effects. As such, read and write is limited 16 bit WAV files
and audio playback is currently only capable on macOS with COreFoundation and AudioToolbox frameworks.

### BaseClasses
BaseClasses folder consists of base classes for particular branches of audio effects.
