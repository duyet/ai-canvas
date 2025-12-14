# AI Canvas

This project hosts static HTML content pages rendered by AI.

## Overview

AI Canvas is a collection of AI-generated HTML pages served as static content via GitHub Pages at:

**https://duyet.github.io/ai-canvas/**

## How It Works

1. AI generates HTML content pages on various topics
2. HTML files are committed to this repository
3. GitHub Actions automatically updates the README.md to list and index all HTML files
4. Content is served via GitHub Pages for easy access

## Structure

- `*.html` - AI-generated static HTML pages
- `README.md` - Auto-generated index of all HTML content (updated by GitHub Actions)
- `.github/workflows/` - Automation workflows

## Contributing

To add new content:
1. Generate HTML content using AI
2. Commit the `.html` file to this repository
3. GitHub Actions will automatically update README.md with the new entry

## Automation

The repository uses GitHub Actions to automatically:
- Detect new or updated `.html` files
- Update `README.md` with a listing of all available pages
- Include direct links to view each page on GitHub Pages
