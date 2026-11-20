# CV

Primary location of my CV.

CV is described in Emacs Org mode in `cv.org`.

On pushing to `master`, the CV is automatically converted to HTML and PDF, released under [Latest CV](https://github.com/canaknesil/cv/releases/tag/latest), and published using Github Pages ([HTML](https://www.canaknesil.com/cv/cv.html), [PDF](https://www.canaknesil.com/cv/cv.pdf)).

To do the conversion manually, run the following commands.

Convert Org to HTML with `org-html-export-to-html`.
```sh
emacs --batch cv.org -f org-html-export-to-html
```

Convert HTML to PDF with `weasyprint`.
```sh
weasyprint cv.html cv.pdf
```

