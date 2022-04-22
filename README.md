# Table-extractor-from-PDF
Table Extractor from PDF   
* Basic of PDF File Format 
* * Installing  required Python modules 
* * Extracting Table from PDF 
* * Introduction to Pandas Dataframe 
* * Writing Table into a CSV

Basic of PDF File Format

* The Portable Document Format (PDF) is a file format developed by Adobe
  in the 1990's to present documents that include text, graphics and images,
  independent of software, hardware and operating systems.
* PDF is based on the PostScript language, each PDF file encapsulated a 
  complete description of a fixed-layout flat document.
* The general structure of a PDF file is composed of the following components:
  Header, Body, Cross-Reference (xref) table, and Trailer.
* The header contains just one line that identifies the version of PDF.
  (Example: %PDF-1.5)   
* The body contains all the object information - Font, Images, Words, Bookmarks
  from Field and so on.
* The xref table contains pointer to all the objects included in the PDF file.
  It identifies how many objects are in the table, where the objects begins
  (the offset), and its length in bytes.
* The Trailer containspointers to the xref table and to key objects contained
  in the trailer dictionary. It ends with %%EOF to identify end of line.

Why Camelot?

* You are in control. Unlike other libraries and tools which either give a nice
  output or fail miserably (with no in-between), Camelot give you the power
  to tweak table extraction. (This is important since everything in the real
  word, including PDF table extraction, fuzzy.)
* Bad Tables can be discarded based on Metrics like accuracy and whitespace,
  without ever having to manually look at each table.
* Each table is a Pandas DataFrame, which seamlessly integrated into ETL and 
  Data Analysis Workflows.
* Export to multiples formats, including JSON, Excel and HTML.
