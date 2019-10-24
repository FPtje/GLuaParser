GLuaParser
==========

# Warning! 
This repository is out of date! The latest version of the lexer and parser are included as a library in the following repository:
https://github.com/FPtje/GLuaFixer

-------

WIP Lexer/Parser for Garry's mod's variant of Lua.

# Compiling

- Make sure cabal is installed
- `cabal configure && cabal build`
- The executable will appear in the `dist/build/gluaparser/` folder

# Profiling
This program can be profiled. Compile the program with profiling tags:

`ghc --make -prof -auto-all -rtsopts Main`

Then execute the compiled program with RTS options:
`./Main <command> <file>  +RTS -K100M -p -hc`
