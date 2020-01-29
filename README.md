# Description

Simple bashscript that finds pdfpages by keyword and merges the pages into one document

## Dependencies
pdftk, pdfgrep:
install on Ubuntu/Debian with sudo apt install pdfgrep pdftk

## What you need to know

I did not write this script myself, so I copied it from [Ask Ubuntu](https://askubuntu.com/questions/454934/how-can-i-extract-pages-containing-a-given-string-from-a-pdf-file) and pasted it here.

## Example

```
./extract_pdf_results.sh Lagrange ./test.pdf
Processing ./test.pdf...
Looking for Lagrange...
Matching pages:3 
Extracting result pages...
Done.
```
