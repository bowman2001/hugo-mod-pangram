---
title: Hugo module for placeholder text with pangram sentences
---

The module provides a **shortcode** for Markdown content processed by Hugo.

## SYNTAX

The shortcode `pangram` generates pure text and we need to call it as a Markdown shortcode with `%` as delimiter. The unnamed parameter is a decimal value and specifies the number of sentences:

```md
{{‍% pangram 3 %}}
```

### Example

{{% pangram 3 %}}
{.placeholder}

{{% pangram 5 %}}
{.placeholder}

## List of all available pangrams

{{% pangram-list %}}
