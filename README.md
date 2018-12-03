# Latex Templates
Latex templates for a variety of different documents. Current files include templates for
- problem sets
- plotting data
- papers (single column)


Eventually, I plan to add templates for
- resumes
- CVs
- slideshows
- figures
- posters
- PhD theses


# Compiling Documents
I use Xelatex and Bibtex to compile documents. From the command line, run `xelatex <filename>.tex`. If you made changes to the `refs.bib` file, or you are compiling a file with references for the first time, next run `bitex <filename>.aux`. Finally, run `xelatex <filename>.tex` twice more.

If you are compiling from a Latex software suite, you should be able to compile directly from that software. Please let me know of any problems you encounter!
