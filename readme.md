# Split PDF and rename files using text within pages

Source (Windows version): [https://glenbambrick.com/2016/09/23/extract-rename-pdf-pages/](https://glenbambrick.com/2016/09/23/extract-rename-pdf-pages/)
My related post (in italian): [https://www.enappi.com/python/rinomina-pdf-in-base-al-contenuto/](https://www.enappi.com/python/rinomina-pdf-in-base-al-contenuto/)

## Note

- To get X chars before the search use:

```python
doc_ext = pdf_text[index.start() – X: index.start()]
```
