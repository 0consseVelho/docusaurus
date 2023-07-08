
 
# How to Decompile GameMaker 8.x Executables with OpenGMK
 
If you have ever wanted to reverse engineer a game made with GameMaker 8 or 8.1, you might have encountered some difficulties. GameMaker 8 executables are protected by a virtualisation layer that makes them hard to disassemble or debug. Moreover, the game assets are stored in a compressed and encrypted format that is not easy to extract or modify.
 
**Download Zip ……… [https://t.co/VcXoTbQHhq](https://t.co/VcXoTbQHhq)**


 
Fortunately, there is a tool that can help you decompile GameMaker 8 executables and restore them to their original project files. It's called OpenGMK, and it's an open-source decompiler for GameMaker 8.x executables. OpenGMK can revert any game back to .gmk or .gm81 format respectively, preserving all the sprites, sounds, scripts, rooms, objects, and other resources.
 
In this article, we will show you how to use OpenGMK to decompile GameMaker 8 executables and explore the game's source code. We will also explain how OpenGMK works and what features it offers.
  
## What is OpenGMK?
 
OpenGMK is a project that aims to reimplement the GameMaker Classic engines, providing a full sourceport of the runner, a decompiler, a TASing framework, and libraries for working with gamedata yourself. It's written in Rust, a fast and safe programming language that guarantees memory safety and concurrency.
 
OpenGMK was originally a fork of Zach Reedy's gm81decompiler, which was a decompiler for GameMaker 8.1 executables. However, gm81decompiler had some limitations and bugs that made it unreliable and incomplete. For that reason, the developers of OpenGMK decided to create their own decompiler from scratch, using Rust as the language of choice.
 
OpenGMK has several advantages over gm81decompiler and other similar tools. It supports both GameMaker 8 and 8.1 executables, it's much faster and more accurate, it can handle more games and edge cases, it can fix broken events and deobfuscate code, it has a user-friendly interface and command-line options, and it's open-source and actively maintained.
  
## How to use OpenGMK?
 
Using OpenGMK is very simple and straightforward. You just need to download the latest release from the GitHub repository (https://github.com/OpenGMK/GM8Decompiler/releases) and extract the zip file. You will find an executable file called gm8decompiler.exe (or gm8decompiler if you are on Linux or Mac).
 
How to use GM8Decompiler to revert GameMaker 8.x executables[^1^],  OpenGMK: a modern rewrite of the GameMaker Classic engines with a decompiler[^2^],  Download the latest release of GM8Decompiler from GitHub[^3^],  How to decompile GameMaker Studio games with Altar.NET,  What is the difference between GM8Decompiler and gm81decompiler,  How to fix broken events and deobfuscate code with GM8Decompiler[^3^],  How to play games with GM8Emulator that require 32-bit DLLs on Windows 64-bit[^2^],  How to build OpenGMK from source code on Windows, Linux and Mac[^2^],  How to use gml-parser library to parse and compile GML code,  How to create TAS videos with OpenGMK and Hourglass,  How to edit gamedata files with gm8exe and gmktool,  How to run GameMaker 6.x and 7.x games with OpenGMK,  How to convert .gmk or .gm81 files to .gmz or .yyp files,  How to use GameMaker Decompiler by Zach Reedy,  How to protect your GameMaker games from decompilation,  How to report bugs and contribute to OpenGMK project[^2^],  How to use GameMaker Unpacker by YellowAfterlife,  How to use UndertaleModTool to decompile and mod Undertale,  How to use GMLive by YellowAfterlife to edit GML code live,  How to use GML Transpiler by JujuAdams to convert GML code to other languages,  How to use GML Snippets by JujuAdams to write better GML code,  How to use GML Lint by JujuAdams to check GML code for errors and warnings,  How to use GMLDoc by YellowAfterlife to generate documentation for GML code,  How to use GMLive++ by PixelatedPope to debug GML code live,  How to use GMSDB by PixelatedPope to browse GameMaker Studio database files,  How to use GMS2 Decompiler by PixelatedPope,  How to use GMS2 Runner Extractor by PixelatedPope,  How to use GMS2 Asset Browser by PixelatedPope,  How to use GMS2 Datafile Editor by PixelatedPope,  How to use GMS2 Project Merger by PixelatedPope,  How to use GMS2 Project Cleaner by PixelatedPope,  How to use GMS2 Project Backup Tool by PixelatedPope,  How to use GMS2 Project Converter by PixelatedPope,  How to use GMS2 Project Updater by PixelatedPope,  How to use GMS2 Project Analyzer by PixelatedPope,  How to use GMS2 Project Optimizer by PixelatedPope,  How to use GMS2 Project Refactorer by PixelatedPope,  How to use GMS2 Project Formatter by PixelatedPope,  How to use GMS2 Project Validator by PixelatedPope,  How to use GMS2 Project Debugger by PixelatedPope,  How to use GMS2 Project Profiler by PixelatedPope,  How to use GMS2 Project Tester by PixelatedPope,  How to use GMS2 Project Builder by PixelatedPope,  How to use GMS2 Project Exporter by PixelatedPope,  How to use GMS2 Project Importer by PixelatedPope
 
To decompile a GameMaker 8 executable, you just need to drag and drop it onto the gm8decompiler.exe file. Alternatively, you can open a terminal window and run the following command:
  `gm8decompiler.exe path/to/game.exe`  
This will start the decompilation process and create a folder with the same name as the game executable in the same directory. Inside this folder, you will find the restored project file (.gmk or .gm81) and a subfolder called "assets" that contains all the extracted resources.
 
You can then open the project file with GameMaker 8 or 8.1 (or any compatible editor) and explore the game's source code. You can also modify the game as you wish, as long as you respect the original author's rights and license.
  
## What are some of the features of OpenGMK?
 
OpenGMK has many features that make it a powerful and versatile tool for decompiling GameMaker 8 executables. Here are some of them:
 
- It supports both GameMaker 8 and 8.1 executables, as well as games with foreign locales.
- It can handle games with multiple frames of collision, window icons, FFI functions, lazy loading, etc.
- It can fix events that are "broken" (non-editable) in the original game.
- It can deobfuscate code that was obfuscated by tools like GMProtect or Enigma Virtual Box.
- It has a fast and efficient algorithm that can decompile games in seconds.
- It has a friendly interface that shows the progress and status of the decompilation.
- It has command-line options that allow you to customize the decompilation process.
- It's open-source and constantly updated with new 8cf37b1e13


