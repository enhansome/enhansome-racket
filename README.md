# Awesome Racket with stars

<a href="https://awesome-racket.com/"><img align="right" src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c1/Racket-logo.svg/240px-Racket-logo.svg.png" alt="awesome-racket" title="awesome-racket" /></a>

A curated list of **Awesome Racket**, libraries and software. Inspired by [awesome-go](https://github.com/avelino/awesome-go) ⭐ 182,150 | 🐛 215 | 🌐 Go | 📅 2026-08-24.

[![Build Status](https://github.com/avelino/awesome-racket/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/avelino/awesome-racket/actions/workflows/ci.yml?query=branch%3Amain) ⭐ 507 | 🐛 0 | 🌐 Racket | 📅 2023-06-24
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 499,615 | 🐛 106 | 📅 2026-08-21

<a href="https://www.producthunt.com/posts/awesome-racket?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-awesome-racket" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=326738&theme=light" alt="awesome-racket - A curated list of awesome Racket language | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a>

[Check the complete package list](https://pkgs.racket-lang.org/)

[The Racket repository](https://github.com/racket/racket) ⭐ 5,198 | 🐛 603 | 🌐 Racket | 📅 2026-08-21

### Contents

* [Awesome Racket](#awesome-racket)
  \- [Contents](#contents)
  * [Audio and Music](#audio-and-music)
  * [Compilers](#compilers)
  * [Data Structures](#data-structures)
  * [Database Drivers](#database-drivers)
  * [Emulators](#emulators)
  * [GUI Development](#gui-development)
  * [Game Development](#game-development)
  * [Games](#games)
  * [Images](#images)
  * [Machine Learning](#machine-learning)
  * [Macros](#macros)
  * [Messaging](#messaging)
  * [Third-party APIs](#third-party-apis)
  * [Testing](#testing)
  * [Web Frameworks](#web-frameworks)

## Audio and Music

*Libraries for manipulating audio.*

* [RSound](https://github.com/jbclements/RSound) ⭐ 45 | 🐛 29 | 🌐 Racket | 📅 2026-04-02 - A framework for manipulating and playing sounds using the portaudio library. Runs on Windows, Mac OS X, and linux.
* [rsc3](https://github.com/quakehead/rsc3) ⭐ 18 | 🐛 0 | 🌐 Racket | 📅 2024-09-16 - SuperCollider client ported to Racket.
* [portaudio](https://github.com/jbclements/portaudio) ⭐ 10 | 🐛 7 | 🌐 Racket | 📅 2026-03-29 - Bindings for portaudio, a cross-platform audio library.
* [osc](https://github.com/jbclements/osc) ⭐ 6 | 🐛 3 | 🌐 Racket | 📅 2024-02-04 - Open Sound Control data definitions.
* [sonic-pi](https://github.com/jbclements/sonic-pi) ⭐ 6 | 🐛 0 | 🌐 Clojure | 📅 2017-11-15 - For now, this package starts scsynth just like sonic pi does, and can make a few sounds.
* [libopenal-racket](https://github.com/lehitoskin/libopenal-racket) ⭐ 3 | 🐛 0 | 🌐 Racket | 📅 2024-11-09 - Racket wrapper to the OpenAL library first written by gcr in 2012.
* [midi-readwrite](https://github.com/jbclements/midi-readwrite) ⭐ 3 | 🐛 0 | 🌐 Racket | 📅 2017-05-08 - Library to read .mid files in racket
* [rtmidi](https://github.com/jbclements/rtmidi) ⭐ 3 | 🐛 1 | 🌐 Racket | 📅 2021-03-29 - Provides racket bindings for the RtMidi library, thus enabling racket programs to send and receive MIDI events.
* [taglib](https://github.com/takikawa/taglib-racket) ⭐ 3 | 🐛 0 | 🌐 Racket | 📅 2016-11-01 - Bindings to the taglib C library, which provides simple access to audio file metadata.
* [3s](https://github.com/jeapostrophe/3s) ⭐ 2 | 🐛 0 | 🌐 Racket | 📅 2022-05-14 - Positional sound and mixing for lux and other applications.
* [openal](https://github.com/jeapostrophe/openal) ⭐ 1 | 🐛 0 | 🌐 Racket | 📅 2024-10-25 - FFI for OpenAL.
* [wavelet-transform-haar-1d](https://github.com/jbclements/wavelet-transform-haar-1d) ⭐ 0 | 🐛 0 | 🌐 Racket | 📅 2016-01-21 - A library to perform forward and reverse 1-d Haar Wavelet transforms.

## Compilers

*Tools for compiling Racket to other languages.*

* [racketscript](https://github.com/racketscript/racketscript) ⭐ 736 | 🐛 81 | 🌐 Racket | 📅 2026-02-18 - A lightweight Racket to JavaScript compiler with some batteries included.
* [urlang](https://github.com/soegaard/urlang) ⭐ 308 | 🐛 8 | 🌐 Racket | 📅 2026-03-05 - Write JavaScript with Racket syntax. Bonus: Use Racket to define macros for JavaScript constructs.
* [minipascal](https://github.com/soegaard/minipascal) ⭐ 92 | 🐛 0 | 🌐 Pascal | 📅 2021-09-26 - MiniPascal as a Racket language.
* [disassemble](https://github.com/samth/disassemble) ⭐ 84 | 🐛 1 | 🌐 Scheme | 📅 2026-06-29 - Disassembler for Racket.
* [lens](https://github.com/jackfirth/lens) ⭐ 79 | 🐛 49 | 🌐 Racket | 📅 2019-09-10 - A Racket package for creating and composing pure functional lenses.
* [wasm-adventure](https://github.com/euhmeuh/wasm-adventure) ⭐ 74 | 🐛 1 | 🌐 Racket | 📅 2018-08-03 - A WebAssembly DSL.
* [zordoz](https://github.com/bennn/zordoz) ⭐ 26 | 🐛 10 | 🌐 Racket | 📅 2021-10-24 - Explorer for .zo bytecode files.
* [wracket](https://github.com/sschauss/wracket) ⭐ 23 | 🐛 0 | 🌐 Racket | 📅 2017-11-26 - Lisp-like language to WebAssembly build with racket.
* [whalesong-tools](https://github.com/vishesh/drracket-whalesong) ⭐ 3 | 🐛 6 | 🌐 Racket | 📅 2015-06-08 - DrRacket tool for compiling with Whalesong.
* [abstract-compilation](https://github.com/philnguyen/abstract-compilation) ⭐ 2 | 🐛 0 | 🌐 Racket | 📅 2018-03-07 - DSL reducing boiler plates for doing abstract compilation.

## Data Structures

*Generic datastructures and algorithms.*

* [algebraic](https://github.com/dedbox/racket-algebraic) ⭐ 78 | 🐛 36 | 🌐 Racket | 📅 2024-07-16 - Algebraic structures for untyped Racket.
* [graph](https://github.com/stchang/graph) ⭐ 60 | 🐛 18 | 🌐 Racket | 📅 2023-11-21 - Generic graph library.
* [gls](https://github.com/Kalimehtar/gls) ⭐ 18 | 🐛 0 | 🌐 Racket | 📅 2024-05-05 - Generic Little (Object, Type, Anything, etc) System - multiple dispatch on types.
* [dssl2](https://github.com/tov/dssl2) ⭐ 9 | 🐛 15 | 🌐 Racket | 📅 2026-08-20 - A language for data structures students.
* [dssl](https://github.com/tov/dssl) ⭐ 5 | 🐛 0 | 🌐 Racket | 📅 2017-07-02 - Data Structures Student Language: an extension of ASL for easier imperative programming.
* [phc-adt](https://github.com/jsmaniac/phc-adt) ⭐ 3 | 🐛 12 | 🌐 Racket | 📅 2021-05-13 - Algebraic Data Types for Typed/Racket, with features tailored to compiler writing. The data types do not have to be declared before they are used, like prefab structs and symbols. Behind the scenes, this library remembers all the data types in a file, and uses it to implicitly pre-declare them. Mostly stable, although some things may change a bit in the future.
* [quad-tree](https://github.com/dented42/racket-quad-tree) ⭐ 1 | 🐛 0 | 🌐 Racket | 📅 2016-04-08 - A fairly simple quad-tree implementation. Nothing terribly fancy. Currently rather unstable.
* [opt](https://gitlab.com/RayRacine/opt) - Optional and Either data type utilities. Provides util function for Typed Racket's Option type as well as defines an Either type.
* [rebellion](https://docs.racket-lang.org/rebellion/index.html) - Dozens of well-documented modules to aid in general-purpose programming. **Extensive**. Includes multidict, range set, and much more.
* [try](https://gitlab.com/RayRacine/try) - A Typed Racket Try datatype and routines for computations that throw exceptions.

## Database Drivers

*Libraries for connecting and operating databases.*

* [deta](https://github.com/Bogdanp/deta) ⭐ 65 | 🐛 6 | 🌐 Racket | 📅 2026-07-16 - A functional database mapper.
* [sql](https://github.com/rmculpepper/sql) ⭐ 33 | 🐛 12 | 🌐 Racket | 📅 2022-03-24 - an S-expression notation for SQL.
* [racquel](https://github.com/brown131/racquel) ⭐ 25 | 🐛 4 | 🌐 Racket | 📅 2021-03-10 - Racquel is an object/relational mapper for Racket.
* [db](https://github.com/racket/db) ⭐ 24 | 🐛 3 | 🌐 Racket | 📅 2026-08-11 - Database connectivity (main distribution).
* [mongodb](https://github.com/jeapostrophe/mongodb) ⭐ 18 | 🐛 2 | 🌐 Racket | 📅 2023-01-05 - A native Racket interface to MongoDB & BSON.
* [redis](https://github.com/stchang/redis) ⭐ 17 | 🐛 9 | 🌐 Racket | 📅 2015-05-16 - A redis client for Racket.
* [rackdis](https://github.com/eu90h/rackdis) ⚠️ Archived - Redis bindings.
* [dbm](https://github.com/jeapostrophe/dbm) ⭐ 4 | 🐛 0 | 🌐 Racket | 📅 2019-12-18 - An interface to UNIX dbm files using a libdbm FFI.
* [fra](https://github.com/jeapostrophe/fra) ⚠️ Archived - Purely functional implementation of relational algebra.
* [binary-class-dbf](https://github.com/Kalimehtar/binary-class-dbf) ⭐ 3 | 🐛 0 | 🌐 Racket | 📅 2014-10-07 - Interface to \*.dbf files (dBase, Foxpro, etc).
* [sqlite-table](https://github.com/jbclements/sqlite-table) ⭐ 0 | 🐛 0 | 🌐 Racket | 📅 2017-12-05 - A quick way to create and query sqlite tables. Basically a simplified wrapper for a subset of the db library.

## Emulators

*Racket programs emulating other computers and architectures*

* [virtual-mpu](https://github.com/euhmeuh/virtual-mpu) ⭐ 17 | 🐛 0 | 🌐 Racket | 📅 2018-09-10 - Universal Emulator & Assembler for Old Microprocessors.
* [6502](https://github.com/soegaard/6502) ⭐ 12 | 🐛 0 | 🌐 Racket | 📅 2018-07-13 - An emulator/assembler/disassembler for 6502.

## GUI Development

*Libraries for cross platform GUI development*

* [gui-easy](https://github.com/Bogdanp/racket-gui-easy) ⭐ 153 | 🐛 8 | 🌐 Racket | 📅 2026-06-12 - A declarative API on top of `racket/gui`.
* [MrEd Designer](https://github.com/Metaxal/MrEd-Designer) ⭐ 63 | 🐛 9 | 🌐 Racket | 📅 2021-05-06 - MrEd Designer is WYSIWYG program to create GUI applications for Racket. (code generator).
* [The Racket Graphical Interface Toolkit](https://docs.racket-lang.org/gui/index.html) - Racket GUI library (core distribution).
* [gui-widget-mixins](https://pkgs.racket-lang.org/package/gui-widget-mixins) - Tool tips, cue text and validation for text-field% GUI widgets in Racket.
* [map-widget](https://pkgs.racket-lang.org/package/map-widget) - A Racket GUI Widget to display maps based on OpenStreetMap tiles
  More at [packages tagged `GUI`](https://pkgd.racket-lang.org/pkgn/search?q=\&tags=gui).

## Game Development

*Awesome game development libraries.*

* [get-bonus](https://github.com/get-bonus/get-bonus) ⭐ 104 | 🐛 1 | 🌐 Racket | 📅 2021-03-10 - An experimental video game development environment.
* [mode-lambda](https://github.com/jeapostrophe/mode-lambda) ⭐ 42 | 🐛 2 | 🌐 Racket | 📅 2021-10-04 - Sprite-based 2D graphics engine.
* [pict3d](https://github.com/jeapostrophe/pict3d) ⭐ 40 | 🐛 10 | 🌐 Racket | 📅 2025-01-16 - A 3D engine with a purely functional API.
* [game-engine](https://github.com/srfoster/game-engine) ⭐ 32 | 🐛 0 | 🌐 Racket | 📅 2020-08-17 - Scratchpad for racket game stuff.
* [vr-lang](https://github.com/thoughtstem/vr-lang) ⭐ 10 | 🐛 3 | 🌐 Racket | 📅 2020-06-09 - Racket Lang for Virtual Reality (Aframe).
* [apse](https://github.com/jeapostrophe/apse) ⚠️ Archived - A Pixel Sprite Editor.
* [towers](https://github.com/Metaxal/towers) ⭐ 5 | 🐛 0 | 🌐 Racket | 📅 2021-11-01 - Towers is an original 2-player board game.

## Games

*Games written in Racket*

* [r-cade](https://github.com/massung/r-cade) ⭐ 287 | 🐛 9 | 🌐 Racket | 📅 2023-07-05 - Retro Game Engine for Racket.
* [Racket games](https://github.com/racket/games) ⭐ 51 | 🐛 1 | 🌐 Racket | 📅 2026-08-11 - games in main distribution.
* [space-invaders](https://github.com/soegaard/space-invaders) ⭐ 7 | 🐛 0 | 🌐 Racket | 📅 2015-02-21 - A Racket remake of Mary Rose Cook's JavaScript version of Space Invaders.
* [web-sweeper](https://github.com/Halfwake/web-sweeper) ⭐ 7 | 🐛 2 | 🌐 Racket | 📅 2017-11-21 - Stateless Server Side Mine Sweeper.

## Images

*Libraries for manipulating images.*

* [video](https://github.com/videolang/video) ⭐ 142 | 🐛 22 | 🌐 Racket | 📅 2019-11-17 - Video is a DSL for describing videos.
* [racket-jpeg](https://github.com/wingo/racket-jpeg) ⭐ 18 | 🐛 2 | 🌐 Racket | 📅 2016-09-18 - JPEG parsing, transformation, and codec library for Racket.
* [simple-qr](https://github.com/simmone/racket-simple-qr) ⭐ 13 | 🐛 1 | 🌐 Racket | 📅 2024-06-15 - a qr code tool for racket-lang.
* [png-image](https://github.com/lehitoskin/png-image) ⭐ 1 | 🐛 1 | 🌐 Racket | 📅 2019-05-21 - Library to view and modify PNG chunks.

## Machine Learning

*Libraries for Machine Learning.*

* [layer](https://github.com/cloudkj/layer) ⭐ 560 | 🐛 0 | 🌐 Scheme | 📅 2019-04-21 - Neural network inference the Unix way.
* [DeepRacket](https://github.com/charlescearl/DeepRacket) ⭐ 69 | 🐛 6 | 🌐 Racket | 📅 2026-03-28 - A simple starting point for doing deep learning in Racket.
* [racket-ml](https://github.com/danking/racket-ml) ⭐ 25 | 🐛 2 | 🌐 Racket | 📅 2018-12-20 - A collection of things I found useful for doing Machine Learning problem sets.
* [racket-knn](https://github.com/asbaker/racket-knn) ⭐ 16 | 🐛 0 | 🌐 Racket | 📅 2013-04-17 - K Nearest Neighbors, KNN, is a lazy, supervised machine learning algorithm. This is an implementation in scheme using racket.
* [rml-core](https://github.com/johnstonskj/rml-core) ⭐ 14 | 🐛 0 | 🌐 Racket | 📅 2024-06-18 - This Package is part of an expected set of packages implementing machine learning capabilities for Racket. The core of this package is the management of 'datasets', these datasets are assumed to be for training and testing of machine learning capabilities.
* [rml-decisiontrees](https://github.com/johnstonskj/rml-decisiontrees) ⭐ 4 | 🐛 0 | 🌐 Racket | 📅 2024-06-18 - This Package is part of a set of packages implementing machine learning capabilities for Racket. This particular package implements support for classification of individuals using decision trees.
* [rml-knn](https://github.com/johnstonskj/rml-knn) ⭐ 1 | 🐛 0 | 🌐 Racket | 📅 2024-03-25 - This Package is part of a set of packages implementing machine learning capabilities for Racket. This particular package implements the K-Nearest Neighbor approach for classification.
* [tesseract](https://github.com/lasfter/tesseracket) - Bindings for Google's Tesseract-OCR.

## Macros

*Awesome macros that make your life easier*

* [threading](https://github.com/lexi-lambda/threading) ⭐ 53 | 🐛 1 | 🌐 Racket | 📅 2024-10-11 - Macros to flatten nested function calls.
* [anaphoric](https://github.com/jsmaniac/anaphoric) ⭐ 8 | 🐛 0 | 🌐 Racket | 📅 2021-07-29 - Anaphoric macros for Racket.

## Messaging

*Libraries that implement messaging systems.*

* [neuron-lib](https://github.com/dedbox/racket-neuron) ⭐ 16 | 🐛 19 | 🌐 Racket | 📅 2022-05-16 - Implementation of neuron.
* [profj](https://github.com/mflatt/profj) ⭐ 11 | 🐛 2 | 🌐 Scheme | 📅 2023-08-08 - Kathy Gray's ProfessorJ language ported to modern DrRacket.
* [zmq](https://github.com/mordae/racket-zmq) ⭐ 4 | 🐛 3 | 🌐 Racket | 📅 2015-09-02 - Minimal Racket ZeroMQ Bindings.
* [zeromq-r](https://github.com/rmculpepper/racket-zeromq) ⭐ 3 | 🐛 2 | 🌐 Racket | 📅 2022-05-27 - Bindings for ZeroMQ.
* [stomp](https://github.com/tonyg/racket-stomp) - STOMP messaging protocol codec and client.

## Third-party APIs

*Libraries for accessing third party APIs.*

* [aws](https://github.com/greghendershott/aws) ⭐ 80 | 🐛 13 | 🌐 Racket | 📅 2026-04-17 - Amazon Web Services including S3, SDB, SES, SNS, SQS, CloudWatch, Glacier, Dynamo, and Route 53.
* [racket-ovh](https://github.com/euhmeuh/racket-ovh) ⭐ 1 | 🐛 0 | 🌐 Racket | 📅 2018-04-06 - Unofficial Racket wrapper for OVH API.
* [recaptcha](https://github.com/LiberalArtist/recaptcha) ⭐ 1 | 🐛 0 | 🌐 Racket | 📅 2022-12-08 - Utilities for using reCAPTCHA with the web-server/formlets API.
* [comm-panel](https://github.com/thoughtstem/comm-panel) ⭐ 0 | 🐛 0 | 🌐 Racket | 📅 2018-06-16 - Racket GUI widget for sending, receiving, listening, and broadcasting strings over AWS SQS.
* [aws-cloudformation-deploy](https://github.com/cjdev/aws-cloudformation-deploy) AWS Cloudformation deployment scripting library.
* [google](https://github.com/tonyg/racket-google) - Google APIs (Drive, Plus, etc) for Racket.

## Testing

*Libraries for testing codebases and generating test data*

* [cover](https://github.com/florence/cover) ⭐ 39 | 🐛 14 | 🌐 Racket | 📅 2024-05-16 - a code coverage tool for racket.
* [al2-test-runner](https://github.com/alex-hhh/al2-test-runner) ⭐ 2 | 🐛 0 | 🌐 Racket | 📅 2020-08-28 - alternate rackunit test runner.
* [test-more](https://github.com/dstorrs/racket-test-more) ⭐ 1 | 🐛 0 | 🌐 Racket | 📅 2023-03-09 - A Racket version of Perl's Test::More library.
* [RackUnit](https://docs.racket-lang.org/rackunit/) - RackUnit is a unit-testing framework for Racket. It is designed to handle the needs of all Racket programmers, from novices to experts.

## Web Frameworks

*Full stack web frameworks.*

* [frog](https://github.com/greghendershott/frog) ⭐ 940 | 🐛 41 | 🌐 Racket | 📅 2026-08-20 - Frog is a static blog generator implemented in Racket, targeting Bootstrap and able to use Pygments.
* [Spin](https://github.com/dmac/spin) ⭐ 231 | 🐛 4 | 🌐 Racket | 📅 2017-07-27 - Write RESTful web apps in Racket.
* [koyo](https://github.com/Bogdanp/koyo) ⭐ 158 | 🐛 0 | 🌐 Racket | 📅 2026-07-19 - A web development toolkit for Racket.
* [Rackt](https://github.com/rackt-org/rackt) ⭐ 61 | 🐛 2 | 🌐 Racket | 📅 2025-04-02 - An ultrasmall (\~70 loc) React wrapper written in RacketScript.
* [riposte](https://github.com/vicampo/riposte) ⭐ 46 | 🐛 7 | 🌐 Racket | 📅 2021-10-13 - Scripting language for testing JSON-based HTTP APIs.
* [vela](https://github.com/nuty/vela) ⭐ 41 | 🐛 0 | 🌐 Racket | 📅 2023-07-14 - Simple web framework to build RESTful app in Racket.
* [web-galaxy](https://github.com/euhmeuh/web-galaxy) ⭐ 27 | 🐛 1 | 🌐 Racket | 📅 2023-03-10 - A minimalist web framework for the Racket web-server.
* [racket-request](https://github.com/jackfirth/racket-request) ⭐ 23 | 🐛 8 | 🌐 Racket | 📅 2022-08-02 - Package for simplifying HTTP requests and writing integration tests of REST-ful APIs in Racket.
* [Routy](https://github.com/Junker/routy) ⭐ 22 | 🐛 0 | 🌐 Racket | 📅 2022-08-30 - Routy is a lightweight high performance HTTP request router for Racket.
* [polkadot](https://github.com/2-3/polkadot) ⭐ 19 | 🐛 0 | 🌐 Racket | 📅 2017-05-19 - A lightweight personal wiki in Racket.
* [HoLy](https://github.com/nihirash/holy) ⭐ 12 | 🐛 0 | 🌐 Racket | 📅 2017-11-03 - HoLy is simple a HTTP-server Library for Racket.
* [web-server/servlet](http://docs.racket-lang.org/web-server/) - Running Web Servlets describes how to run the servlets you’ve written.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-24._
