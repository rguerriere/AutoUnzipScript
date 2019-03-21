# AutoUnzipScript
A script created for my system administration course professor, Ahmad Esmaili @ Stony Brook University.

# Usage
This simple powershell script will unzip all .zip files in a given directory to another directory.
Includes support for the following formats.
```css
ZipFile>Folder>Files/Folders
ZipFile>Files/Folders
```

It will then forcibly remove any files/folders that do not have the extension:
*.html *.css

# Modifying for personal use
Lines 2, 3, 37 & 41 are paths for your source/destination files

Delete lines 37-42 if you do not need the second portion of the functionality, forcibly removing files/folders without the proper extension.

Modify line 38 to whatever extensions you wish to delete.
