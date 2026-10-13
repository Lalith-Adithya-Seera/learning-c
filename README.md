# Learning C

Hey! This is my learning log as a Mahindra University student learning C on a Mac. I’m starting with small programs and adding what I learn as I go.

## Programs

| Date | Program | What it does | What I learned |
|---|---|---|---|
| 2026-10-13 | [Hello World](01-hello-world/hello.c) | Prints “Hello World!” | A C program starts in `main`; `printf` prints text. I compiled it with `clang` and ran it with `./myfirstprogram`. |

## Compile and run

From the repository folder in Terminal:

```sh
clang 01-hello-world/hello.c -o myfirstprogram
./myfirstprogram
```

The first command compiles the C source into a program named `myfirstprogram`. The second runs it. The compiled program is ignored by Git, so only the source code is tracked.

## Adding the next program

See [HOW-I-ADD-NEW-PROGRAMS.md](HOW-I-ADD-NEW-PROGRAMS.md) for a beginner-friendly guide to Git and checking the Mac tools.
