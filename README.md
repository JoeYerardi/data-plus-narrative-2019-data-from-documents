# Data + Narrative 2019 Liberating Data from Documents: Free and Reliable Methods
This repo contains information used in an introductory class on extracting data from PDFs taught at the [Boston University Data + Narrative workshop](https://combeyond.bu.edu/workshop/data-narrative/) on 6/4/19.

Our objective was to convert two files from PDFs into machine-readable data using Tabula, import that data into Excel, clean and analyze it.

[The advanced level of this class can be found here](https://github.com/JoeYerardi/data-plus-narrative-2019-advanced-data-from-documents).

## [Sublime Text](https://www.sublimetext.com/)
Sublime Text is a good text editor that'll help you understand what your raw, converted text file looks like before importing it into Excel.

## [Tabula](http://tabula.technology/)
Tabula is a browser-based tool for extracting tables within PDFs and converting them to other file formats.

## Other tools

### [Cometdocs](https://www.cometdocs.com/)
CometDocs is a web-based service for converting between many different file formats.

### [Excalibur](https://www.tryexcalibur.com/)
Similar to Tabula, Excalibur is a browser-based tool for extracting tables within PDFs and converting them to other file formats.

### [Xpdf](http://www.foolabs.com/xpdf/)
Xpdf is a command line-based tool for converting PDFs to text files.

### Handling misaligned columns in Excel
1. Find-and-replace
2. Text to columns
3. Delete and shift cells left and right

### Two tips and a warning for checking the integrity of your newly-converted data
1. Does your original PDF file contain a row with the sum of each column? Sum your converted data for each column to make sure it matches the figures in that row.
2. Use column sorting liberally. It'll help you quickly get rid of blank rows and other artifacts that tend to accompany data converted from PDFs.
3. Beware errant text (e.g. page numbers, header rows that repeat on every page, rows of summary data) in the PDF. That stuff can easily sneak into your data columns and seriously trip up your analysis.
