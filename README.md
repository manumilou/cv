# Generate HTML

```
$ resume export --theme=stackoverflow resume.html
```

# Generate PDF

```
$ cd /usr/lib/node_modules/resume-cli/node_modules/html-pdf
$ node bin/index.js %PATH_TO_HTML_FILE% /tmp/resume.pdf
```

NOTE: changement dans index.js pour ajouter les marges (L34)


# Thème: Stackoverflow

Emplacement du thème (après installation en global avec npm): `/usr/lib/node_modules/jsonresume-theme-stackoverflow`
