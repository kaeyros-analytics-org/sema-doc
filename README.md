# Multilingual bs4_book

[![Project Status: Concept – Minimal or no implementation has been done yet, or the repository is only intended to be a limited example, demo, or proof-of-concept.](https://www.repostatus.org/badges/latest/concept.svg)](https://www.repostatus.org/#concept)


* Chapters are in two folders by language.
* The content of index.Rmd is in each language folder, without any frontmatter, as index.Rmd.pre.
* The mapping between English and French filenames is in dic.yaml.
* The script `make-books.R` builds the books, copy their content to the docs folder, then perform xml2 surgery to get the mapping between Rmd and HTML filenames, and to add a link to each HTML to the HTML in the other language.

This is a prototype.
For instance it'd be good to have more generic code, with not only two languages.
