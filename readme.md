# PDF2TXT

A b4j program which converts PDF files to text files.

If the pdf's text can be extracted, then use the pdf2txt_noocr, which uses pdfbox to extract text.

If the pdf is just images, then use the pdf2txt, which uses tesseract to do the OCR job first.