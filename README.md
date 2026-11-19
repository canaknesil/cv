# Generate CV

Primary location of my CV.

CV is described in Emacs Org mode in `cv.org`.

Convert to HTML with `org-html-export-to-html`.
```sh
emacs --batch cv.org -f org-html-export-to-html && mv cv.html output/
```

