# HCI-Master-Thesis-Template
An Overleaf template for the Master thesis in HCI at the PLUS and SUAS


This is a template for theses written in the HCI Master of the PLUS and the SUAS. It tries to follow the provided guidelines closely (02/2022). To create this template, this tutorial series has been consulted: %% https://de.overleaf.com/learn/latex/How_to_Write_a_Thesis_in_LaTeX_(Part_1)%3A_Basic_Structure}

MOST IMPORTANT: check back with your supervisor if this template is sufficient for them. 

The template is split into these folders and files: Chapters, Front and Back Chapters, Images, main.tex, reference.bib and titlepage.tex

Chapters include all main text sections as .tex files.
Front and Back Chapters include Abstract, Acknowledgements, Appendix, Oath, and Zusammenfassung .tex files. 
    All chapters are put in the main.tex by this or a similar command:
        % \chapter{Related Work}
        % \input{Chapters/Related Work}
    You can edit the text of any chapter in the according .tex file. For now they are filled with the guideline instructions and some examples. In case you need more chapters just add them in a similar way by creating a new .tex file and an input of it.

titlepage.tex creates the title page. Make sure to replace all placeholders with the according information.

Declaration on oath also needs some placeholders filled out. 

In the introduction.tex you can see how to create a referred figure, how to cite sources and how to use acronyms.
    Figures should be uploaded in the Images folder.
    Sources are added to the reference.bib by adding the Bibtex information (Google Scholar, ACM Dig Lib).
    Acronyms are defined in the beginning of main.tex file. They are sorted by alphabet automatically. 

In related work.tex you can see how to create and refer to a table.

List of Figures and List of Tables and List of Abbreviations are automatically update with any referred elemtent of each type.

For editing the header and footer see lines 7-13 in the main.tex file and tutorials (Related Work p.13 and 14 for illustration). Also fill out placeholders. Simple layout explained in line 14 main.tex
