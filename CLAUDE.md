# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static website for Long Course Consulting, a boutique consultancy for early-stage startups. The site is built with pure HTML, CSS, and Bootstrap 5.

## Architecture

- **Static Website**: No build process or server-side rendering
- **Bootstrap 5**: Uses CDN-hosted Bootstrap for responsive layout and components
- **Single Page Application**: All content is in `index.html` with anchor-based navigation
- **Media Assets**: Images stored in `media/` directory (uses .jp2 format for photos)

## File Structure

- `index.html` - Main website file containing all sections (header, services, about)
- `index.css` - Custom CSS with header background styling and backdrop blur effects
- `media/` - Contains header background image and profile photo

## Key Styling Patterns

- **Header Section**: Uses full-screen background image with blurred overlay for text readability
- **Bootstrap Components**: Leverages Bootstrap's card system for service listings
- **Custom CSS Classes**: 
  - `.lcc-header` - Header background image styling
  - `.blurred` - Backdrop filter blur effect with semi-transparent white background

## Development Notes

- No build process required - files can be served directly by any web server
- Bootstrap is loaded from CDN, no local dependencies
- Contact links use `mailto:adam@longcourse.consulting` throughout
- Responsive design handled by Bootstrap's grid system

## Commit Style

Use Conventional Commit style for all commits and PR titles (e.g. `feat:`, `fix:`, `chore:`, `docs:`, `refactor:`, etc.).
