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
