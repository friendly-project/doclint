# Obsolete documentation standards

[Go back](../README.md)

## Introduction

This document covers documentation standards that were removed from this project. They're preserved for historical reference.

## Rules

### DOC01: Use Markdown

*This rule was removed because it was Doclint was originally a set of rules for writing documentation specific to the friendly! project inside GitHub. Since then it's been separated into its own repository to act as a more general-purpose tool for documentation linting. Markdown usage has instead been moved to a new Recommendations section in the [Standards](../Standards.md) document.*

This project uses [Markdown](https://en.wikipedia.org/wiki/Markdown) to format documentation. Markdown is a lightweight markup language that makes it easy to create formatted text using a simple text editor.

It also uses [markdownlint](https://github.com/DavidAnson/markdownlint) by David Anson to make documentation consistent and easy to read.

When referring to markdownlint rules, use the format "MD<rule_number>". A full list of rules can be found in the [markdownlint documentation](https://github.com/DavidAnson/markdownlint/tree/main/doc).

### DOC11: Use folders as subpages

*This rule was removed because it was specific to the friendly! project. While it's still recommended as a best practice for organizing documentation, it's no longer enforced by Doclint.*

When organizing documentation, use folders to create subpages for related content. This helps keep the documentation structured and easy to navigate.

The main page should be titled `README.md`. This makes GitHub use it as the default landing page for the folder.

```text
Project
Project/Docs
Project/Docs/README.md
Project/Docs/Page1.md
Project/Docs/Page2.md
Project/Docs/Subfolder
Project/Docs/Subfolder/README.md
Project/Docs/Subfolder/Page1.md
Project/Docs/Subfolder/Page2.md
...
```

### DOC12: Include a back link

*This rule was removed because it was specific to the friendly! project. While it's still recommended as a best practice for organizing documentation, it's no longer enforced by Doclint.*

Always include a back link to the main documentation page at the top of each document, under the main heading.

There's a few ways you can do this:

- For the main README page of a folder:

  ```markdown
  [Go back](../README.md)
  ```

  - This navigates back to the parent folder.

- For other pages in the same folder:

  ```markdown
  [Go back](README.md)
  ```

  - This navigates back to the main page of the folder.
