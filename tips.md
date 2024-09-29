## Some tips for updating the website

### Changing the size of figures 
Modifying x in `<div class="col col-sm-x abbr">` in [_layouts/bib.liquid](_layouts/bib.liquid). 

### Adding/deleting publications
Modify [_bibliography/papers.bib](_bibliography/papers.bib).
For videos, place it under [assets/img/publication_preview](assets/img/publication_preview) and specify file name as ``

### Adding notes to a publication
Add a key `note={...}` to the bib entry in [_bibliography/papers.bib](_bibliography/papers.bib). 

### Adding preview to a publication
Add images/gifs to [_assets/img/publication_preview](_assets/img/publication_preview) and a key `preview={...}` to the bib entry. 

### Adding news
Create a new file in [_news](_news)

### Changing intro
Updating file [_pages/about.md](_pages/about.md). 
