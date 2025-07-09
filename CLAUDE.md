# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static website for **Solvi** - a mental health tool for private reflection and self-tracking. The site serves as a public landing page hosted on GitHub Pages.

## Architecture

This is a simple static website consisting of:
- `index.html` - Main landing page with header, logo, and intro section
- `styles.css` - CSS styling using system fonts and clean design
- `solvi-logo.png` - Main logo asset
- `favicons/` - Directory containing favicon assets in multiple sizes

## Development

### File Structure
- No build process required - this is a static HTML/CSS site
- All assets are committed directly to the repository
- No package.json or build dependencies

### Deployment
- Site is hosted on Cloudflare
- Cloudflare reads content from the main branch
- Changes are deployed automatically when pushed to the main branch
- Available at https://solvi.care

### Making Changes
- Edit `index.html` for content changes
- Edit `styles.css` for styling changes
- Replace `solvi-logo.png` for logo updates
- Update favicons in `favicons/` directory as needed

## Contact Information
- Email: hello@solvi.care
- Website: https://solvi.care