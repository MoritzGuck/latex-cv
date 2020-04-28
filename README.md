# Industry latex-cv: A minimal curriculum vitæ template in German/Swiss style

This repository is an adaptation of Bastian Riecks template for academic CVs: 
[Original Repo](https://github.com/Pseudomanifold/latex-cv). Check it out, especially if you write an academic CV. 
If you like it or find areas for improvement, write me or open an issue. 

## Requirements

The current font is Avenir Next. If you want to use it, you need to put the respective .ttc-file into the folder or change the directory in the preamble of the `styling.tex`-file. 

## Using the template

I belief in separating the content from the formatting (you can change the formatting once and your different CV-versions will all adapt automatically). The `styling.tex`contains the formatting.
If you want to change the formatting, look at the `TODO`-comments. 
The actual content is saved in the `CV.tex`file.

Use luatex to build the project, otherwise it will mess up your formatting:

    latexmk -pdflatex=lualatex -pdf CV

## License

The project uses the MIT-license: [`LICENSE.md`](LICENSE.md)

## Some CV-tipps

* Adapt your CV for each company (Make it relevant for the position)
* Use the company-lingo in your CV (for keyword-search algorithms)
* Be sure that you can backup everything that is written and write about things that are attributable to you
* Highlight text that the recruiter is looking for 