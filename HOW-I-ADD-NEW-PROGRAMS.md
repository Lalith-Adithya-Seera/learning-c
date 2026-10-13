# How I add my next C program

This is the short version for adding another small program to this learning log.

## Before starting

Make sure this repository is on your Mac. If it is not, open the repo on GitHub, choose **Code**, copy the HTTPS link, then in VS Code choose **Clone Repository** and paste that link. Open the cloned `learning-c` folder in VS Code, then open its terminal (**Terminal → New Terminal**).

Check that Git is available:

```sh
git --version
```

If macOS offers to install developer tools, choose **Install**. A version number means Git is ready.

Check that the Xcode Command Line Tools are installed:

```sh
xcode-select -p
```

A path is printed when the tools are installed. If macOS says no developer tools were found, run `xcode-select --install` and follow the install prompt. These tools include the `clang` C compiler.

## Add and push a program

1. Create a numbered folder such as `02-variables/` and save the new `.c` file inside it.
2. Add a new row to the **Programs** table in `README.md` with the date, what the program does, and what you learned.
3. In the VS Code terminal, run these four Git commands from the repository folder:

   ```sh
   git status
   git add 02-variables/ README.md
   git commit -m "Add variables practice"
   git push
   ```

   - `git status` shows what changed; check that your new file and README are listed.
   - `git add` selects those changes for the next save.
   - `git commit` saves a named checkpoint on your Mac.
   - `git push` sends your committed work to GitHub.

For the next program, replace `02-variables/` and the commit message with names that describe that program. If Git asks you to set your name or email the first time you commit, follow its instructions before trying the commit again.
