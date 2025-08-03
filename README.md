# Stride Support Lab Articles

This repository contains the official support articles and documentation for Stride Labs, the core team behind Stride - a Cosmos-SDK blockchain that enables liquid staking of ATOM and other Cosmos assets.

## Current Articles

### Getting Started
- **liquid-staking-guide.md** - Complete beginner's guide to liquid staking with Stride
- **wallet-setup.md** - Setting up and connecting wallets (Keplr, Leap, Cosmostation)
- **governance-guide.md** - Participating in governance with liquid staking tokens
- **security-guide.md** - Security best practices for Stride users
- **troubleshooting-guide.md** - Solutions to common issues and problems

### Advanced Guides
- **defi-integration-guide.md** - Using Stride LSTs in DeFi protocols
- **general-faq.md** - Frequently asked questions about Stride

## Article Formatting Guidelines

All articles in this repository follow a standardized format to ensure consistency and readability. When creating or editing articles, please follow these guidelines:

### 1. File Structure

**Filename Format:**
- Use lowercase with hyphens: `liquid-staking-guide.md`
- Be descriptive and clear
- Include the word "guide" for instructional content

**File Location:**
- All articles go in the `/articles/` directory
- No subdirectories unless specifically needed

### 2. Frontmatter (YAML)

Every article must start with YAML frontmatter containing these fields:

```yaml
---
title: "Article Title - Descriptive Subtitle"
description: "SEO-friendly meta description explaining what the article covers"
category: "Getting Started" | "Integrations" | "Liquid Staking" | "Advanced"
readTime: "15 min read"
featured: "yes" | "no"
tags: ["tag1", "tag2", "tag3", "etc"]
nextArticles: ["wallet-setup", "defi-integration-guide"] # optional
date: "2024-01-15" # optional
---
```

**Field Guidelines:**
- **title**: Clear, descriptive title with subtitle if needed
- **description**: 150-160 character SEO description
- **category**: One of the predefined categories
- **readTime**: Estimated reading time based on content length
- **featured**: "yes" for important/popular articles
- **tags**: 5-10 relevant keywords, use kebab-case for multi-word tags
- **nextArticles**: Optional array of related article filenames (without .md)
- **date**: Optional publication date in YYYY-MM-DD format

### 3. Content Structure

**Required Elements:**
1. **Title (H1)**: Same as frontmatter title
2. **Table of Contents**: Numbered list with anchor links
3. **Horizontal divider**: `---` after ToC
4. **Main content sections**
5. **Horizontal dividers**: Between major sections
6. **Footer section**: Last updated date and disclaimers

**Example Structure:**
```markdown
# Article Title

## Table of Contents
1. [Section One](#section-one)
2. [Section Two](#section-two)
3. [Getting Help](#getting-help)

---

## Section One

Content here...

---

## Section Two

Content here...

---

## Getting Help

Contact information...

---

*Last updated: Month Year*
*Disclaimer text here.*
```

### 4. Heading Hierarchy

- **H1 (#)**: Article title only (once per article)
- **H2 (##)**: Major sections
- **H3 (###)**: Subsections within major sections
- **H4 (####)**: Sub-subsections (use sparingly)

**Section Dividers:**
- Use `---` horizontal rules between all major H2 sections
- This creates clear visual separation

### 5. Content Formatting

**Text Formatting:**
- **Bold**: For important terms, UI elements, warnings
- *Italic*: For emphasis, technical terms
- `Code`: For commands, code snippets, file names
- Use bullet points for lists
- Use numbered lists for step-by-step procedures

**Links:**
- Format: `[Link Text](https://example.com)`
- Use descriptive link text, not "click here"
- Prefer HTTPS links
- For Stride official links: `[app.stride.zone](https://app.stride.zone)`

**Code Blocks:**
```bash
# Commands or code examples
stride tx staking delegate
```

**Tables:**
```markdown
| Column 1 | Column 2 | Column 3 |
|----------|----------|----------|
| Data     | Data     | Data     |
```

**Callouts and Warnings:**
```markdown
**Important:** Critical information here

**Note:** Additional context here

**Warning:** Caution about risks
```

### 6. Step-by-Step Instructions

Format procedures as numbered lists with clear action items:

```markdown
1. **Action verb**: Specific instruction
   - Additional context or sub-steps
   - Screenshots or examples if helpful

2. **Next action**: Continue the process
   - More context
   - Expected results
```

### 7. Standard Sections

**Include these sections where applicable:**

**Table of Contents:**
- Always include for articles >500 words
- Use numbered lists with anchor links
- Keep to 10 items or fewer

**Getting Help Section:**
```markdown
## Getting Help

**Official Support:**
- **Discord**: [discord.gg/stride](https://discord.gg/stride)
- **Documentation**: [docs.stride.zone](https://docs.stride.zone)
- **Twitter**: [@stride_zone](https://twitter.com/stride_zone)

**Community Resources:**
- List community resources here
```

**Footer:**
```markdown
---

*Last updated: Month Year*

*This guide is for educational purposes. Always do your own research and understand the risks before using any protocol.*
```

### 8. Writing Style

**Tone:**
- Friendly but professional
- Clear and accessible to beginners
- Authoritative without being condescending

**Language:**
- Use active voice
- Write in second person ("you" not "one")
- Define technical terms when first used
- Use consistent terminology throughout

**Content Guidelines:**
- Start with basics, build to advanced concepts
- Include context and "why" not just "how"
- Provide multiple approaches when applicable
- Address common questions and concerns
- Include realistic examples and scenarios

### 9. SEO and Discoverability

**Keywords:**
- Include relevant keywords naturally in content
- Use keywords in headings and subheadings
- Include synonyms and related terms

**Meta Information:**
- Write compelling meta descriptions
- Use descriptive, keyword-rich titles
- Include relevant tags in frontmatter

### 10. Content Maintenance

**Updates:**
- Update "Last updated" date when making changes
- Review articles quarterly for accuracy
- Update screenshots and links as needed
- Revise outdated information promptly

**Version Control:**
- Use clear commit messages when updating
- Note major changes in commit descriptions
- Consider creating new articles for major feature updates

## Quality Checklist

Before publishing, ensure:
- [ ] Frontmatter is complete and accurate
- [ ] Table of contents matches actual sections
- [ ] All links work and go to correct destinations
- [ ] Code examples are tested and functional
- [ ] Screenshots are current and clear
- [ ] Grammar and spelling are correct
- [ ] Content follows the style guide
- [ ] Footer information is updated