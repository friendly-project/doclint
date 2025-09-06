# English documentation standards

[Go back](../README.md)

## Introduction

This document goes over the standards for writing documentation in English. They'll help ensure that it's clear and consistent.

To make referring to rules easier, they follow this format:

- DOC-EN<rule_number>: \<description>

When removing a rule, the number will be reserved to prevent conflicts and moved to the [obsolete documentation standards](Obsolete/EN.md).

## Rules

### DOC-EN02: Use simple language

Use simple, straightforward language to make documentation more accessible.

- Use "help" instead of "assistance".
- "The system should have numerous pathways to accomplish the same task, without ambiguity" becomes "There should be multiple ways you can do the same task."

### DOC-EN03: Use generic terms

Use generic terms instead of specific product names to make documentation more dynamic.

- Use "password manager" instead of "Bitwarden"
- If referring to a product or service, use its name.

### DOC-EN04: Organize content with headings

Headings are used to structure content and make it easier to read.

- Use headings to break up content into sections.
- Use a levels for headings (for example, H1 or # for the main heading, H2 or ## for main sections, H3 or ### for subsections, etc.).

### DOC-EN05: Use sentence case

Sentence case is when the first letter of the first word is capitalized, and all other words are lowercase (except for [proper nouns](https://en.wikipedia.org/wiki/Proper_noun)).

- "THIS IS A HEADING" becomes "This is a heading"
- "This Is A Subheading" becomes "This is a subheading"

### DOC-EN06: Use American English

American English is the most widely used form of English worldwide. To make documentation accessible to the largest audience, it's used here.

- Use "color" instead of "colour"
- Use "organize" instead of "organise"

### DOC-EN07: Use the Oxford comma

The Oxford comma is the final comma in a list of 3 or more items, placed before "and" or "or".

- Use "apples, oranges, and bananas" instead of "apples, oranges and bananas"
- But "apples and bananas" is correct.

### DOC-EN08: Use contractions

Contractions are used to make text more conversational and easier to read. However, avoid contractions that have double sounds, or when it makes the text vague.

- Use "don't" instead of "do not"
- Use "it's" instead of "it is"
- Don't use "this's" or "there're".

### DOC-EN09: Use inclusive language

Inclusive language avoids terms that might be biased or insensitive. It aims to be respectful and considerate of all people.

- Use "firefighter" instead of "fireman"
- Use "police officer" instead of "policeman"
- Use "they" instead of "he" or "she" when gender is unknown or not needed.

### DOC-EN10: Use "might" instead of "may"

"May" can mean permission, while "might" is for when something is possible. To make things easier, don't use "may".

- "**You may** be able to complete the task" becomes "**You might** be able to complete the task".
- "**You may not** complete the task" becomes "**You're not** allowed to complete the task".

### DOC-EN13: Avoid Latin abbreviations

Use full words, different formatting or reword your sentence instead of using Latin abbreviations to make documentation clearer.

- Use "for example" instead of "e.g."
- Use a colon, comma or em-dash instead of "i.e."
- "There's many ways you can do this, **e.g.**:" becomes "There's many ways you can do this, **for example**:"

### DOC-EN14: Avoid double sounds in pairs of words

Avoid using pairs of words that create a double sound. They can be confusing or awkward when read out loud.

- Use "there's" instead of "there are"
- "You can **see each** file that is stored on the operating system." becomes "You can **see every** file that's stored on the operating system."

### DOC-EN15: Write instructions from a user's perspective

When writing instructions for a task that the user can do, use a user's perspective to make them more relatable and easier to follow.

- Use "you" instead of "the user."
- Use "your" instead of "the user's."
- Don't use "you can" when talking about a system's capabilities.

### DOC-EN16: Limit minor steps to 3

When providing minor steps or instructions, limit them to a maximum of 3. If more steps are needed, consider breaking them into separate major steps. Having more than 3 minor steps can make instructions harder to follow.

> 1. Step 1.1 > step 1.2 > step 1.3 > step 1.4 > step 1.5
> 2. Step 2.1 > step 2.2 > step 2.3

becomes

> 1. Step 1.1 > step 1.2 > step 1.3
> 2. Step 2.1 > step 2.2
> 3. Step 3.1 > step 3.2 > step 3.3

### DOC-EN17: Use written large numbers

When writing large numbers, such as 1,000,000 or 8,000,000,000, write them as words.

- "1,000,000" becomes "1 million"
- "8,000,000,000" becomes "8 billion"
- However, numbers meant to be specific, such as 1,234,567 should remain as digits to maintain accuracy.

## Recommendations

While these recommendations are not strict rules, following them can help improve the quality and consistency of documentation:

### Use Markdown

[Markdown](https://en.wikipedia.org/wiki/Markdown) is a lightweight markup language that makes it easy to create formatted text using a simple text editor.

We recommend using [markdownlint](https://github.com/DavidAnson/markdownlint), a tool created by David Anson to make your Markdown documentation consistent and easy to read.

When referring to markdownlint rules, use the format "MD<rule_number>". A full list of rules can be found in the [markdownlint documentation](https://github.com/DavidAnson/markdownlint/tree/main/doc).
