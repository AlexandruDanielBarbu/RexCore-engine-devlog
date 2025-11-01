# Chapter 0 - Uneasy Beginnings

## Motivation

## So where do I start?

## Mistakes along the way

Cmake
    - LANGUAGE instead of LANGUAGES (plural)
    - trying to build the main.cpp but main.cpp has no main function
        - fix: add some line that tells the compiler to use main as entry point not WinMain()
    - `cmake --build .` was not building anything
        - Turns out i forgot to update main.cpp so cmake had nothing to build, everything was already built
    - after successfully building my project, running it resulted in a bunch of error
        - turns out i compiled for g++ not visual studio compiler mvc something.
    - executable now runs correctly