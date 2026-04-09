# Personal Portfolio - Syed Nihaal Ahmed

Modern GitHub Pages portfolio website with a dark visual style, dynamic GitHub data integration, and a clean single-page layout.

## Live Site

[https://syed-nihaal.github.io/](https://syed-nihaal.github.io/)

## Overview

This portfolio showcases:

- Most active repositories
- Repository cards with About and Topics
- Extracted topic toolbox from GitHub
- A year-by-year learning journey timeline
- Contact links for collaboration and opportunities

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- GitHub Pages
- GitHub REST API

## Dynamic Data Notes

- Repository and topic sections are fetched from public GitHub API endpoints.
- Basic client-side caching is used to reduce API requests and avoid rate-limit issues.
- If live fetch fails, cached data is used when available.

## Project Structure

- `index.html`: Main single-page portfolio layout and client-side data logic
- `assets/css/style.css`: Styles, responsive layout, and component theming
- `assets/img/`: Image and background assets

## Local Preview

Open `index.html` in a browser, or use a lightweight static server for best behavior.
