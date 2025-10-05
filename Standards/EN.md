# English documentation standards

[Go back](../README.md)

## Introduction

This document goes over the standards for writing documentation in English. They'll help ensure that it's clear and consistent.

To make referring to rules easier, they follow this format:

- DOC-EN<rule_number>: \<description>

When removing a rule, the number will be reserved to prevent conflicts and moved to the [obsolete documentation standards](Obsolete/EN.md).

## Rules

### DOC-EN02

**Use simple, straightforward language**.

- Use "help" instead of "assistance".
- "The system should have numerous pathways to accomplish the same task, without ambiguity" becomes "There should be multiple ways you can do the same task."

#### Why is DOC-EN02 a rule?

Using simple language can help in multiple ways: it can make translation easier, and non-English speakers typically learn simple words first rather than complex ones. Using simple language makes your documentation as widely accessible as possible.

#### When was DOC-EN02 submitted and added?

- **Issue:** No issue
- **Pull request:** https://github.com/friendly-project/docs/commit/d944b5ce5f6cf90b051f621f71ca70f65c4a9558

### DOC-EN03

**Use generic terms** instead of specific product names.

- Use "password manager" instead of "Bitwarden"
- If referring to a product or service, use its name.

#### Why is DOC-EN03 a rule?

Product names change a lot, dependencies get updated, and projects get shut down. By making your documentation generic when talking about products outside your control, it's best to be as generic as possible.

#### When was DOC-EN03 submitted and added?

- **Issue:** No issue
- **Pull request:** https://github.com/friendly-project/docs/commit/d944b5ce5f6cf90b051f621f71ca70f65c4a9558

### DOC-EN04

**Organize content with headings**

- Use headings to break up content into sections.
- Use a levels for headings (for example, H1 or # for the main heading, H2 or ## for main sections, H3 or ### for subsections, etc.).

#### Why is DOC-EN04 a rule?

Making sure your documentation is structured with headings makes it easier to link to specific sections, skim through to specific information the reader needs, and easier to understand when one sections ends and another starts.

#### When was DOC-EN04 submitted and added?

- **Issue:** No issue
- **Pull request:** https://github.com/friendly-project/docs/commit/d944b5ce5f6cf90b051f621f71ca70f65c4a9558

### DOC-EN05

**Use sentence case for headings and subheadings.** Sentence case is when the first letter of the first word is capitalized, and all other words are lowercase (except for [proper nouns](https://en.wikipedia.org/wiki/Proper_noun)).

- "THIS IS A HEADING" becomes "This is a heading"
- "This Is A Subheading" becomes "This is a subheading"

#### Why is DOC-EN05 a rule?

[Research](https://www.researchgate.net/publication/347481260_A_Comparative_Study_of_Dyslexia_Style_Guides_in_Improving_Readability_for_People_With_Dyslexia) has found that using mixing uppercase letters into a lowercase title (known as Title case) lead to confusion for people with dyslexia because they found it hard to differentiate lowercase and uppercase letters.

#### When was DOC-EN05 submitted and added?

- **Issue:** No issue
- **Pull request:** https://github.com/friendly-project/docs/commit/d944b5ce5f6cf90b051f621f71ca70f65c4a9558

### DOC-EN06

**Use American English** to make documentation accessible to the largest audience.

- Use "color" instead of "colour"
- Use "organize" instead of "organise"

#### Why is DOC-EN06 a rule?

American English is the most widely used form of English worldwide, and is typically the form of English learned by non-English speakers. Using this makes your documentation more approachable for the largest audience possible.

#### When was DOC-EN06 submitted and added?

- **Issue:** No issue
- **Pull request:** https://github.com/friendly-project/docs/commit/d944b5ce5f6cf90b051f621f71ca70f65c4a9558

### DOC-EN07

**Use the Oxford comma**, the final comma in a list of three or more items, placed before "and" or "or".

- Use "apples, oranges, and bananas" instead of "apples, oranges and bananas"
- But "apples and bananas" is correct.

#### Why is DOC-EN07 a rule?

The Oxford comma makes comma-separated lists much easier to read by making the separation of the final two items of a list less vague.

#### When was DOC-EN07 submitted and added?

- **Issue:** No issue
- **Pull request:** https://github.com/friendly-project/docs/commit/d944b5ce5f6cf90b051f621f71ca70f65c4a9558

### DOC-EN08

**Use contractions** to make text more conversational and easier to read. However, avoid contractions that have double sounds, or when it makes the text vague.

- Use "don't" instead of "do not"
- Use "it's" instead of "it is"
- Don't use "this's" or "there're".

#### Why is DOC-EN08 a rule?

The most readable documentation is typically the one that's easiest to say out loud. By writing in a conversational tone, it's easier for users to read through the steps in their heads.

#### When was DOC-EN08 submitted and added?

- **Issue:** No issue
- **Pull request:** https://github.com/friendly-project/docs/commit/d944b5ce5f6cf90b051f621f71ca70f65c4a9558

### DOC-EN09

**Use inclusive language**

- Use "firefighter" instead of "fireman"
- Use "police officer" instead of "policeman"
- Use "they" instead of "he" or "she" when gender is unknown or not needed.

#### Why is DOC-EN09 a rule?

Inclusive language helps to avoid terms that might be biased or insensitive. By using this, it can make documentation more approachable by all people.

#### When was DOC-EN09 submitted and added?

- **Issue:** No issue
- **Pull request:** https://github.com/friendly-project/docs/commit/d944b5ce5f6cf90b051f621f71ca70f65c4a9558

### DOC-EN10

**Avoid the word "may".** Use "might" for possibility, and use an alternative phrase for permission.

- "**You may** be able to complete the task" becomes "**You might** be able to complete the task".
- "**You may not** complete the task" becomes "**You're not** allowed to complete the task".

#### Why is DOC-EN10 a rule?

"May" can mean both permission and possibility, which can cause confusion.

#### When was DOC-EN10 submitted and added?

- **Issue:** No issue
- **Pull request:** https://github.com/friendly-project/docs/commit/d944b5ce5f6cf90b051f621f71ca70f65c4a9558

### DOC-EN13

**Avoid Latin abbreviations** like "e.g." and "i.e.". Use full words, different formatting or reword your sentence instead.

- Use "for example" instead of "e.g."
- Use a colon, comma or em-dash instead of "i.e."
- "There's many ways you can do this, **e.g.**:" becomes "There's many ways you can do this, **for example**:"

#### Why is DOC-EN13 a rule?

While Latin abbreviations might be common in your form of English or area, they're not universally known. To be as universal in your writing as possible, use alternatives.

#### When was DOC-EN13 submitted and added?

- **Issue:** No issue
- **Pull request:** https://github.com/friendly-project/docs/commit/cce376f0a70c7ff8931cb32741b281344caa07a9

### DOC-EN14

**Avoid double sounds** in pairs of words.

- Use "there's" instead of "there are"
- "You can **see each** file that is stored on the operating system." becomes "You can **see every** file that's stored on the operating system."

#### Why is DOC-EN14 a rule?

The most readable documentation is typically the one that's easiest to say out loud. By writing in a conversational tone and avoiding difficult pairs of words, it's easier for users to read through the steps in their heads.

#### When was DOC-EN14 submitted and added?

- **Issue:** No issue
- **Pull request:** https://github.com/friendly-project/docs/commit/cce376f0a70c7ff8931cb32741b281344caa07a9

### DOC-EN15

**Write instructions from a user's perspective** to make them more relatable and easier to follow.

- Use "you" instead of "the user."
- Use "your" instead of "the user's."
- Don't use "you can" when talking about a system's capabilities.

#### Why is DOC-EN15 a rule?

Technical documentation can often feel daunting to non-technical users. By writing from the user's perspective, readers can feel more empowered to complete the steps in front of them, rather than getting stuck and giving up.

#### When was DOC-EN15 submitted and added?

- **Issue:** No issue
- **Pull request:** https://github.com/friendly-project/docs/commit/cce376f0a70c7ff8931cb32741b281344caa07a9

### DOC-EN16

**Limit minor steps or instructions to a maximum of three.** If more steps are needed, consider breaking them into separate major steps.

> 1. Step 1.1 > step 1.2 > step 1.3 > step 1.4 > step 1.5
> 2. Step 2.1 > step 2.2 > step 2.3

becomes

> 1. Step 1.1 > step 1.2 > step 1.3
> 2. Step 2.1 > step 2.2
> 3. Step 3.1 > step 3.2 > step 3.3

#### Why is DOC-EN16 a rule?

Having more than three minor steps can make instructions harder to follow.

#### When was DOC-EN16 submitted and added?

- **Issue:** https://github.com/friendly-project/doclint/issues/5
- **Pull request:** https://github.com/friendly-project/doclint/pull/9

### DOC-EN17

**Use words for large numbers**, such as 1,000,000 or 8,000,000,000.

- "1,000,000" becomes "1 million"
- "8,000,000,000" becomes "8 billion"
- However, numbers meant to be specific, such as 1,234,567 should remain as digits to maintain accuracy.

#### Why is DOC-EN17 a rule?

Numbers above one million are harder to read as digits.

#### When was DOC-EN17 submitted and added?

- **Issue:** https://github.com/friendly-project/doclint/issues/7
- **Pull request:** https://github.com/friendly-project/doclint/pull/17

### DOC-EN18

**Use words instead of digits for numbers under 10.** For 10 and above, use digits.

- "1, 2, 3" is "one, two, three"
- "twelve, thirteen, fourteen" is "12, 13, 14"

#### Why is DOC-EN18 a rule?

Digits below 10 can be misread as letters, such as `1` and `I`.

#### When was DOC-EN18 submitted and added?

- **Issue:** https://github.com/friendly-project/doclint/issues/6
- **Pull request:** https://github.com/friendly-project/doclint/pull/18

### DOC-EN19

**Explain acronyms and abbreviations on first use.** However, don't do this for common terms used in everyday life.

- "POC" is "point-of-contact (POC)" on first use, then use "POC" after
- Common terms like Graphics Interchange Format (GIF) should just be GIF

#### Why is DOC-EN19 a rule?

While acronyms might be familiar and simple to you, they won't be to a first-time reader.

#### When was DOC-EN19 submitted and added?

- **Issue:** https://github.com/friendly-project/doclint/issues/23
- **Pull request:** https://github.com/friendly-project/doclint/pull/31

---

## Recommendations

While these recommendations are not strict rules, following them can help improve the quality and consistency of documentation:

### Use Markdown

[Markdown](https://en.wikipedia.org/wiki/Markdown) is a lightweight markup language that makes it easy to create formatted text using a simple text editor.

We recommend using [markdownlint](https://github.com/DavidAnson/markdownlint), a tool created by David Anson to make your Markdown documentation consistent and easy to read.

When referring to markdownlint rules, use the format "MD<rule_number>". A full list of rules can be found in the [markdownlint documentation](https://github.com/DavidAnson/markdownlint/tree/main/doc).
