# Newcastle University Thesis Guidelines LaTeX Template

![Newcastle University Logo](Newcastle_University_logo.png)

LaTeX template for the [University Thesis Guidelines](https://www.ncl.ac.uk/students/progress/assets/documents/GuidelinesfortheSubmissionandFormatofThesis-January2018.pdf).

## Usage Instructions

### Linux and Mac
Use the following command in a desired folder to generate a new `.tex` file.
```
curl https://raw.githubusercontent.com/SzyJ/Newcastle_University_Thesis_Template/master/thesis.tex >> thesis.tex
```

alternatively, for bash users...

Add this to you .bashrc
```
download_latex_template() {
    if [ $# -eq 0 ]
    then
        curl https://raw.githubusercontent.com/SzyJ/Newcastle_University_Thesis_Template/master/thesis.tex >> thesis.tex
    else 
        curl https://raw.githubusercontent.com/SzyJ/Newcastle_University_Thesis_Template/master/thesis.tex >> "$1".tex
    fi
}
alias latextemp='download_latex_template'
```
You can now create a new `example.tex` file from the template like so:
```
latextemp example
```

### Windows
Copy the code from [this](https://raw.githubusercontent.com/SzyJ/Newcastle_University_Thesis_Template/master/thesis.tex) link and paste it into a new `.tex` file.
