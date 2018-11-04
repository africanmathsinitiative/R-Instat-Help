## Folder to store files related to the [R-Instat wiki](https://github.com/africanmathsinitiative/R-Instat/wiki)

### How to create PDF versions of help pages on R-Instat wiki

1. Go to the wiki page you want to covert and click **Edit**

2. Copy the text and place in a plain text file.

3. Add the title at the top of the text file since this is not in the text copied. e.g.

```
# Introductory Tutorial: Part 1 Describing Data
```

4. Save the text file with a **.md** extension. The file name should be the same as the title.

5. Upload the .md file here https://www.markdowntopdf.com/. 
If the PDF file does not appear after a minute then the .md file may have unsupported characters in it. If this happens you will not get any error message to explain this. You need to find the unsupported characters in the .md file. Common examples of unsupported characters are when text is copied from Word with formatting. E.g. curley quotation makes instead of standard ones (").
Paths to images also need to be specified in the correct format. This is the correct format:
```
https://raw.githubusercontent.com/africanmathsinitiative/R-Instat-Help/master/wiki/Introductory-Tutorial/Import%20Excel%20Dodoma%20file.png
```
