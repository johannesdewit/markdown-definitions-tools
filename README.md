# Markdown Definitions Tools

This repository is to contain scripts to work with [definitions list](https://www.markdownguide.org/extended-syntax/#definition-lists)
within [Markdown](https://www.markdownguide.org/) files.

A definition list is a list of items that are formatted like so:
```markdown
Term
: Definition 1
: Definition 2
```

I mainly use these definitions in two occasions:
1. In order to make a list of unknown vocabulary and their translations.
2. In order to add a glossary at the end of a .md file to inform the reader.

Please note that these definitions are part of the 'extended' syntax of Markdown.
It is thus not part of the syntax defined by standards as [Commonmark](https://commonmark.org/)
and is thus not taken to be 'proper' markdown by all processors. I, however, do
find it a pretty neat and easy way to format a glossary, which is quite readable
and understandable without any styling or processors.


## Ideas and goals
- [ ] Write script that orders multiple definitions within a file alphabetically.
  - [ ] Make option for changing sort order.
- [ ] Write a script to clean up typo's within the definition format.

## order_definitions.py

A python script for ordering a definition list alphabetically.

#### Roadmap
- [ ] Write pseudocode
- [ ] Write test and get test data
- [ ] Write code
- [ ] Write documentation
- [ ] Implement option to change sort order

## cleanup_definitions.py
- [ ] Write pseudocode
- [ ] Write test and get test data
- [ ] Write code
- [ ] Write documentation
