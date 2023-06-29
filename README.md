# American Geophysical Union (AGU)

This Quarto format will help you create documents for the American Geophysical Union. To learn more about AGU publications, see [AGU's Publication Page]([https://www.acm.org/publications/authors/information-for-authors](https://www.agu.org/Publish-with-AGU/Publish/)). For more about Quarto and how to use format extensions, see <https://quarto.org/docs/journals/>.

## Creating a New Article

You can use this as a template to create an article for the American Geophysical Union. To do this, use the following command:

```quarto use template quarto-journals/agu```

This will install the extension and create an example qmd file and bibiography that you can use as a starting place for your article.


## Installation For Existing Document

You may also use this format with an existing Quarto project or document. From the quarto project or document directory, run the following command to install this format:

```quarto add quarto-journals/agu```

## Usage 

To use the format, you can use the format names `agu-pdf` and `agu-html`. For example:

```quarto render article.qmd --to agu-pdf```

or in your document yaml

```yaml
format:
  pdf: default
  agu-pdf:
    keep-tex: true    
```

You can view a preview of the rendered template at <https://quarto-journals.github.io/agu/>. 

