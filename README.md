# LaTex via Atom

# LiveTex setup
0. Install LiveTex (https://www.tug.org/texlive/)

# Atom setup
0. Install Atom (https://atom.io/)
1. File -> Settings -> Install Packages:
2. Required packages:
    * language-latex 1.2.0 (https://atom.io/packages/language-latex)
    * latex 0.50.2 (https://atom.io/packages/latex)
    * pdf-view 0.72.0 (https://atom.io/packages/pdf-view)
    
# Packages setup
* language-latex:
    * default
* pdf-view:
    * default
* latex:
    * `TexPath` : C:\%installpath%\texlive\2019\bin\win32
    * `Engine`  : pdflatex
    * `Enable Shell Escape` : no
    * `Enable SynTex` : no
    * `Use DiCy` : no
    * `Enable Extended Build Mode` : no
    * `Logging Level` : info
    * `Output Format` : pdf
    * `PDF Producer` : dvipdfmax
    * `Move Result to Source Directory` : yes
    * `Build on Save` : yes
    * `Open Result after Successful Build` : yes
    * `Open Result in Background` : yes
* Open document
* Packages -> Latex -> Check Runtime
* `Ctrl+Alt+b` to build solution
* Open file directory, find res .pdf, drag and drop it into Atom split screen
