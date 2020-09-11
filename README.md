# pandoc-utils
Hopefully I'll gather my pandoc setup here, to make it easy install my setup.

Install pandoc
```
sudo apt install pandoc
```

Clone repo:
```
git clone git@github.com:renzph/pandoc-utils.git
```

Add to .zshrc:
```
alias pandoc-bs="pandoc --filter=pandoc-citeproc --template $PREFIX/template.html --include-in-header $PREFIX/header.html --include-after-body $PREFIX/footer.html --mathjax --toc --toc-depth 2"
```
