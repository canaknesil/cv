# Generate CV

Primary location of my CV.

CV is described in Emacs Org mode in `cv.org`.

Convert to HTML with `org-html-export-to-html`, and move to `output` folder, where the associated `.css` file is located.

Convert to PDF with `org-latex-export-to-pdf`, and move to `output` folder.



From the command line:

```sh
emacs --batch cv.org -f org-html-export-to-html && mv cv.html output/
emacs --batch cv.org -f org-latex-export-to-pdf && mv cv.pdf output/
```

The CV includes `photo.jpg`; place it in the repository root (for the PDF) and in `output/` (for the HTML).
