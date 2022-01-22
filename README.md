# Programming_Resources
Links to varies resources regarding mostly Programming (System Programming, Kernel, OS, Algorithms, Rendering etc)  
Many links also include discussion on HackerNews (HKN links), that additionally expands information about those resources.

# Table of Contents
- [Low Level Programming](#low-level-programming)
- [Compilers](#compilers)
- [Kernels, emulators and OS programming](#kernels--emulators-and-os-programming)
  * [Zig](#zig)
  * [C/C++](#c-c--)
  * [Forth and others](#forth-and-others)
- [Small, low memory programs](#small--low-memory-programs)
  * [C](#c)
  * [Debugging](#debugging)
  * [GUI](#gui)
  * [Assembly](#assembly)
- [Standalone libraries with single header (STB like)](#standalone-libraries-with-single-header--stb-like-)
- [Electronics / computers from scratch / FPGA](#electronics---computers-from-scratch---fpga)
- [General Programming](#general-programming)
  * [Javascript / WEB](#javascript---web)
  * [Powershell](#powershell)
  * [Rust](#rust)
  * [WebAssembly](#webassembly)
  * [Net C#](#net-c-)
  * [Python](#python)
  * [General links to programming language pages:](#general-links-to-programming-language-pages-)
  * [Others](#others)
  * [Projects](#projects)
  * [Deep learning/Neural Networks](#deep-learning-neural-networks)
  * [Interesting Libraries](#interesting-libraries)
- [Graphics and game programming](#graphics-and-game-programming)
  * [Graphics / Shaders](#graphics---shaders)
  * [Game engines](#game-engines)
  * [Graphics engines / renderers](#graphics-engines---renderers)
  * [Raytracing](#raytracing)
  * [Games](#games)
  * [Procedural](#procedural)
  * [Server/Client architecture](#server-client-architecture)
  * [Graphics libraries](#graphics-libraries)
  * [Resources and tools for assets](#resources-and-tools-for-assets)
  * [Others](#others-1)
- [Algorithms](#algorithms)
  * [General](#general)
  * [Text Editing](#text-editing)
- [Operating Systems](#operating-systems)
  * [Windows](#windows)
  * [Linux](#linux)
  * [Terminals tools and programming](#terminals-tools-and-programming)
  * [Other tools/programs](#other-tools-programs)
- [EMBEDDED](#embedded)
  * [RaspberryPi](#raspberrypi)
- [Others:](#others-)
  * [Zig](#zig-1)
  * [C](#c-1)
  * [Others](#others-2)
  * [Useful tools/programs](#useful-tools-programs)
  * [Small hints/links](#small-hints-links)
  * [Books](#books)
  * [Learning tools / CS Cources](#learning-tools---cs-cources)
  * [BLOGS](#blogs)
  * [Conferences](#conferences)
  * [Others](#others-3)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>


====================

## Low Level Programming

----
## Compilers
Small scripting language in C
[LINK](https://github.com/bamless/jstar)

TinyCC, has small busybox and gmake compilation step
[LINK](http://download.savannah.gnu.org/releases/tinycc/)
[HKN](https://news.ycombinator.com/item?id=26141124)

Elk: A low footprint JavaScript engine for embedded systems 
[LINK](https://github.com/cesanta/elk)
[HKN](https://news.ycombinator.com/item?id=28614092)

Small JS engine for embedded devices
[LINK](https://github.com/jerryscript-project/jerryscript)
[HKN](https://news.ycombinator.com/item?id=25881366)

C based Javascript interpreter for low memory embedded devices
[LINK](https://github.com/espruino/Espruino)

LISP with GC in 436 bytes
[LINK](https://justine.lol/sectorlisp2/)
[HKN](https://news.ycombinator.com/item?id=29630293)

A work-in-progress C compiler from scratch
[HKN](https://news.ycombinator.com/item?id=28048528)
[LINK](https://github.com/riicchhaarrd/ocean)

Compilers are hard
[LINK](https://blog.shipreq.com/post/compilers_are_hard)
[HKN](https://news.ycombinator.com/item?id=25831911)

Bootstrapping GCC from machine code
[LINK](https://github.com/fosslinux/live-bootstrap)

List of links for creating compilers and interpreters
[HKN](https://news.ycombinator.com/item?id=23441767)

First C compiler
[HKN](https://news.ycombinator.com/item?id=26419628)

Standalone compilation hack library for C
[HKN](https://news.ycombinator.com/item?id=25556286)
[LINK](https://justine.lol/cosmopolitan/index.html)

Small C compiler - will have a book written about how to make it:
[LINK](https://github.com/rui314/chibicc)

Full Fortran in WASM
[LINK](https://github.com/StarGate01/Full-Stack-Fortran)

Creating interpreters:
[LINK](https://craftinginterpreters.com/contents.html)

CPU optimization blog
[LINK](https://www.agner.org/)  




## Kernels, emulators and OS programming
How to Write a Computer Emulator 
[HKN](https://news.ycombinator.com/item?id=29237372)
[LINK](https://fms.komkon.org/EMUL8/HOWTO.html)

x86 Bare Metal Examples: Minimal operating systems, learn x86 system programming (also discussion and learning materials about OS dev and hardware access)
[LINK](https://github.com/cirosantilli/x86-bare-metal-examples)
[HKN](https://news.ycombinator.com/item?id=27654257)

Writing a register based VM in less than 125 lines of C code 
[LINK](https://www.andreinc.net/2021/12/01/writing-a-simple-vm-in-less-than-125-lines-of-c)
[HKN](https://news.ycombinator.com/item?id=29492183)

OS from scratch in C with utilities
[LINK](https://github.com/klange/toaruos)

Quite advanced OS written in Assembly
[LINK](http://menuetos.net/)
[LINK](https://github.com/marcosptf/menuetos)

Interesting projects and compiler (examples of small allocators, operating systems etc)
[LINK](https://github.com/strawberryhacker)

Linux executable walkthrough
[LINK](https://fasterthanli.me/series/making-our-own-executable-packer/part-1)

QEMU Internals
[HKN](https://news.ycombinator.com/item?id=26941744)

Open source DOS with repository:
[LINK](http://svardos.osdn.io/)

MS-DOS original source code (assembly):
[LINK](https://github.com/microsoft/MS-DOS)  

MS-DOS programs and sources:
[HKN](https://news.ycombinator.com/item?id=26157165)

Tons of info about emulators with resources:
[HKN](https://news.ycombinator.com/item?id=26095834)

Making OS in Rust for RISC-V
[LINK](https://osblog.stephenmarz.com/)

OS in RUST
[LINK](https://os.phil-opp.com/)
[LINK](http://scialex.github.io/reenix.pdf)

Operating system in ASM
[LINK](https://createyourownos.blogspot.com/)

Faux86: A portable, open-source 8086 emulator for bare metal Raspberry Pi (2019)
[HKN](https://news.ycombinator.com/item?id=26057472https://github.com/jhhoward/Faux86)

Bootstrap for cortex-M series microcontroller.
[LINK](https://interrupt.memfault.com/blog/how-to-write-a-bootloader-from-scratch)
[HKN](https://news.ycombinator.com/item?id=24635383)

Low Level Programming course and materials:
[LINK](https://github.com/gurugio/lowlevelprogramming-university#Linux-kernel-and-device-driver)  
[LINK](https://www.reddit.com/r/linux/comments/3gw172/a_good_book_on_how_the_linux_kernel_works/)  



### Zig
Zig advent of code 2021 pro
[LINK](https://github.com/NashFP/advent-2021/tree/main/shritesh%2Bzig)

Trending Zig on github
[LINK](https://github.com/trending/zig?since=daily)

ZLD linker with examples of zig c++
[LINK](https://media.handmade-seattle.com/zld/)

Zig Vulkan headers:
[LINK](https://github.com/SpexGuy/Zig-Vulkan-Headers)

### C/C++
C programming learning materials links/cheatsheet
[LINK](https://github.com/agavrel/42_CheatSheet)

Modern C book (K&R C programming book modern replacement)
[LINK](https://gustedt.gitlabpages.inria.fr/modern-c/#orge4fc44a)

Simple JSON parser in C
[LINK](https://github.com/pangbox/rugburn/blob/master/src/json.c)

Writing programs with NCURSES
[LINK](https://invisible-island.net/ncurses/ncurses-intro.html)
[HKN](https://news.ycombinator.com/item?id=28354194)

VC++ bulding tools without Visual Studio:
[LINK](https://devblogs.microsoft.com/cppblog/announcing-visual-c-build-tools-2015-standalone-c-tools-for-build-environments/)  



### Forth and others
Check about Forth, bootstrapping lang for low memory devices
[HKN](https://news.ycombinator.com/item?id=25772483)



--
## Small, low memory programs

### C
Media Players in C, more on favourited on github (mostly in C)
[LINK](https://www.portablefreeware.com/forums/viewtopic.php?t=23626)
[LINK](https://www.codeproject.com/Articles/9586/Simple-Media-Player)

MPC fork thats actively being worked on (C++)
[LINK](https://github.com/clsid2/mpc-hc)

Terminal-based Music Player (fully open sourced)
[LINK](https://musikcube.com)

Single-file distributable Web Server with Lua and SQLite
[LINK](https://redbean.dev/)
[HKN](https://news.ycombinator.com/item?id=26271117)

Small SSH server (tinyssh, dropbear)
[HKN](https://news.ycombinator.com/item?id=29661170)

List of utilities with descriptions! (from DOS and win95 times, mostly without code)
[LINK](http://www.ericphelps.com/favorites/utilities.html)  

Writting PPM files (image using text format) with C code (nice to combine with STB libraries to save as jpg/png) or pipe into media player
[LINK](https://nullprogram.com/blog/2017/11/03/)
[HKN](https://news.ycombinator.com/item?id=29808180)
[LINK](https://solarianprogrammer.com/2019/06/10/c-programming-reading-writing-images-stb_image-libraries/)
[LINK](https://github.com/nothings/stb)
[HKN](https://news.ycombinator.com/item?id=24996791)

Writing a SQLite clone from scratch in C 
[LINK](https://cstack.github.io/db_tutorial/)
[HKN](https://news.ycombinator.com/item?id=27731966)

Micro-Max, a 133-line Chess Source
[LINK](https://home.hccnet.nl/h.g.muller/max-src2.html)

Simple C based HTTP server by SQLLite in one file
[HKN](https://news.ycombinator.com/item?id=27431910)

Pretty nice Text Editor with only 2000 lines of C code and 4000 Lua
[LINK](https://orbitalquark.github.io/textadept/)

Dos Navigator port
[LINK](https://github.com/unxed/dn2l)

Fast small browser Badwolf
[LINK](https://hacktivis.me/projects/badwolf)

Ultra small web server with Sqlite DB included - 350kb in exe
[LINK](https://code.google.com/archive/p/mongoose/downloads) 
[LINK](https://github.com/cesanta/mongoose) 

Tiny contenarized http server (100kb)
[LINK](https://github.com/emikulic/darkhttpd)

Lwan - high-performance & scalable web server
[LINK](https://lwan.ws/)

Ultra lightweight containers runner and manager (also for Rpi)
[LINK](https://github.com/containers/krunvm)
[HKN](https://news.ycombinator.com/item?id=25939995)



### Debugging
How to use GDB
[HKN](https://news.ycombinator.com/item?id=27204883)
[LINK](https://jvns.ca/blog/2021/05/17/how-to-look-at-the-stack-in-gdb/)

Extreme debugging
[LINK](https://squanderingti.me/blog/2020/10/28/extreme-debugging.html)
[HKN](https://news.ycombinator.com/item?id=24950120)

Application Reverse Engineering (An opinionated guide on how to reverse engineer software (margin.re))
[LINK](https://margin.re/media/an-opinionated-guide-on-how-to-reverse-engineer-software-part-1.aspx)
[HKN](https://news.ycombinator.com/item?id=29084716)


### GUI
Ultra lightweight GUI library
[LINK](https://github.com/sixtyfpsui/sixtyfps)

Small multiplatform UI in C
[LINK](https://github.com/andlabs/libui/)

### Assembly
C to Assembly parser in browser!!!
[LINK](https://godbolt.org/) 

NASM Assembly Language Tutorials
[LINK](https://asmtutor.com/)

A mini assembler for x86-64 (C)  
[LINK](https://github.com/andrewchambers/minias)

Disassembly challenges
[LINK](https://github.com/guyinatuxedo/nightmare)

Flat Assembler -  assembler compiler and a lot of resources 
[LINK](http://flatassembler.net/)

A lot of useful resource for Assembly:
[HKN](https://news.ycombinator.com/item?id=26311722)

Writing IL (.NET Assembly)
[LINK](https://www.i-programmer.info/programming/other-languages/933-getting-started-with-il.html)  

x64 assembly blog
[LINK](https://blog.benjojo.co.uk/post/interactive-x86-bootloader-tutorial)

Assembly application example (put it onto USB)
[LINK](https://johv.dk/blog/bare-metal-assembly-tutorial.html)  


## Standalone libraries with single header (STB like)
C single header libraries (Sean Barrett)
[LINK](https://github.com/nothings/stb)
[LINK](https://github.com/nothings/single_file_libs)

Zig gamedev and graphics library with no dependecies
[LINK](https://github.com/michal-z/zig-gamedev)

Libwebsockets a powerful and lightweight pure C library
[LINK](https://libwebsockets.org/)
[HKN](https://news.ycombinator.com/item?id=28439447) 

Modern TinyGL implementation with some multithreading support
[LINK](https://github.com/C-Chads/tinygl)

TinyGL is intended to be a very small implementation of a subset of OpenGL * for embedded systems or games. (no hw acceletation)
[LINK](https://bellard.org/TinyGL/)

PortableGL is an implementation of OpenGL 3.x core in clean C99 as a single header library
[LINK](https://github.com/rswinkle/PortableGL)
[HKN](https://news.ycombinator.com/item?id=29745029)

Bloat-free C++ GUI library
[LINK](https://github.com/ocornut/imgui)

C headers for really nice libraries
[LINK](https://www.reddit.com/r/programming/comments/cnze7k/sokol_minimal_crossplatform_standalone_c_headers/)  


## Electronics / computers from scratch / FPGA
Creating 386 motherboard from scratch
[HKN](https://news.ycombinator.com/item?id=29273829)
[LINK](https://alexandrugroza.ro/microelectronics/system-design/isa-80386dx-sbmc/index.html)

Ben Eater's channel (creating simple computers)
[LINK](https://www.youtube.com/watch?v=HyznrdDSSGM&list=PLowKtXNTBypGqImE405J2565dvjafglHU)

Micro code, cpu simulator
[LINK](http://www.mikrocodesimulator.de/index_eng.php)

80486 architecture document
[LINK](http://datasheets.chipdb.org/Intel/x86/486/manuals/27302101.PDF)

Making in Python: Geohot/twitchcore: A RISC-V core, first in Python, then in Verilog, then on FPGA 
[HKN](https://news.ycombinator.com/item?id=27728749)
[LINK](https://www.youtube.com/watch?v=camQ9QeBY9Q)
[LINK](https://github.com/geohot/twitchcore)

Simple 16-bit CPU
[LINK](https://github.com/jes/scamp-cpu)

Designing a RISC-V CPU, Part 1: Learning hardware design as a software engineer 
[HKN](https://news.ycombinator.com/item?id=26164574)

FPGA open source project for hardware emulation
[LINK](https://github.com/MiSTer-devel/Main_MiSTer/wiki)

From Nand to Tetris - full course of creating a computer
[LINK](https://www.nand2tetris.org/)
[HKN](https://news.ycombinator.com/item?id=25282507)

Understanding the computer architecture:
[HKN](https://news.ycombinator.com/item?id=24680109)
[LINK](https://www.amazon.com/dp/0262640686/ref=cm_sw_r_cp_api_i_yH-EFb40311E0)

Simple computer with programmed CPU
[LINK](http://www.mynor.org/)

Making ultra simple CPU
[HKN](https://news.ycombinator.com/item?id=24664196)

GPU architecture walkthrough:
[LINK](https://fgiesen.wordpress.com/2011/07/09/a-trip-through-the-graphics-pipeline-2011-index/)

BIOS history
[LINK](https://thestarman.pcministry.com/asm/bios/index.html)



=================
## General Programming

### Javascript / WEB
Good web site for JS training
[LINK](https://github.com/Thorinair/Stardew-Profits) 

JS ES6 feature set with examples to execute:
[LINK](http://es6-features.org/#BlockScopedVariables) 

In browser free notepad
data:text/html, <html contenteditable><head><title>Quick Note</title></head><body></body>

Small web frameworks (HTMX, HTML)
[LINK](https://htmx.org/)
[LINK](https://alpinejs.dev/)
[HKN](https://news.ycombinator.com/item?id=26693959)

Winamp in the browser
[LINK](https://webamp.org/)

Hosting SQLite databases on GitHub Pages or any static file hoster
[HKN](https://news.ycombinator.com/item?id=27016630)
[LINK](https://phiresky.github.io/blog/2021/hosting-sqlite-databases-on-github-pages/)

Bongo cat
[HKN](https://news.ycombinator.com/item?id=24866896)

Modern CSS walkthrough/tutorial:
[LINK](https://newcss.net/)

CSS animations
[LINK](https://www.imaginarycloud.com/blog/how-to-make-css-animations/)

Synth maker in html5
[LINK](https://learningsynths.ableton.com/)

JSON Parser with Typescript's Type system
[LINK](https://twitter.com/buildsghost/status/1301976526603206657)

SQL DB with TypeScript Type system
[HKN](https://news.ycombinator.com/item?id=24615185)

JS Asynchronous mechanics
[LINK](https://medium.com/javascript-in-plain-english/you-dont-know-javascript-until-you-can-beat-this-game-aa7fd58befb) 

Nice Javascript game - a lot useful code:
[LINK](https://github.com/AlexNisnevich/untrusted)  

Nice site to get console like visuals written in JS:
[LINK](https://krzysh.pl/)

Sandbox javascript:
[LINK](https://playcode.io/online-javascript-editor) 

GraphQL
[LINK](https://www.programmableweb.com/news/what-graphql-and-how-did-it-evolve-rest-and-other-api-technologies/analysis/2019/07/31)  


### Powershell
Remote Desktop coded in Powershell
[LINK](https://github.com/DarkCoderSc/PowerRemoteDesktop)

### Rust
Rewritting toy blockchain to Rust
[LINK](https://ezzeriesa.notion.site/Rewriting-my-toy-blockchain-in-Rust-9a130f225666488491ba497004821fbb)

Sample, basic (hello type) video codec implementation in RUST
[LINK](https://blog.tempus-ex.com/hello-video-codec/)

Rust weekly magazine with publications from blogs etc
[LINK](https://this-week-in-rust.org/)

Rust project to debug IoT Watch via RPi with VSCode
[LINK](https://medium.com/@ly.lee/debug-rust-mynewt-firmware-for-pinetime-on-raspberry-pi-4b9ac2d093a9)  



### WebAssembly
WebAssembly from Scratch: From FizzBuzz to DooM
[HKN](https://news.ycombinator.com/item?id=27832115)
[LINK](https://github.com/diekmann/wasm-fizzbuzz)

### Net C#
C# DeAssembly tool
[LINK](https://github.com/dnSpy/dnSpy)
[LINK](https://www.youtube.com/watch?v=knc0Y78hh6c)

### Python
Small IDE for Python
[LINK](https://thonny.org/)
Python sandbox in WASM
[HKN](https://news.ycombinator.com/item?id=27884055)
[LINK](https://github.com/brython-dev/brython)

Python programming web based sandbox, hosting and IDE:
[LINK](https://www.pythonanywhere.com)   

Code execution visualization (python):
[LINK](https://cscircles.cemc.uwaterloo.ca/visualize#mode=display) 


### General links to programming language pages:
Nim
[LINK](https://nim-lang.org/)

Zig
[LINK](https://ziglang.org/)
Zig pastebin
[LINK](https://zigbin.io/)
Zig forums
[LINK](https://zigforum.org/)

C
C Language Cheat Sheet
[LINK](https://courses.cs.washington.edu/courses/cse351/14sp/sections/1/Cheatsheet-c.pdf)  

GO
Go playground powered by WASM that runs in the browser 
[HKN](https://news.ycombinator.com/item?id=28636540)

### Others
Decompressing a Gzip File by Hand
[HKN](https://news.ycombinator.com/item?id=29336271)

Quick Java programming exercise: 
[LINK](https://codingbat.com/java/Recursion-2)  

TCL guide from MIT
[HKN](https://news.ycombinator.com/item?id=24916713)

Regex best tricks
[LINK](http://rexegg.com/regex-best-trick.html)
[HKN](https://news.ycombinator.com/item?id=27774584)

Websocketd – It's like CGI, twenty years later, for WebSockets
[LINK](http://websocketd.com/) 
[HKN](https://news.ycombinator.com/item?id=29656456)

Microservices with .NET Core
[LINK](https://www.reddit.com/r/csharp/comments/dbbel6/building_microservices_on_net_core_part_7/?utm_medium=android_app&utm_source=share)  



### Projects
Game of life Conway
[LINK](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life)
[LINK](https://github.com/edt-xx/life)

Challenging projects every programmer should try:
[HKN](https://news.ycombinator.com/item?id=25489879)
Build your own X (programming projects with examples done in the past)
[LINK](https://github.com/danistefanovic/build-your-own-x)

### Deep learning/Neural Networks
Neural Network From Scratch
[LINK](https://sirupsen.com/napkin/neural-net)
[HKN](https://news.ycombinator.com/item?id=29796789)

Deep learning Basics 11 part series:
[LINK](https://www.brainstobytes.com/deep-learning-basics-introduction/)


### Interesting Libraries
Community tools and libraries
[HKN](https://news.ycombinator.com/item?id=27171970)


====================
## Graphics and game programming

### Graphics / Shaders
Grafica Obscura – Collected Computer Graphics Hacks (technical notes, pictures and essays)
[LINK](http://graficaobscura.com/)

Shader School - An introduction to GLSL shaders that runs in your web browser
[HKN](https://news.ycombinator.com/item?id=28660024)

Michael Abrash's Graphics Programming Black Book
[LINK](https://github.com/jagregory/abrash-black-book)

How to read Shader assembly
[HKN](https://news.ycombinator.com/item?id=26859507)

Computer Graphics from Scratch:
[HKN](https://news.ycombinator.com/item?id=25266812)
[LINK](https://www.gabrielgambetta.com/computer-graphics-from-scratch/introduction.html)

A perceptual color space for image processing (turning color to grey gradient)
[LINK](https://bottosson.github.io/posts/oklab/)

### Game engines
MicroStudio now supports microScript, Python, JavaScript and Lua (simple IDE like PICO-8)
[HKN](https://news.ycombinator.com/item?id=29482163)

GameEngine from scratch
[LINK](https://github.com/heroseh)

RTS engine in C
[LINK](https://github.com/eduard-permyakov/permafrost-engine)

Quake3 engine copycat
[LINK](https://github.com/ec-/Quake3e)
[LINK](https://github.com/id-Software)
[HKN](https://news.ycombinator.com/item?id=27159906)

### Graphics engines / renderers
Building a PS1 style retro 3D renderer
[LINK](https://www.david-colson.com/2021/11/30/ps1-style-renderer.html)
[HKN](https://news.ycombinator.com/item?id=29486066)

Small toy renderer in C 
[LINK](https://momentsingraphics.de/ToyRendererOverview.html)

Commanche voxel terrain gen in 20 lines
[LINK](https://github.com/s-macke/VoxelSpace)

2d graphic game library in Rust
[LINK](https://github.com/ggez/ggez)

### Raytracing
RayTracing in One Weekend
[LINK](https://raytracing.github.io/books/RayTracingInOneWeekend.html)

From NAND to Raytracer
[HKN](https://news.ycombinator.com/item?id=27549225)

Nvidia's RTGI source code:
[LINK](https://developer.nvidia.com/rtxgi)  

### Games
Small 2D shooter in C without any dependencies
[LINK](https://github.com/tsherif/space-shooter.c/tree/master/src/game)
[HKN](https://news.ycombinator.com/item?id=29520200)

Trackmania open source clone:
[LINK](http://maniadrive.raydium.org/index.php?screenshots=yes)

Flight sim in C++
[LINK](https://github.com/marek-cel/mscsim)

Multiplayer game that you write in assembly like language
[LINK](https://github.com/AZHenley/HarvestMemory)


### Procedural
Roguelike tutorials
[HKN](https://news.ycombinator.com/item?id=29823957)

Simple Dungeon Map Generation (also notes to technical procedural generation talks)
[HKN](https://news.ycombinator.com/item?id=29812704)
[LINK](https://www.youtube.com/channel/UCKv_QzXft4mD6TXmQBZtzIA/featured)

### Server/Client architecture
Client game-server architecture:
[LINK](https://gabrielgambetta.com/client-server-game-architecture.html)

### Graphics libraries


### Resources and tools for assets
Free sounds and music for games and videos
[HKN](https://news.ycombinator.com/item?id=27232297)

### Others
Programming visualization engine kinda
[LINK](https://processing.org/)

Frink calc and lang for physics calcutations with units explained in detail
[HKN](https://news.ycombinator.com/item?id=26645172)

Graphics Programming Weekly discussion:
[HKN](https://news.ycombinator.com/item?id=26134854)
[HKN](https://news.ycombinator.com/item?id=26143837)

FPS in Unity book
[LINK](https://wireframe.raspberrypi.org/books/unity-fps)

GPU access via code in Linux
[LINK](https://blogs.igalia.com/elima/tag/gpu/)

Vectors:
[LINK](https://grobots.fandom.com/wiki/Tutorials/Vectors)  

====================
## Algorithms


### General
POSIX Threads Programming
[HKN](https://news.ycombinator.com/item?id=26085373)
[LINK](https://computing.llnl.gov/tutorials/pthreads/)

Algorithmic complexity by examples
[LINK](https://adrianmejia.com/most-popular-algorithms-time-complexity-every-programmer-should-know-free-online-tutorial-course/)  

MIT Introduction to Algorithms
[LINK](https://catonmat.net/summary-of-mit-introduction-to-algorithms)

Sorting algorithm (Einstein) in java
[LINK](https://gist.github.com/pencil/1253001/cd0f36b6c50dcd6417bc7fbfcf5cb3861761908c)  

V language - memory management
[LINK](https://aardappel.github.io/lobster/memory_management.html)  

Libdill: Structured Concurrency for 
[LINK](http://libdill.org/structured-concurrency.html)
[HKN](https://news.ycombinator.com/item?id=27357295)


### Text Editing
The Craft of Text Editing
[LINK](http://www.finseth.com/craft/)


====================
## Operating Systems

### Windows
Windows services:
[LINK](https://www.reddit.com/r/Windows10/comments/8mgkmi/which_windows_10_servicesprocesses_are_safe_to/)
[LINK](http://www.blackviper.com/service-configurations/black-vipers-windows-10-service-configurations/)
[LINK](https://www.thewindowsclub.com/which-windows-10-services-safe-to-disable)

Debloaded  Windows 10 - Tiny10 - created with NTlite
[LINK](https://twitter.com/NTDEV_/status/1340034560583757830)

Nano98: Windows 98 that boots and runs under 5M (also a lot of tips for small Win)
[HKN](https://news.ycombinator.com/item?id=28591866)

Optimizing windows startup:
[LINK](https://www.tomshardware.com/reviews/fastest-windows-10-boot-time,5810-4.html)

Big WSL Guide
[LINK](https://adamtheautomator.com/windows-subsystem-for-linux/)  

Moving WSL installation:
[LINK](https://github.com/DDoSolitary/LxRunOffline)  

WSL - custom distro tutorial (ArchLinux in example) based on docker image
[LINK](https://medium.com/@hoxunn/wsl-docker-custom-distro-2-0-730fd97fe72e) 

Linux Apps ported to Windows with MinGW:
[LINK](https://packages.msys2.org/base) 

Microsoft Win32 full documentation
[LINK](https://github.com/MicrosoftDocs/win32)

OpenSSH in windows - create a server on laptop and connect from PC, use then bash console
[LINK](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse)  
[LINK](https://devblogs.microsoft.com/powershell/using-the-openssh-beta-in-windows-10-fall-creators-update-and-windows-server-1709/)  


### Linux
Bash/Linux Cheatsheet
[LINK](https://devhints.io/bash)
[LINK](https://github.com/r0f1/linuxhelp)

Linux Offline HowTo documentation repo:
[LINK](https://tldp.org/docs.html#howto)

Memory read on Linux (top, htop, free)
[HKN](https://news.ycombinator.com/item?id=29653573)
[LINK](https://www.linuxatemyram.com/)

Alpine Linux 3.15 (a lot useful posts):
[HKN](https://news.ycombinator.com/item?id=29330394)

X Window System on a Floppy (tiny linux, tinylinux)
[HKN](https://news.ycombinator.com/item?id=28515025)

XFCE Windows 95 theme
[LINK](https://github.com/grassmunk/Chicago95)

Setup of Alpine via 2 USB (in the example for a Fileserver)
[LINK](https://blog.haschek.at/2020/the-perfect-file-server.html)

Awesome description of GNU core utils
[LINK](http://maizure.org/projects/decoded-gnu-coreutils/)

Getting better with Linux (10 projects)
[LINK](https://carltheperson.com/posts/10-things-linux)
[HKN](https://news.ycombinator.com/item?id=26002335)

Linux's MAN via REST
[LINK](https://man-api.ch/)

NixOS introduction and review:
[LINK](https://jae.moe/blog/2020/11/one-week-of-nixos/)

SSH cheatsheet
[LINK](https://github.com/dennyzhang/cheatsheet-ssh-A4)

Linux productivity Tools:
[HKN](https://news.ycombinator.com/item?id=23229241)

Piping video from one linux to another linux via SSH (my case passing video from laptop to RPi connected to TV)
[LINK](https://unix.stackexchange.com/questions/2302/can-i-pipe-dev-video-over-ssh)  
[LINK](https://linuxconfig.org/how-to-stream-video-from-vlc) 
[LINK](https://superuser.com/questions/321787/piping-video-device-over-ssh-or-tcptunnel) 
[LINK](https://askubuntu.com/questions/203173/run-application-on-local-machine-and-show-gui-on-remote-display)  

Visual guide to SSH tunneling
[HKN](https://news.ycombinator.com/item?id=26053323)

Direct linux binaries:
[LINK](https://anaconda.org/conda-forge)  

Linux Networking 101
[LINK](https://cumulusnetworks.com/learn/resources/linux-101/linux-networking-101)  

Linux 101 from IBM?!
[LINK](https://developer.ibm.com/tutorials/l-lpic1-101-1/)  
[LINK](https://developer.ibm.com/tutorials/l-lpic1-map/) 

Running apps without WM and DE
[LINK](https://linuxconfig.org/how-to-run-x-applications-without-a-desktop-or-a-wm)

Dissecting a GPU bug in Linux
[LINK](https://www.phoronix.com/forums/forum/linux-graphics-x-org-drivers/open-source-amd-linux/1099745-how-to-tell-if-a-driver-is-gallium-or-just-mesa-slow-renderng-with-radeon)  

Yocto linux - custom linux for embedded hw
[LINK](https://www.yoctoproject.org/)

New type of Docker packaging, more like VM (DX11)
[LINK](https://medium.com/stack-me-up/my-dream-come-true-launching-gui-docker-sessions-with-dx11-in-seconds-9e01653bed1f)



### Terminals tools and programming
Easy way for creating SSH based command line applications (whole repo of tools)
[LINK](https://github.com/charmbracelet/bubbletea)

ASCII escape codes and how to use them to display stuff in terminal without ncurses
[LINK](http://xn--rpa.cc/irl/term.html)

Recording terminal session:
[LINK](https://asciinema.org/)

Convert images to Terminal color output:
[LINK](https://github.com/csdvrx/derasterize)
[HKN](https://news.ycombinator.com/item?id=25976856)

AWK tutorial and exercises
[LINK](https://github.com/FreedomBen/awk-hack-the-planet)

AWK overview
[LINK](https://jemma.dev/blog/awk-part-1)

Book and discussion about AWK:
[HKN](https://news.ycombinator.com/item?id=25142867)

The Linux shell commands handbook
[LINK](https://openbootcamps.com/the-linux-commands-handbook/)

Bash utils
[LINK](https://github.com/pirate/bash-utils)

Linux terminal tools guide (pdf)
[HKN](https://news.ycombinator.com/item?id=27037583)
[LINK](https://ketancmaheshwari.github.io/pdfs/LPT_LISA.pdf)

fzf is a general-purpose command-line fuzzy finder  
[LINK](https://github.com/junegunn/fzf)

TLP linux power management
[LINK](https://www.reddit.com/r/ManjaroLinux/comments/clg4nv/best_de_for_battery_life/)

Easy tunneling
[LINK](https://github.com/erebe/wstunnel)

Logging to WM via SSH (X server)
[LINK](https://unix.stackexchange.com/questions/327532/how-to-remotely-log-in-with-full-graphical-desktop-over-x11)  

turn logs output into tree structure
[LINK](https://github.com/birchb1024/frangipanni)

W3M, Oddilo - light-weight Linux browser
[LINK](http://w3m.sourceforge.net/)

best terminal applications:
[LINK](https://www.reddit.com/r/commandline/comments/9b426l/best_terminal_apps/)  


### Other tools/programs
USB Formatting utilities
[HKN](https://news.ycombinator.com/item?id=27071982)

Reducing container size
[LINK](https://devopsdirective.com/posts/2021/04/tiny-container-image/)

===================
## EMBEDDED
Using kindle as RaspberryPi display
[LINK](https://www.raspberrypi.org/blog/kindleberry-pi-the-second/)

Installing Linux on Xperia Z3 Compact
[LINK](http://prochal.com/2017/09/turn-your-android-phone-into-a-web-server/)  

FreeRTOS - Real-time operating system for microcontrollers
[LINK](https://www.freertos.org/index.html)  

Highly efficient Box86 x86 emulator for non x86 platforms like ARM
[LINK](https://github.com/ptitSeb/box86)


### RaspberryPi
Backup and restore USB with linuxvia Win32 Disc Imager in windows
[LINK](https://www.howtogeek.com/341944/how-to-clone-your-raspberry-pi-sd-card-for-foolproof-backup/)  

installation setup via DD 
[LINK](https://www.raspberrypi.org/forums/viewtopic.php?t=46911) 


====================
## Others:

### Zig

### C

### Others

### Useful tools/programs
File sharing 
[LINK](https://wormhole.app/?ref=hn)
[LINK](https://send.vis.ee/)

Small, passive open source Anti-Vir app
[LINK](https://github.com/Cisco-Talos/clamav)

### Small hints/links
C/C++ quotes!
[LINK](https://www.tutorialspoint.com/single-quotes-vs-double-quotes-in-c-or-cplusplus)  

News site that aggregates data from different news sites and display them as pure html
[LINK](http://68k.news/)

youtube-dl alternative
[LINK](https://github.com/yt-dlp/yt-dlp/)

Good and cheap dedicated hosting:
[LINK](https://www.hetzner.com/)

Oasis Linux - Statically linked (nice browser)
[HKN](https://news.ycombinator.com/item?id=25265761)

Search Engine with a public API (Gigablast)
[LINK](https://gigablast.com/about.html)
[HKN](https://news.ycombinator.com/item?id=29421898)

Google Searcher for Papers and Publications
[LINK](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=raytracing&btnG=)

Basic English
[LINK](http://ogden.basic-english.org/)

JSON design business card
[LINK](http://james.newtonking.com/images/JSONStandardBusinessCard_C4C7/image_3.png)

Achieving 11M IOPS and 66 GB/S IO on a Single ThreadRipper Workstation 
[HKN](https://news.ycombinator.com/item?id=25956670)
[LINK](https://spdk.io/news/2019/05/06/nvme/) (10.39M Storage I/O Per Second From One Thread)

Learn x in y minutes
[LINK](https://learnxinyminutes.com/)

Best hacker news posts
[HKN](https://news.ycombinator.com/item?id=24351073)

VPN + Local network guide
[LINK](https://blog.lan-tech.ca/2013/02/21/access-local-and-vpn-network-simultaneously/)  

Great tool for creating gifs from any view
[LINK](https://www.screentogif.com/screenshots)
[LINK](https://askubuntu.com/questions/107726/how-to-create-animated-gif-images-of-a-screencast/833995#833995)

Site with a lot of APIs
[LINK](https://devdocs.io/)

RDP specification:
[LINK](https://github.com/FreeRDP/FreeRDP/issues/4030)  

Custom CPU design:
[LINK](https://www.sifive.com/)  

Azure free account - full VMs for free for 750h
[LINK](https://azure.microsoft.com/en-us/free/?WT.mc_id=A261C142F)   

Mermaid - Graph creator via syntax
[LINK](https://mermaid-js.github.io/mermaid-live-editor/#/edit/)

Thread about Firewalls
[HKN](https://news.ycombinator.com/item?id=25743546)

Github search 
[LINK](https://grep.app/)
[LINK](https://sourcegraph.com/search)

Random walkthrough GIT
[LINK](https://bakkenbaeck.github.io/a-random-walk-through-git/)

Real Hacking Games:
[LINK](http://overthewire.org/wargames) 


### Books
Effective C book - BUY!
[LINK](https://nostarch.com/Effective_C)

Book on practical electronics design
[HKN](https://news.ycombinator.com/item?id=27439266)

Ebooks of Compilers and C
[LINK](https://github.com/germanoa/compiladores/tree/master/doc/ebook)

Book 3D Math Primer for Graphics and Game Development.
[LINK](https://gamemath.com/)

Books about creating operating systems (with homework and examples):
[LINK](https://pages.cs.wisc.edu/~remzi/OSTEP/)

Operating system from scratch:
[LINK](https://www.cs.bham.ac.uk/~exr/lectures/opsys/10_11/lectures/os-dev.pdf)

Linux Device Driver books
[LINK](https://lwn.net/Kernel/LDD3/) 

The Architecture of Open Source Applications
[LINK](http://aosabook.org/en/index.html)

Programming from the ground up - book (assembly and C)
[HKN](https://news.ycombinator.com/item?id=11702025)
[LINK](http://download-mirror.savannah.gnu.org/releases/pgubook/ProgrammingGroundUp-1-0-booksize.pdf)
(for Rust)
[HKN](https://news.ycombinator.com/item?id=24764589)
[LINK](https://lowlvl.org/)


### Learning tools / CS Cources
Teach Yourself Computer Science
[HKN](https://news.ycombinator.com/item?id=29353904)
[LINK](https://teachyourselfcs.com/)
[LINK](https://cs1000.vercel.app/)

IT related book notes:
[LINK](https://notes.eddyerburgh.me/operating-systems/linux)  

Math and Science docs compilation github
[LINK](https://github.com/bobeff/programming-math-science)
[HKN](https://news.ycombinator.com/item?id=28349475)

MIT 6.172: Performance Engineering of Software Systems 
[HKN](https://news.ycombinator.com/item?id=25626315)

Computer Science textbooks that are freely available online
[HKN](https://news.ycombinator.com/item?id=25572852)
[LINK](https://csgordon.github.io/books.html)

Ossu/computer-science: Path to a free self-taught education in Computer Science
[LINK](https://github.com/ossu/computer-science)

Algorithm Design and Analysis Course:
[LINK](https://www.edx.org/course/algorithm-design-analysis-pennx-sd3x)

Math learning resources:
[HKN](https://news.ycombinator.com/item?id=26981864)

Geometric Algebra:
[LINK](https://crypto.stanford.edu/~blynn/haskell/ga.html)
[HKN](https://news.ycombinator.com/item?id=25142528)

Mathematics Cheat Sheet
[HKN](https://news.ycombinator.com/item?id=27468908)
[LINK](https://ourway.keybase.pub/mathematics_cheat_sheet.pdf)

Probability, Mathematical Statistics, Stochastic Processes
[LINK](http://www.randomservices.org/random/)

Mathematical exercises:
[LINK](https://projecteuler.net/news)  
below one with bio/chemistry twist
[LINK](http://rosalind.info/problems/rna/)  

AI course Finish university:
[LINK](https://www.elementsofai.com/) 

All physics 101 materials:
[LINK](https://www.susanjfowler.com/blog/2016/8/13/so-you-want-to-learn-physics)

Teaching yourself Demoscene in 14 days
[HKN](https://news.ycombinator.com/item?id=27254838)

What happens when:
[LINK](https://github.com/alex/what-happens-when)

Busy Beaver problem
[HKN](https://news.ycombinator.com/item?id=25381325)

Animating mechanical engines:
[LINK](http://animatedengines.com/)
[HKN](https://news.ycombinator.com/item?id=26368939)

A search engine that favors text-heavy sites and punishes modern web design (good for academic entries)
[HKN](https://news.ycombinator.com/item?id=28550764)


### BLOGS
blog:
[LINK](https://raphlinus.github.io/personal/2018/04/08/smooth-resize.html)
[LINK](http://siciarz.net/)  
[LINK](https://ocharles.org.uk/blog/pages/2013-12-01-24-days-of-hackage.html)

Nice blog with technical examples:
[LINK](http://www.blog.j-labs.pl/)

Optimization blog
[LINK](https://tomforsyth1000.github.io/blog.wiki.html)  

Atomics in AArch64 in a blog
[LINK](https://cpufun.substack.com/p/atomics-in-aarch64)
[HKN](https://news.ycombinator.com/item?id=27191275)

TCP optimization (blog):
[LINK](https://jvns.ca/blog/2015/11/21/why-you-should-understand-a-little-about-tcp/)

Anatomy of a program in memory (screenshots messed up)
[LINK](https://manybutfinite.com/post/anatomy-of-a-program-in-memory/)

### Conferences
FOSDEM - Open Source Conference
[LINK](https://fosdem.org/2021/)

Conference about cybersecurity
[LINK](https://sekurak.pl/pieronsko-dobra-i-darmowa-konferencja-od-sekuraka-wbijajcie-na-lshp/?fbclid=IwAR1w8r3u9Fjh4r-ioHT_g9hbwat1VUrb2sLxZrw2F83a26ce29ObbC_5y0U)  


### Others
New physics model:
[LINK](https://writings.stephenwolfram.com/2020/10/faster-than-light-in-our-model-of-physics-some-preliminary-thoughts/)