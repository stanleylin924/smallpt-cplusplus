smallpt-cplusplus
==============

smallpt: Global Illumination in 99 lines of C++ 
(http://www.kevinbeason.com/smallpt/)

This is a simple 'port' of Kevin Beason's smallpt to make it run on Windows via Visual C++ and Visual Studio 2022. Please visit Kevin's site for more information.  

My purpose is to have a comparison point as I'm going to port the code over to C# (http://github.com/randyridge/smallpt-csharp) and refactor for my own amusement and education...  This is similar to what Ronald Chen did in Java (http://pyrolistical.github.com/smallpt/).

I made a few modifications which increased line count to 105, they are all noted with comments starting with // ***.  I've also supplied a compiled version of smallpt.exe for Windows.  Also, on Windows you may need an application to view the .PPM file output...

For handy timing use the following from PowerShell:
Measure-Command {.\smallpt.exe 5000}

Please note that running 5000 samples will take quite a long time (perhaps start with a much lower number) and I've disabled status indicators.
