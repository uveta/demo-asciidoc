# AsciiDoc documentation demo

## Introduction

Demo using AsciiDoc and Asciidoctor to build rich technical documentation. Includes:

- Setting up [Ruby](https://www.ruby-lang.org), [Asciidoctor](https://asciidoctor.org), [Graphviz](https://graphviz.org/) and [Pandoc](https://pandoc.org)
- Using [AsciiDoc](https://asciidoc.org) and [PlantUML](https://plantuml.com) to create technical documents
- Exporting documentation to HTML, PDF, Word, and Markdown format
- Upload Markdown files to GitHub Wiki

## Provisioning GitHub Wiki

Some manual steps, not covered by YAML pipeline, are required to provision and upload content to GitHub Wiki.

Before running pipeline:

- Make sure Wiki is enabled in your repository, by going to repository settings.

- Create a single page on repository Wiki. You do not need to add any content. This will trigger creation of Wiki Git repository, to which workflow will commit changes.
