# Netduma Knowledge Base

A static site generated with Hugo and Hextra.

## Requirements

* Hugo installed https://github.com/gohugoio/hugo/releases/tag/v0.135.0
* Go installed

## Development

### On Linux:

```bash
hugo server --logLevel debug --disableFastRender -p 1313
```

### On Windows:

```batch
rmdir /s public && hugo server --logLevel debug --disableFastRender -p 1313
```

## Publish

```bash
hugo --gc --minify
```

Will output to `public/` directory