![issues](https://img.shields.io/github/issues/Unknown6656/AutoIt-Interpreter)
![forks](https://img.shields.io/github/forks/Unknown6656/AutoIt-Interpreter)
![stars](https://img.shields.io/github/stars/Unknown6656/AutoIt-Interpreter)
![repo size](https://img.shields.io/github/repo-size/unknown6656/AutoIt-Interpreter)
![downloads](https://img.shields.io/github/downloads/unknown6656/AutoIt-Interpreter/total)
![license](https://img.shields.io/github/license/Unknown6656/AutoIt-Interpreter)

![Banner image](new/artwork/banner.png)<br/>
![Banner image](new/artwork/banner-features.png)

# Platform-Independent AutoIt3 Interpreter

### [TL;DR: Take a look at the Wiki](https://github.com/Unknown6656/AutoIt-Interpreter/wiki)

AutoIt is a traditionally Windows-only scripting language based on the Visual Basic syntax.
The aim of this repository is to provide an AutoIt3 Interpreter for other platforms, such as Linux/Unix and MacOS.

This repository contains _two_ AutoIt-Interpreters:

 1. [The newer (.NET5-based) **extensible AutoIt3 Interpreter**.](new/readme.md)
    <br/>
    This Interpreter is based purely on .NET5-conform C#/F# code and primarily supports the AutoIt3-specification.
    The Interpreter does support a plugin-based extension system in order to provide a custom syntax or framework functionality to the interpreter.

 1. [The "old" **AutoIt++ Interpiler** written in 2018 (discontinued).](old/readme.md)
    <br/>
    This Interpiler compiles AutoIt++-Code (a superset of AutoIt3) into CIL-code, which can be executed on any platform supporting .NET.
    <br/>
    Truth be told, the Interpiler is not super stable on non-Windows platforms, and has therefore been discontinued.


#### Comparison:

Category | [new AutoIt3 Interpreter](new/readme.md) | [old AutoIt++ Interpiler](old/readme.md)
---------|---------------------|--------------------
Supported Language| Strict AutoIt 3<br/>with extension support | AutoIt 3<br/>AutoIt++ 
Works as an ... | Interpreter | Interpiler/Transpiler:<br/>60% compiler, 30% interpreter, 10% magic 
Written in | C#, F# | C#, F#
Target Framework | .NET 5 and newer | .NET Core 2.1
Works on Windows | Hell yeah | Yup
Works on Linux | Yes, but not tested thoroughly | Kinda
Works on MacOs | Yes, but not tested thoroughly | Kinda
Status | [In development](https://github.com/Unknown6656/AutoIt-Interpreter/projects/1) | Discontinued, Beta-ish

## Links

 - [Wiki](https://github.com/Unknown6656/AutoIt-Interpreter/wiki)
 - [Code Overview](./new)
 - [.NET 5 developement progress](https://github.com/Unknown6656/AutoIt-Interpreter/projects/1)
 - [Issues](https://github.com/Unknown6656/AutoIt-Interpreter/issues)
 - [Official AutoIt3 documentation](https://www.autoitscript.com/autoit3/docs/)

### Old Links

 - [**Old** Code Overview](./old)
 - [**Old** Usage page](old/doc/usage.md)
 - [AutoIt++ Language reference](old/doc/language.md)
 - [AutoIt++ Syntax reference](old/doc/syntax.md)
 - [AutoIt++ Runtime behaviour](old/doc/runtime.md)
 - [AutoIt++ Syntax tree reference](old/doc/syntax-tree.md)

## Maintainer(s)

 - [@Unknown6656](https://github.com/Unknown6656)
 - ([@Zedly](https://github.com/Zedly) / [@wickersoft](https://github.com/wickersoft) in assistive and advisory function)

## License
The code is licensed under the Giant Penis License (GPL), which is a more restrictive version of the MIT License. [Click here](https://github.com/Unknown6656/AutoIt-Interpreter/blob/daddy/LICENSE.md) for more information.
