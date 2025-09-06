# Documentation standards

[Go back](README.md)

## Introduction

This document goes over the standards for writing documentation in this project. They'll help ensure that it's clear and consistent.

To make referring to rules easier, they follow this format:

- DOC<rule_number>: \<description>

When removing a rule, the number will be reserved to prevent conflicts and moved to the [obsolete documentation standards](Obsolete/Standards.md).

## Rules

### DOC02: Use simple language

Use simple, straightforward language to make documentation more accessible.

- Use "help" instead of "assistance".
- "The system should have numerous pathways to accomplish the same task, without ambiguity" becomes "There should be multiple ways you can do the same task."

### DOC03: Use generic terms

Use generic terms instead of specific product names to make documentation more dynamic.

- Use "password manager" instead of "Bitwarden"
- If referring to a product or service, use its name.

### DOC04: Organize content with headings

Headings are used to structure content and make it easier to read.

- Use headings to break up content into sections.
- Use a levels for headings (for example, H1 or # for the main heading, H2 or ## for main sections, H3 or ### for subsections, etc.).

### DOC05: Use sentence case

Sentence case is when the first letter of the first word is capitalized, and all other words are lowercase (except for [proper nouns](https://en.wikipedia.org/wiki/Proper_noun)).

- "THIS IS A HEADING" becomes "This is a heading"
- "This Is A Subheading" becomes "This is a subheading"

### DOC06: Use American English

American English is the most widely used form of English worldwide. To make documentation accessible to the largest audience, it's used here.

- Use "color" instead of "colour"
- Use "organize" instead of "organise"

### DOC07: Use the Oxford comma

The Oxford comma is the final comma in a list of 3 or more items, placed before "and" or "or".

- Use "apples, oranges, and bananas" instead of "apples, oranges and bananas"
- But "apples and bananas" is correct.

### DOC08: Use contractions

Contractions are used to make text more conversational and easier to read. However, avoid contractions that have double sounds, or when it makes the text vague.

- Use "don't" instead of "do not"
- Use "it's" instead of "it is"
- Don't use "this's" or "there're".

### DOC09: Use inclusive language

Inclusive language avoids terms that might be biased or insensitive. It aims to be respectful and considerate of all people.

- Use "firefighter" instead of "fireman"
- Use "police officer" instead of "policeman"
- Use "they" instead of "he" or "she" when gender is unknown or not needed.

### DOC10: Use "might" instead of "may"

"May" can mean permission, while "might" is for when something is possible. To make things easier, don't use "may".

- "**You may** be able to complete the task" becomes "**You might** be able to complete the task".
- "**You may not** complete the task" becomes "**You're not** allowed to complete the task".

### DOC13: Avoid Latin abbreviations

Use full words, different formatting or reword your sentence instead of using Latin abbreviations to make documentation clearer.

- Use "for example" instead of "e.g."
- Use a colon, comma or em-dash instead of "i.e."
- "There's many ways you can do this, **e.g.**:" becomes "There's many ways you can do this, **for example**:"

### DOC14: Avoid double sounds in pairs of words

Avoid using pairs of words that create a double sound. They can be confusing or awkward when read out loud.

- Use "there's" instead of "there are"
- "You can **see each** file that is stored on the operating system." becomes "You can **see every** file that's stored on the operating system."

### DOC15: Write instructions from a user's perspective

When writing instructions for a task that the user can do, use a user's perspective to make them more relatable and easier to follow.

- Use "you" instead of "the user."
- Use "your" instead of "the user's."
- Don't use "you can" when talking about a system's capabilities.

## Recommendations

While these recommendations are not strict rules, following them can help improve the quality and consistency of documentation:

### Use Markdown

[Markdown](https://en.wikipedia.org/wiki/Markdown) is a lightweight markup language that makes it easy to create formatted text using a simple text editor.

We recommend using [markdownlint](https://github.com/DavidAnson/markdownlint), a tool created by David Anson to make your Markdown documentation consistent and easy to read.

When referring to markdownlint rules, use the format "MD<rule_number>". A full list of rules can be found in the [markdownlint documentation](https://github.com/DavidAnson/markdownlint/tree/main/doc).
