# Overview

This is a Jekyll static site generator project using the Mundana theme. It's a blog/content management system that generates static HTML websites from Markdown content. The site includes blog posts, author profiles, category/tag organization, and standard pages like contact and about sections. The theme features a modern, responsive design with Bootstrap styling and includes functionality for comments, search, and content categorization.

# User Preferences

Preferred communication style: Simple, everyday language.

# System Architecture

## Static Site Generation
The project uses Jekyll, a Ruby-based static site generator that converts Markdown files into HTML pages. The build process transforms content files in `_posts/` and `_pages/` directories into a complete website in the `_site/` directory. This approach provides fast loading times, security benefits, and easy deployment to static hosting platforms.

## Content Management
Content is organized through Jekyll's file-based system:
- Blog posts are stored in `_posts/` with YAML front matter for metadata
- Static pages are in `_pages/` directory
- Authors are defined in site configuration with profile information
- Categories and tags provide content organization and filtering

## Template System
The site uses Liquid templating with Jekyll layouts:
- `_layouts/default.html` provides the base template structure
- `_layouts/post.html` handles individual blog post display
- `_layouts/page.html` and `_layouts/page-sidebar.html` manage static pages
- `_includes/` directory contains reusable template components

## Responsive Frontend
The frontend is built with Bootstrap framework for responsive design, custom CSS themes, and Font Awesome icons. jQuery is included for interactive functionality, and Google Fonts provide typography styling.

## Content Features
- Author profiles with social media links and biographical information
- Featured posts system using tags
- Category and tag-based content organization
- Reading time estimation for posts
- Social sharing functionality
- Search functionality using Lunr.js client-side search

## Form Handling
Contact forms are configured to use Formspree for form submission handling, providing a serverless solution for contact functionality.

# External Dependencies

## Core Technologies
- **Jekyll**: Static site generator for content management and site building
- **Ruby/RubyGems**: Runtime environment and package management for Jekyll
- **Bundler**: Dependency management for Ruby gems

## Frontend Libraries
- **Bootstrap**: CSS framework for responsive design and UI components
- **jQuery**: JavaScript library for DOM manipulation and interactive features
- **Font Awesome**: Icon library for social media and UI icons
- **Google Fonts**: Web fonts service for typography (Lora font family)
- **Lunr.js**: Client-side search engine for content searching

## Third-Party Services
- **Formspree**: Form submission handling service for contact forms
- **Disqus**: Comment system integration for blog post discussions
- **GitHub Pages**: Potential hosting platform (Jekyll native support)

## SEO and Analytics
- **Jekyll SEO Tag**: Plugin for generating SEO-friendly meta tags
- **Google Analytics**: Analytics tracking capability (placeholder implementation)

## Development Tools
- **Liquid**: Templating language used by Jekyll for dynamic content generation
- **YAML**: Front matter format for content metadata
- **Markdown**: Content authoring format for posts and pages