# Quarto Templates for Legal Filings

The `legal-filing` format is designed for legal filings and expert reports.
While still a work-in-progress, it is designed to be relatively customizable to different user's needs.

## Creating a New Article

To create a new article using this format:

```bash
quarto use template CoryMcCartan/legal
```

This will create a new directory with an example document that uses this format.

## Using with an Existing Document

To add this format to an existing document:

```bash
quarto add CoryMcCartan/legal
```

Then, add the format to your document options:

```yaml
format:
  legal-filing-pdf: default
```    

## Example and Options

Here is the source code for a minimal sample document: [template.qmd](template.qmd).
This sample is relatively self-documenting and contains YAML for all the possible options that are specific to the template.

