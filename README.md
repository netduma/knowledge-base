# Netduma Knowledge Base

A static site generated with Hugo and Hextra.

## Requirements

* Hugo >=0.135.0

## Development

### Run makdownlint

Install markdownlint-cli2 globally (`npm --global markdownlint-cli2` or from your package manager)

```bash
markdownlint-cli2 "**/*.md" "*.md"
```

### On Linux

```bash
hugo server --logLevel debug --disableFastRender -p 1313
```

### On Windows

```batch
rmdir /s public && hugo server --logLevel debug --disableFastRender -p 1313
```

## Publish

```bash
hugo --gc --minify
```

Will output to `public/` directory
