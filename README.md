I was having issues with the book not rendering properly when using `quarto publish gh-pages`, so I resorted to using [this approach](https://quarto.org/docs/publishing/github-pages.html#render-to-docs).

Next time you add material that you'd like to publish do the following:

```bash
# render stuff locally
quarto render

git status
# add add'l changes if needed
# then push changes to GitHub
git push
```
