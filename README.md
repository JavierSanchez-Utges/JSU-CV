# _Curriculum Vitae_ of Javier Sánchez Utgés
This repository contains my personal CV generated with [RenderCV](https://docs.rendercv.com/). RenderCV is a Python application to create a $\LaTeX$ as a PDF from a JSON/YAML input file. It is really easy to install, run and offers multiple templates and flexibility for customisation. The following start guide is grabbed from their [website](https://docs.rendercv.com/). You can find their GitHub repository [here](https://github.com/sinaatalay/rendercv).

Click [**here**](rendercv_output/Javier_Sánchez_Utgés_CV.pdf) to see the current version of my CV in _.PDF_ format!

[![DOI](https://zenodo.org/badge/893465524.svg)](https://doi.org/10.5281/zenodo.14212305)

## Quick Start Guide

1. Install [Python](https://www.python.org/downloads/) 3.10 or newer.
   
2. Run the command below in a terminal to install RenderCV.
   
   ```
   pip install rendercv
   ```
   
3. Run the command below to generate starting input files.

   ```
   rendercv new "Full Name"
   ```

4. Edit the contents of _Full_Name_CV_.yaml in your favorite editor (tip: use an editor that supports JSON Schemas. I used [Sublime](https://www.sublimetext.com/) for example).

5. Run the command below to generate your CV.

    ```
    rendercv render Full_Name_CV.yaml
    ```

For more instructions, refer to the RenderCV [website](https://docs.rendercv.com/) or their PyPi [site](https://pypi.org/project/rendercv/).

## Output

RenderCV generates rich output including _.HTML_, _.MD_, _.PDF_, _.PNG_ and ._TEX_ files. Check the [rendercv_output](/rendercv_output) directory for this.

## First Page of my CV

![JSU_CV_page1](/rendercv_output/Javier_Sánchez_Utgés_CV_1.png)

## Acknowledgements

I wanted to thank the **RenderCV** contributors for their tool, [Tanmayee Narendra](https://github.com/ntanmayee) for recommending this tool and [Radoslav Krivák](https://github.com/rdk) for suggesting I make this repository.


