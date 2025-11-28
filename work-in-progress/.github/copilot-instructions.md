# Copilot Agent Instructions: Markdown Code Reviews

## Purpose
These instructions guide AI agents performing code reviews on Markdown (`.md`) files in this repository. The focus is on ensuring high-quality, well-structured, and error-free documentation.

## Review Checklist

### 1. Spelling and Grammar
- Perform a comprehensive spellcheck on all text.
- Correct all spelling errors, including technical terms (verify against context).
- Check for and correct grammar issues, including:
  - Subject-verb agreement
  - Sentence fragments or run-ons
  - Punctuation and capitalization
  - Consistent tense and voice
- Avoid over-correcting intentional stylistic choices or domain-specific language.

### 2. Markdown Structure and Syntax
- Validate that all Markdown syntax is correct:
  - Headings use `#`, `##`, etc. in proper order (no skipped levels)
  - Lists use `-`, `*`, or `1.` consistently
  - Code blocks are fenced with triple backticks (```) and language tags if needed
  - Links and images use correct `[text](url)` or `![alt](url)` syntax
  - Blockquotes use `>`
  - Tables are properly formatted
- Ensure there are no unclosed tags, broken links, or malformed tables.
- Check for consistent indentation and spacing.

### 3. General Content Quality
- Ensure headings are descriptive and reflect the content.
- Paragraphs should be concise and logically organized.
- Remove duplicate or redundant sections.
- Ensure all referenced files or images exist in the repository.

## Example Review Comments
- "Corrected spelling of 'intialization' to 'initialization'."
- "Changed heading from '##Usage' to '## Usage' for consistency."
- "Fixed broken link: [API Docs](api.md) did not exist."
- "Added missing closing backticks for code block."

## Key Files
- All `.md` files in the repository, especially documentation and guides.

---

For more details on Markdown best practices, see: https://www.markdownguide.org/basic-syntax/
