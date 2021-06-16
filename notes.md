---
# -- MAIN INFO -------------------------------------------
title: "Notes (Template)"
date: "2021-01-01"
author: [Ian Effendi]

# -- ADDITIONAL INFO -------------------------------------
subtitle: "The subtitle for this document."
description: |
    This is a description of the document.

    This can be as short as one sentence or as long as a few paragraphs.
lang: en-US
keywords: [Notes]

# -- LAYOUT ----------------------------------------------
documentclass: article
toc: True
geometry:
- a4paper
- portrait
- margin=1in
---

## Overview

This is a notetaking template that was written in Pandoc Markdown and can be converted into different formats (eg. PDF, LaTeX, etc.).

## Convert Markdown

If the appropriate tools are installed on your system, you can convert this document into a properly formatted HTML webpage, PDF, or LaTeX file.

Using pandoc, you can run commands like:

```bash
pandoc -s {FILENAME}.md -o {FILENAME}.pdf
```

Consider using pandoc filters for even more flexibility.

## Math Equations

This workflow also allows you to convert LaTeX syntax into math equations.

The following syntax:

```LaTeX
$$ a = mx + b $$
```

Generates:

$$ a = mx + b $$

Inline equations can be displayed using one set of `$` signs:

```LaTeX
$a = \frac{\sum_{i=1}^{a}c_i\mu_i}{\sum_{i=1}^{a}c_i\tau_i} = 1 \text{ when } \sum_{i=1}^{a}c_i = 0$
```

Generates:

$a = \frac{\sum_{i=1}^{a}c_i\mu_i}{\sum_{i=1}^{a}c_i\tau_i} = 1 \text{ when } \sum_{i=1}^{a}c_i = 0$.

Particularly complex statements can be displayed using the `\displaystyle` command:

```LaTeX
$\frac{\displaystyle \sum_{i=1}^{a}c_i\mu_i}{\displaystyle \sum_{i=1}^{a}c_i\tau_i} = 1 \text{ when } \sum_{i=1}^{a}c_i = 0$
```

$\frac{\displaystyle \sum_{i=1}^{a}c_i\mu_i}{\displaystyle \sum_{i=1}^{a}c_i\tau_i} = 1 \text{ when } \sum_{i=1}^{a}c_i = 0$
