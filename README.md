# DAIICT-resume-latex
DAIICT resume format in latex.

* There are 2 ways, you can use this resume template to make your resume:

1. Installing Latex on your machine
2. Use [ShareLatex Website](https://www.sharelatex.com?r=a4a63167&rm=d&rs=b) to avoid installing Latex on local machine.

### 1. Installing Latex on your machine

Since Installing Latex on your machine requires minimum 2 GB of bandwidth and hard to maintain 
it if you are newbie, please go with 2nd option.

##### Installing Latex on Ubuntu

`sudo apt-get install texlive-full`

It will install all necessary files, fonts and packages. (Expected download > 2 GB)

1. After installing, download this repo.
2. Compile using `xelatex` or `lualatex` by using below command.

```
xelatex cv.tex
OR
lualatex cv.tex
```

NOTE: If you use `xelatex`, please install fonts(OTF files) by double-clicking on them.

### 2. Use sharelatex

[Sharelatex](https://www.sharelatex.com?r=a4a63167&rm=d&rs=b) is website that allows to write latex files and generate PDF files for it. Follow below steps:

1. Make an account on Sharelatex.
2. Download .zip file from this repo.
3. Upload all files to a new project on Sharelatex.
4. Use below settings from left sidebar in Project view:
```
Compiler: LuaLatex
PDF Viewer: Native
```
5. Edit your details.
6. Press recompile and you will be able to generate your pdf.

DAIICT logo is property of www.daiict.ac.in . All rights are reserved by DAIICT. Used with 
permission.