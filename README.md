# Contributing to the Privacy Guide

This guide is here to assist people in protecting their privacy and/or anonymity.
Please continue reading to contribute.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Directory Structure](#directory-structure)
- [Quick Start](#quick-start)
- [Content Creation](#content-creation)
- [Writing Guidelines](#writing-guidelines)
- [Pull Request Process](#pull-request-process)

## Prerequisites

- Git
- Hugo

## Directory Structure

```bash
docs/
├── topic/
│   ├── subsection/
│   └── another-subsection/
├── another-topic/
│   └── subsection/
```

## Quick Start

1. Fork the repository:
```bash
# On GitHub.com, click Fork button
```

2. Clone your fork:
```bash
git clone https://github.com/your-username/Guide-for-anonymity-and-privacy.git
cd Guide-for-anonymity-and-privacy/guide
```

3. Create branch:
```bash
git checkout -b feature/your-feature-name
```

4. Start local server:
```bash
hugo server -D
# Site runs at http://localhost:1313
```

## Content Creation

### Create New Pages

```bash
# Main sections
hugo new docs/section-name/_index.md

# Subsections
hugo new docs/section-name/subsection/_index.md

# Individual pages
hugo new docs/section-name/subsection/page-name.md
```

### Page Template

```markdown
---
title: "Page Title"
date: 2025-02-11
weight: 1
draft: true
---

## Overview
Brief introduction (2-3 sentences)

## Steps
1. First step
   - Detail
   - Example

2. Second step
   - Detail
   - Example

## Common Mistakes/Issues
- Mistake 1
- Mistake 2

## Tools & Resources
- [Tool Name](link): Description
- [Resource Name](link): Description

## References
1. [Source Name](url)
2. [Source Name](url)
```

## Writing Guidelines

### Element to Include

- Clear title
- Brief overview
- Step-by-step instructions
- Source citations
- Tools/resources section

### Content Rules

The Element Guidelines are written as a guide only, with room for flexibility.

Must not include:
- Illegal techniques
- Personal data
- Unverified claims unless explicitly stated to be speculatory or unverified
- Personal opinions.

## Pull Request Process

1. Update files:
```bash
git add .
git commit -m "Describe changes"
git push origin feature/your-feature-name
```

2. Create PR:
   - Go to GitHub
   - Click "Pull Request"
   - Fill template
   - Add change description

3. Review Process:
   - Wait for review
   - Address feedback
   - Update PR if needed

## License

MIT License - See LICENSE.md