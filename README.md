# Mina Mikhail's (aka fightingtheboss) Resume

Tired of managing different versions of my resume, I drew inspiration from [Alessia Bellisario's "resume-as-code"](https://aless.co/resume-as-code) and moved my resume design to LaTeX.

Rather than start from scratch, given that my initial knowledge of LaTeX was minimal, I used one of the templates provided by [resumake.io](https://resumake.io), which gave me clean, well-structured LaTeX code as a jump-off point.

## Usage
To generate a PDF from this LaTeX code, navigate to this folder in a terminal and run:

    xelatex resume.tex

## Requirements
You will need to have `xelatex` installed on your machine. On a Mac, you can install MacTex, which includes all of the libraries you'll need, via `brew cask install mactex`, or via the provided binaries at https://www.tug.org/mactex/

Alternatively, you can use a site like [ShareLaTeX](https://sharelatex.com) to build and edit your LaTeX instead.
