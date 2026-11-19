# Generate CV

Primary location of my CV.

CV is described in Emacs Org mode in `cv.org`.

Convert Org to HTML with `org-html-export-to-html`.
```sh
emacs --batch cv.org -f org-html-export-to-html
```

Convert HTML to PDF with `weasyprint`.
```sh
weasyprint cv.html cv.pdf
```
