Version 0.7

What does it do
Externally scan a process for signatures and dump the relative offsets to a header file which is easy to incorporate into your Visual Studio project. When an update is released for a game, you run the dumper to get the latest offsets.

Why
Scrubs don't know how to pattern scan so they manually update their offsets in their game hacks after running an offset dumper like this.

How to use
Put an updated config.json in the same folder as GH-Offset-Dumper.exe
Run the game
Run the dumper
Include the .h file which gets generated into your project
How is this different from HazeDumper?
This dumper was inspired by hazedumper so thank you to frk1, rN' and the other contributors to that project.

I started learning Rust when messing with HazeDumper and I decided we needed a C++ version, I also wanted to extend the functionality.

GH Dumper will do the same thing as HazeDumper with the addition of dumping ReClass files and Cheat Engine Tables.

Our dumper uses the same json config file format, so they are interchangeable

Notes
Ignore the files in the modules folder, these are just modules from my framework which I use to do some of the background stuff.

The main code is GHDumper and SrcDumper

TODO
Reduce bloat from modules folder
Improve CE Output
Add ReClass.NET output
Turn into a lib which can be incorporated into hacks
Make an internal version
Seperate CSGO vs regular functionality
Add CSS functionality
organize output of offsets or put comments showing what module they are for and what base object
Other ideas to make it kewl
Credits
Thank you to frk1, rN' and the contributors to hazedumper

Thank you to hjiang and the contributors of jsonxx

Official GH Courses
The Game Hacking Bible - a massive 70 chapter Game Hacking Course
Computer Science 420 - an eight chapter lecture on CS, Data Types & Assembly
Binary Exploit Development - a 9 chapter series on exploit dev from a certified OSED
Game Hacking Shenanigans - a twenty lesson Cheat Engine hacking course
Python Game Hacking Course - 7 chapter external & internal python hack lesson
Python App Reverse Engineering - Learn to reverse python apps in 5 lessons
Web Browser Game Hacking - Hack javascript games with this 4 chapter course
Roblox Exploiting Course - 7 Premium Lessons on Hacking Roblox
Java Reverse Engineering Course - 5 chapter beginner guide
Java Game Hacking Course - 6 Chapter Beginner Guide
