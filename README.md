# Hokudai Dissertation

## Introduction
This is a LaTeX template based on [Dissertate Project](https://github.com/suchow/Dissertate). See the sample [HERE](https://eprints.lib.hokudai.ac.jp/dspace/bitstream/2115/70225/1/Zhai_HongJie.pdf).

## Getting started
1. Install LaTeX. For Mac OS X, we recommend MacTex (http://tug.org/mactex/); for Windows, MiKTeX (http://miktex.org/); and for Ubuntu, Tex Live (`sudo apt-get install texlive-full`)
2. Install the default fonts: EB Garamond, Lato, and Source Code Pro. The files are provided in `fonts/EB Garamond`, `fonts/Lato`, and `fonts/Source Code Pro`.
3. Personalize the document by filling out your name and all the other info in `frontmatter/personalize.md`.
4. Build your dissertation with `build.command`, located in the `scripts` directory (e.g., you can `cd` into the main directory and then run `./scripts/build.command`).
5. Or, you can use `xelatex` to compile your files manually.

## FAQ

### How do I make the text justified instead of ragged right?
Remove or comment out the line `\RaggedRight` from the .cls file.
