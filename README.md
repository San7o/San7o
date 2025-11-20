<h1 align="center">Giovanni Santini</h1>

Hi,

I am Giovanni, welcome to my github page. I am a [software developer](https://giovanni-diary.netlify.app/programming/notes/recreational-programming) working on [Linux](https://giovanni-diary.netlify.app/programming/linux/linux) system libraries and tools, and a bit of everything else! [[CV](https://giovanni-diary.netlify.app/programming/cv)]

Most of my open source software is hosted here on GitHub. I have a **blog**, more like a diary, where I write down my thoughts.
Check It out:

[https://giovanni-diary.netlify.app/](https://giovanni-diary.netlify.app/)

Get in contact with me:

- preferably via email at [giovanni.santini@proton.me](mailto:giovanni.santini@proton.me),
- on mastodon [@santo7@mastodon.social](https://mastodon.social/@santo7).
- on IRC, I go by "santo_".

<details>
 <summary>
      Click to view a list of my software (more than 100 projects!)
 </summary>

[really cool visualization](https://san7o.github.io/repo-graph/)

## [micro-headers](https://github.com/San7o/micro-headers)
A collection of high-quality, configurable, header-only libraries written in C99. The libraries are designed to be highly reusable, simple to maintain with little to no dependencies, and easy to integrate in your projects. [website](https://san7o.github.io/micro-headers/)

- [micro-tests.h](https://github.com/San7o/micro-tests.h): lightweight, header-only testing framework, with multithread support and run-time settings
- [micro-log.h](https://github.com/San7o/micro-log.h): configurable, thread safe logging framework in C99. With lots of features
- [micro-draw.h](https://github.com/San7o/micro-draw.h): a 2D software renderer
  - Projects that use this renderer: [cosu](https://github.com/San7o/cosu), [cgis](https://github.com/San7o/cgis), [game-of-life](https://san7o.github.io/micro-draw.h/#canvas) (wasm)
- [micro-lex.h](https://github.com/San7o/micro-lex.h): simple lexer for lisp-like languages, and others. See also [justlex-rs](https://github.com/San7o/justlex-rs) [crates.io](https://crates.io/crates/justlex)
- [micro-arena.h](https://github.com/San7o/micro-arena.h/): memory allocator (first fit). It implements the common memory functions from stdlib.h.
- [micro-flag.h](https://github.com/San7o/micro-flag.h/): tiny library to parse command line arguments
- [micro-module.h](https://github.com/San7o/micro-module.h): define, load, and unload runtime modules / plugins with a simple C99 API
- [micro-serde.h](https://github.com/San7o/micro-serde.h): serialization library for C99, in ~150 lines of code.
- [micro-bench.h](https://github.com/San7o/micro-bench.h): micro benchmarking library
- [micro-conf.h](https://github.com/San7o/micro-conf.h): library to parse config files
- [micro-hash.h](https://github.com/San7o/micro-hash.h): quick and dirty hash functions in C99, with some benchmarks
- [micro-la.h]( https://github.com/San7o/micro-la.h.git): linear algebra types and functions
- [hll.h](https://github.com/San7o/hll.h): configurable, header-only implementation of HyperLogLog, used for approximating the cardinality of large multisets
- [bloom-filter.h](https://github.com/San7o/bloom-filter.h): configurable, header-only implementation of bloom filters, a space-efficient probabilistic data structure that is used to test whether an element is a member of a set
- [rendezvous-hasher.h](https://github.com/San7o/rendezvous-hasher.h): dependency-free implementation of Rendezvous Hashing (a.k.a. Highest Random Weight hashing), useful for distributing keys across a dynamic set of nodes
- [consistent-hasher.h](https://github.com/San7o/consistent-hasher.h): implementation of consistent hashing, alternative to rendezvous-hashing
- [hashmap.h](https://github.com/San7o/hashmap.h): implementation of an hashmap for any type
- [hashset.h](https://github.com/San7o/hashset.h): implementation of an hashset for any type
- [llist.h](https://github.com/San7o/llist.h): type-safe, generic doubly-linked list in C99
- [liblaunchpad.h](https://github.com/San7o/liblaunchpad.h): abstraction layer over Novation's Launchpad S through ALSA, as an header-only C99 library
- [micro-example.h](https://github.com/San7o/micro-example.h): example header-only library in C99 used as a template project, in the style of the great micro-headers
- [game-of-life.h](https://github.com/San7o/game-of-life.h/): Conway's Game of Life logic implementation

## (New) [micro-tools](https://github.com/San7o/micro-tools)
A collection of useful tools for programmers to solve programmer problems. Mostly written in C99.

- [micro-templating.c](https://github.com/San7o/micro-templating.c/): generate a file from a template, in ~200 lines of code
- [micro-timerd](https://github.com/San7o/micro-timerd/): client-server application to start, stop and list timers
- [micro-sprite](https://github.com/San7o/micro-sprite): simple drawing tool.
- [lkde-tool](https://github.com/San7o/lkde-tool): develop and test kernel patches and applications in multiple kernel branches, trees, architectures and configurations.

## Highlights
Some other interesting projects that you should check out.

- [Brenta Engine](https://github.com/San7o/Brenta-Engine): a 3D renderer and game engine in modern C++, with a custom ECS framework. [website](https://san7o.github.io/brenta-engine-documentation/v1.1/)
  - Satellite projects:
    - [valfuzz](https://github.com/San7o/valFuzz): modern testing and fuzzing library. [website](https://san7o.github.io/brenta-engine-documentation/valfuzz/v1.0/)
    - [oak](https://github.com/San7o/oak): a feature-rich thread-safe C++23 logger library. [website](https://san7o.github.io/brenta-engine-documentation/oak/v1.0/)
    - [viotecs](https://github.com/San7o/viotecs): the engine's ECS. [website](https://san7o.github.io/brenta-engine-documentation/viotecs/v1.0/)
- [haplolang](https://github.com/San7o/haplolang): a Lisp-like, s-expression based, imperative, strongly typed programming language
  - [The Design and Implementation of Haplolang](https://san7o.github.io/haplolang/): my notes after implementing the language
- [kivebpf](https://github.com/San7o/kivebpf): eBPF-powered file access monitoring Kubernetes operator
  - [The Kibebpf website](https://san7o.github.io/kivebpf/): more documentation about the operator
- [Baldo scanner](https://github.com/San7o/Baldo-Scanner): malware scanner daemon for linux using a kernel module
- [fft.c](https://github.com/San7o/fft.c): Implementation of Discrete Fourier Transform (DFT) and Fast Fourier Transform (FFT) in C99, with a bonus cool music visualization.
- [tenno-tl](https://github.com/San7o/tenno-tl): a partial re-implementation of the c++26 standard library

## Misc / Old
Backlog of projects.

- [Introduction-to-machine-learning](https://github.com/San7o/Introduction-to-machine-learning): useful notes for students studying for an introductionary course to Machine Learning, or to anyone interested in the subject
- [Algorithms and Data Structure course (Italian)](https://giovanni-diary.netlify.app/programming/notes/algoritmi/algoritmi): high quality notes from my Algorithms university course
- [design-patterns-cpp](https://github.com/San7o/design-patterns-cpp.git): implementation of common design patterns in C++, useful reference for many projects
- [ld-preload-sample](https://github.com/San7o/ld-preload-sample): sample LD_PRELOAD demonstration to replace libc functions
- [ebpf-c-sample](https://github.com/San7o/ebpf-c-sample): sample project for an eBPF program + loader in C with libbpf and clang
- [opentelemetry-cpp-sample](https://github.com/San7o/opentelemetry-cpp-sample): sample C++ application with OpenTelemetry instrumentation to emit telemetry data
- [linux-kernel-module](https://github.com/San7o/linux-kernel-module): hello world kernel module with a full developement setup using qemu
- [micro-gl-sample](https://github.com/San7o/micro-gl-sample): simple setup project for OpenGL graphics.
- [cosu!](https://github.com/San7o/cosu): a rhythm game written in C, (not yet fully) compatible with osu!mania maps.
- [minipiano.c](https://github.com/San7o/minipiano.c): play the piano using sinewaves and your keyboard!
- [santOS](https://github.com/San7o/santOS): a general purpose microkernel for i386.
- [modern-cpp-template](https://github.com/San7o/modern-cpp-template): a template for c++ libraries
- [parallel-computing-cpp](https://github.com/San7o/parallel-computing-cpp): MPI and OpenMP algorithms and benchmarks
- [cycloidal-curves](https://github.com/San7o/cycloidal-curves/): cycloidal curves interactive visualization. [website](https://san7o.github.io/cycloidal-curves/)
- [fixmi](https://github.com/orgs/IS-FixMi/repositories): business management software using microservices.
  -  [documentation](https://github.com/IS-FixMi/FixMi)
  -  [root-project](https://github.com/IS-FixMi/fixmi-compose)
- [repo-graph](https://github.com/San7o/repo-graph/): visualize GitHub repositories through a graph based on their topics.
- [go-chat-server](https://github.com/San7o/go-chat-server?tab=readme-ov-file): a server and client for a minimal text-based chat in Go.
- [elixir-blockchain](https://github.com/San7o/elixir-simple-bockchain): a simple blockchain library implemented in elixir.
- [react-express-template](https://github.com/San7o/react-express-template): a meplate for web applications using node, express, typescript, react, tailwind, docker.
- [webgl-3D-renderer](https://github.com/San7o/webgl-3D-renderer): a 3D renderer in WebGL and Angular
- [tiny-rss](https://github.com/San7o/tiny-rss.git): RSS feeds generator for org mode
- [musync](https://github.com/San7o/musync.el.git): download music declaratively
- [snakepp](https://github.com/San7o/snakepp): simple demo of snake in C++, using SFML
- [ssap](https://github.com/San7o/ssap): local password encryption manager written in in Rust
- [rust-lc3](https://github.com/San7o/rust-little-computer-3): implementation of a virtual machine for [LC-3](https://en.wikipedia.org/wiki/Little_Computer_3)
- [robotUI](https://github.com/San7o/rust-robotUI): bevy visualizer for Advanced Programming 2023 @Unitn
- [rust-pomodoro-timer](https://github.com/San7o/rust-pomodoro): TUI study timer written in Rust
- [rust-music-player](https://github.com/San7o/rust-music-player): a TUI music player written in Rust
- [broutines](https://github.com/San7o/broutines): goroutines and coroutines implemented in C
- [stock-exchange-py](https://github.com/San7o/stock-exchange-py): simple logic implementation of a stock exchange in Python.
- [chttps](https://github.com/San7o/chttps): https server in C with server-side rendering
- [cchecker](https://github.com/San7o/cchecker): borrow checker in C++
- [regEZ](https://github.com/San7o/regEZ): fully constexpr regex implementation in modern C++
- [go-ebpf](https://github.com/San7o/go-ebpf): example eBPF program in go
- [risto89](https://github.com/San7o/risto89-fork): online tickets market in java
- [ledger-board](https://github.com/San7o/ledger-board): highly scalable transaction producer/consumer app, built with Kubernetes, Kafka, Django, Angular, Nginx, Redis, Celery, Docker
- [how-to-root-samsung-galaxy-j5](https://github.com/San7o/how-to-root-samsung-galaxy-j5): instructions to root a Samsung Galaxy J5
- [hypr-nerd-gestures](https://github.com/San7o/hypr-nerd-gestures): control hyprland through hand gestures, using openCV.
- [launchpad-app-launcher](https://github.com/San7o/launchpad-app-launcher): launch commands from a novation's launchpad
- [modern-python-template](https://github.com/San7o/modern-python-template)
- [youtube-minuature-generator](https://github.com/San7o/youtube-miniature-generator)
- many more...

### Gists
Code extracted from my other projects that can be easily reused, or implementation of simple algorithms.

- [unix_server.c](https://gist.github.com/San7o/4a2cfa08783ab55c10f7af5c93401e28): Create an unix socket server that reads data sent to it
- [inet_server.c](https://gist.github.com/San7o/4af3f058cd1508f9779a310aef75b9c6): Create an inet server that reads data sent to it
- [set_signals.c](https://gist.github.com/San7o/c933925bc8bc8beb493bc618c90e1cbf): Setup an handler for various POSIX signals.
- [sdl_window.c](https://gist.github.com/San7o/b80ee8e26fecda3bfaa113b12be470c5): Create an SDL3 window and poll events.
- [micro-style.css](https://gist.github.com/San7o/e56fc5299abbc7e21ba7a049b8078d5d): Very simple css style for minimalistic websites.
- [mmap_file.c](https://gist.github.com/San7o/1c88efae81f499e5882d0f63104a228e): Read a file's contents using mmap, faster than read(2). Neat optimization on POSIX systems.
- [traverse_dir.c](https://gist.github.com/San7o/270736ae4c9215aeee80d4593156c003): Traverse a directory recursively and call handle_file on each file.
- [djb2.c](https://gist.github.com/San7o/e41c79a609aaf3385f133d309ec39922):  Simple hash function for strings.
- [lcg.c](https://gist.github.com/San7o/f979a38a4746990da527041d62da2d71): LCG algorithm for fast pseudo random number generation.
- [utils.h](https://gist.github.com/San7o/6660fde97f359b83040a4b762a978f14): Utility macros for C projects.
- [mandelbrot.c](https://gist.github.com/San7o/2eea69c31a9f631253d2b9c72d9fe34a): Get the number of iterations of a point in the Mandelbrot set.
- [left_space.c](https://gist.github.com/San7o/b1161f85888bc09a995e1fb3f54f52da): Get number of separator charactes from the left of a string in C99.
- [clear_screen.c](https://gist.github.com/San7o/0a7ab7492e521cb5decd0e4eac18b276):  Clear the terminal screen using ANSI control sequences.
- [delta_time.c](https://gist.github.com/San7o/51807bdc9266241c76f15ac4247167db): Calculate the frame delta time and render a certain number of times per seconds in C99.
- [time_sec.c](https://gist.github.com/San7o/dcf1373ecb1eaff9c6f70ec025d0fe90): Get the time in seconds in C.
- [xorshift_rng.c](https://gist.github.com/San7o/5f45fe794f76bb451b134a9332a9d4f2): xorshift algorithm for generating pseudo random numbers.
- [Makefile](https://gist.github.com/San7o/630a4c8a42ae5b914a4fe41b4f19e374): Simple Makefile template for C projects.
- [CMakeLists.txt](https://gist.github.com/San7o/25c16f1a069474581bda8b33aa5f8001): Modern Cmake template for C++ projects.
- [windows-commands.ps1](https://gist.github.com/San7o/b4650e0b1be17cb9d1c8f853076165a7): Useful Microsoft Windows commands.
- [yt-dl-mp3.sh](https://gist.github.com/San7o/8fcf11f588c049442968ae39a0b34248): Download mp3 music from youtube.
- [k-means.py](https://gist.github.com/San7o/b648bbbe4f8da434d2d00e6e59a531c6): Implementation of k-means clustering in Python.
- [scikit-sample.py](https://gist.github.com/San7o/f5948a04ddecd93ece67e19e66f48fa6): Example of using a ML model with scikit-learn.
- [knn.c](https://gist.github.com/San7o/4bfe69a9e1eb251d5267d8b74ff73dda): Implementation of KNN for supervised learning classification
  on a one-dimensional dataset in C.
- [perceptron.c](https://gist.github.com/San7o/da2efc84eb3e7c8bdbefbd540c8cfbea): Implementation of a perceptron for binary
  classification in C.
- [generate-debuginfo](https://gist.github.com/San7o/a85d3bd5796bc6b5a488fd6e660029ec): Separate debuginfo and executable in two different files.
- [gcc-print-definitions](https://gist.github.com/San7o/4ebdc3d64a170278e463d71a3332cea7): Print all the #define symbols and their values with gcc or clang
- [sha1.c](https://gist.github.com/San7o/10496ad588e3e956c145501f89d13886): sha1 implementation from nginx (src/core/ngx_sha1.c)
- [md5.c](https://gist.github.com/San7o/d8803805c0829fb9cf208b4fcd0d6a63): md5 implementation from nginx (src/core/ngx_md5.c)

### Setup
Custom configurations for my daily development setup and workflow.

- [.emacs.d](https://github.com/San7o/.emacs.d.git): my emacs configuration
- [dwm](https://github.com/San7o/dwm.git): my fork of DWM and DWL
- [init.lua](https://gist.github.com/San7o/2d5856a3c3de041091ee92d5488edf58): simple Neovim configuration without too much bloat
- [i3config](https://gist.github.com/San7o/63bfb7f49153ebabb3a98e44e47e1182): i3 configuration, I use it as a fallback
- [lfs](https://github.com/San7o/lfs): my Linux From Scratch distribution
- [mapkg](https://github.com/San7o/mapkg): my own packet manager
- [nixos-dotfiles](https://github.com/San7o/nixos-dotfiles): my (outdated) nixos setup
- [obsidian-chill-theme](https://github.com/San7o/obsidian-chill-theme): my custom obsidian theme
- [obsidian-advanced-slided-theme](https://github.com/San7o/obsidian-advanced-slides-theme-chill): custom theme for obsidian advanced slides

### My Favourite libraries

These are the libraries that I use the most in my projects and that I find incredibly useful.

- [SDL](https://github.com/libsdl-org/SDL) (C): my goto library for writing desktop applications
- [RGFW](https://github.com/ColleagueRiley/RGFW) (C99): when you just want to open a window in a cross-platform way, love it!
- [stb headers](https://github.com/nothings/stb) (C): great source of inspiration and knowledge. There are some other headers in the creator's website such as [stb_malloc.c](https://nothings.org/stb/stb_malloc.h).
- [raylib](https://github.com/raysan5/raylib) (C99): simple 2D/3D graphics library
- [miniaudio](https://github.com/mackron/miniaudio) (C): my goto library to play and mix audio
- [micro-headers](https://github.com/San7o/micro-headers) (C99): my own cool libraries for all my other projects
- [SFML](https://github.com/SFML/SFML) (c++17): another great multimedia library, more ideomatic for C++
- [csynth](https://github.com/leovandriel/csynth) (C):  A simple synth in C, very fun to explore the code, It is somewhat unusual and enlightening.
- [luigi](https://github.com/nakst/luigi) (C): single header GUI framework in C. It is absurdly simple and well written, amazing read.
- [nginx](https://github.com/nginx/nginx) (C): even if it is not a library, each source file is well divided from the others so that you can copy paste almost everything in your projects!

### Minor Contributions

Minor contributions all over the interweb:

- https://github.com/riscv/riscv-opcodes/pull/375: Correct parse.py example
- https://github.com/ColleagueRiley/RGFW/pull/329: fix example program

</details>

