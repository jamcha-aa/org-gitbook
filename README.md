# org-gitbook
build gitbook from org-mode (blueprint)

## Procedure
1. org-export *.org to *.md
2. run gitbook-builder (https://github.com/jamcha-aa/gitbook-builder)
3. rm *.md *except* README.md SUMMARY.md

## Known Issues
### Procedure 3. deletes all markdown files which includes user-written markdown files.
#### Solution (under planning)
Before exporting .md, creating .org lists then mapping .md during remove procedure.
### GitBook does not reflect org format.
This may be a problem of org-md-export.
