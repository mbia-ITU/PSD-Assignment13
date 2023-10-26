# Assignment 13

Solved by the group Recursive Rebels.

## Exercises

Chapter 14: 14.1, 14.2, 14.3 (not curriculum as not supported on Mac).

Alternatively you can do assignment 3, 4 and 5 in exam set from January 2017. 

## Run instructions

```{}
fslex --unicode <LexerSpecification>.fsl
fsyacc --module <ParserName> <ParserSpecification>.fsy
dotnet fsi -r FsLexYacc.Runtime.dll ...
```

On MacBook

```{}
mono ~/bin/fsharp/fslex.exe --unicode <LexerSpefication>.fsl
mono ~/bin/fsharp/fsyacc.exe --module <ParserName> <ParserSpecification>.fsy
dotnet fsi -r FsLexYacc.Runtime.dll ...
```

## Handin details

Handin file name:

- BPRD-13-AMDH-EMNO-MBIA.zip

Files to handin:

- 
