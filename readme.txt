This is a template for thesis works, and this file is a guide how to use it. This template follows the regulations of the Appendix 1 of Code of Studies and Exams. Here is a quick summary of the requirements declared by that appendix:
 - The bachelor thesis work must be at least 30 pages long and must contain of at least 50 000 non-white-space characters, excluding the title page, thesis proposal form, acknowledgements, table of contents, bibliography, and appendices. The master thesis must be 40 pages long and must contain at least 65 000 non-white-space characters (excluding the same pages). The maximal length of the thesis is 120 pages.
 - Long code fragments, wiring diagrams, tables of measurement data, etc. can only be attached as an appendix. All source code should be open access (should be uploaded to a server available to public), including the project and configuration files needed, and the URL should be included in the text.
 - Literal quotes may be included only in particularly justified cases (theorems, definitions, etc.). With the exception of the theorems, the literal quotes or translation must be enclosed in quotation marks, with the source cited immediately after the quoted section.
 - Source of all figures and tables created by other than the author of the thesis must be indicated in the caption of the figure/table.
 - The list of used literature should be given in a uniform format, following the conventions of the field, at the end of the thesis. (E.g. IEEE, Nature format) All publications in the bibliography should be referenced in the appropriate location in the text.

What is LaTeX?
LaTeX (/ˈlɑːtɛx/ LAH-tekh or /ˈleɪtɛx/ LAY-tekh) is a document preparation system. When writing, the writer uses plain text as opposed to the formatted text found in "What You See Is What You Get" word processors like Microsoft Word, LibreOffice Writer and Apple Pages. The writer uses markup tagging conventions to define the general structure of a document (such as article, book, and letter), to stylise text throughout a document (such as bold and italics), and to add citations and cross-references. (https://en.wikipedia.org/wiki/LaTeX)

Why should you use LaTeX?
While it takes some (but definitely not much) time to familiarize yourself with the LaTeX commands, it becomes incredibly beneficial later when you want to concentrate only on the content of your document, and you can let LaTeX render it in a nice and professional-looking way! This template aims to ease your work by providing a framework which is set up to produce a document that follows the requirements of the university, and includes all the tools you might need to render your content correctly. You can use it not even touching the configurations in the contents.tex and style.tex files, however, you are encouraged to read the comments I left there to help understanding the commands used, and even change them to make the resulting PDF even more beautiful.

How to use this template?

1. Create a copy of this project: Register to this website, and then after logging in and clicking on the "Menu" button in the upper left corner of the page, you will find a button named "Copy project". After clicking on that link you should be able to edit your copy of this template.

2. First you need to specify your name, the title of your thesis, name of supervisors writing it into the proper locations in the contents.tex file.

THAT'S IT! YOU CAN USE THE TEMPLATE!

However, here are some further tips you might find useful:

3. The style.tex file contains formatting rules, and the contents.tex collects other sources and assembles the document. The "other sources" containing the actual content of your thesis are located in the "contents" folder. In this folder, I named each file to start with a number according to the location in the thesis. I prefer to name files this way because then the files are sorted in the same order as they appear in the thesis making it easier find things. However, if you don't like it, don't hesitate to change this naming convention.

4. Feel free to delete the z_example.py in the contents folder, and all images in the "images" folder as they are there only as examples (except the "ITK_logo.pdf" which you should definitely keep as it should appear on the title page). Also, if you don't want to add appendix to your thesis, you can also delete the contents/appendix.tex file. In general, you can freely delete, modify, rename files in the contents folder -- you just need to remember to change the content of "contents.tex" accordingly.

5. You can use \url{http://www.citethisforme.com/ieee} to generate bibliography file (references.bib) easily. On this website, under the "More" menu you can find the "Export" sub menu with the "Export as BibTeX" item, that allows you to generate and download the bib file. Another great software is zotero, that has a lot awesome features, but slightly more complex and you need to download and install it to your PC: \url{https://www.zotero.org/support/getting_stuff_into_your_library}.

6. I prefer using https://www.tablesgenerator.com/ website to generate tables as opposed to write it by hand (which I find particularly tedious).

7. You can find examples how to reference figures, tables, equations and cite papers correctly in contents/8-summary.txt file.

8. It is just a minor detail, but it's nice to pay attention to such details: If you use a dot after an abbreviation, LaTeX will assume that it is the end of the sentence, so it will render slightly more space after this dot as it normally does. Writing a backslash before the dot can prevent that: "...approx\. 8 grams of...". Additional thing worth to know: the ~ character will insert a non-breaking space. It can be useful between in the following context: "... as it is depicted on fig.~\ref{fig:rat}...". Here we definitely don't want a line break between "fig." and the number of the figure.

9 You should never write something like "... as you can see on the figure below..." because LaTeX might render it pages later, or even earlier in the text as you expect. Instead, you should reference the number of the figure (again, see contents/8-summary.tex for examples). However, you can give some commands to LaTeX where and how to render you image: "\begin{figure}[htbp]" where the "htbp" command specifies the following:
    h Insert into running text
    t It is allowed to place it at the top of a page
    b It is allowed to place it at the bottom of a page
    p It is allowed to place it on a separate page.

10. One of the most useful feature of Overleaf, that it renders your document when you press Ctrl+Enter. Another outstanding feature that you can share the document with your supervisor (the free version only lets you share the document by a link) and you can let him or her edit or document or add comments.

Finally, don't forget:
  - Supervisor’s Notice: Fill in all the details of the Supervisor’s Notice Data Sheet both side of the paper. Make sure that both your external or your internal supervisor has signed it properly. The Reviewer should be recommended by the internal supervisor. The Supervisor’s Notice can be downloaded from here: https://wiki.itk.ppke.hu/twiki/bin/view/TO/Diploma?sortcol=table;table=up#Supervisor%E2%80%99s%20Notice
  - Consultation Certificate: You should submit the Consultation Certificate until the last day of the exam period of the last semester. The Consultation Certificate can be downloaded from here: https://wiki.itk.ppke.hu/twiki/bin/view/TO/Diploma?sortcol=table;table=up;up=#Consultation%20Certificate
  - Bound copy of the Thesis (1 copy)*( it is not necessary to be a hard book cover!) written on the cover "Thesis", student's name and the year of the submission. *Please make sure that your supervisor had signed it!

Finally let me give thanks to MARCELL Márton on whose LaTeX template (https://bitbucket.org/marczellm/ppke-itk-thesis/) served as a starting poing creating this template, and I would like to thank BOTOS Csaba for letting me use his LaTeX template from where I "stole" many neat tricks.

HAKKEL Tamás
2020

Ps: In case of question or comment regarding this template, you are more than welcomed to contact me: hakkelt@gmail.com