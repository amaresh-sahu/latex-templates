# Latex Templates
Latex templates for a variety of different documents. Current files include templates for
- problem sets
- one-column papers


Coming soon are templates for
- two-column papers
- resumes
- CVs


Eventually, I will include examples of how I use Latex outside of documents. This includes
- slideshows (the equivalent of PowerPoint presentations, but all in Latex)
- figures
- posters

# Compiling Documents
I use Xelatex and Biber to compile documents. From the command line, run `xelatex <filename>.tex`. If you made changes to the `refs.bib` file, or you are compiling a file with references for the first time, next run `xelatex <filename>.bcf`. Finally, run `xelatex <filename>.tex` once again.

If you are compiling from a Latex software suite, you should be able to compile directly from that software. Please let me know of any problems you encounter!
