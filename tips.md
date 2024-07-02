## Some tips for updating the website

### Changing the size of figures 
Modifying x in the last line `col col-sm-x` here
```angular2html
<div class="row">
  {% if site.enable_publication_thumbnails %}
    <div class="col col-sm-4 abbr">
```
in [_layouts/bib.liquid](_layouts/bib.liquid). 

### Adding/deleting publications
Modify [_bibliography/papers.bib](_bibliography/papers.bib)

### Adding notes to a publication
Add a key `note={...}` to the bib entry in [_bibliography/papers.bib](_bibliography/papers.bib). 

### Adding news
Create a new file in [_news](_news)

### Changing intro
Updating file [_pages/about.md](_pages/about.md). 
