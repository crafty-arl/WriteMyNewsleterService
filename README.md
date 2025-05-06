# /build Starter Newsletter Template

A clean, customizable newsletter template for developers, indie hackers, and content creators who want full ownership and control over their newsletter format.

## Overview

The /build Starter Newsletter Template provides a professional foundation for creating and sending developer-focused newsletters. Built with simplicity and customization in mind, this template helps you maintain a consistent, high-quality newsletter without the overhead of complex tools or platforms.

### Who's it for?

- Developers sharing their journey and insights
- Indie hackers documenting their product development
- Content creators focusing on tech and development topics
- Anyone who wants full control over their newsletter format

### Why use this template?

- **Ownership**: Full control over your content and format
- **Simplicity**: Clean, semantic HTML with inline CSS
- **Flexibility**: Easy to customize and extend
- **Professional**: Pre-formatted sections for consistent content structure
- **Fast**: Quick to edit and deploy

## What's Included

### Core Files
- `newsletter.html` - The main HTML template with inline CSS
- `newsletter.md` - Markdown version for easy editing
- `preview.html` - Local preview version

### Content Sections
1. **Header** - Newsletter title and issue number
2. **Devlog** - Your development journey and updates
3. **Tool Stack** - Current tools and technologies
4. **News Roundup** - Curated industry news
5. **Code Tip** - Quick programming tips and tricks
6. **Footer** - Social links and subscription info

### Folder Structure
```
starter-newsletter/
├── newsletter.html
├── newsletter.md
├── preview.html
└── assets/
    └── images/
```

## Quick Start Guide

### 1. Customizing Content

#### HTML Version
1. Open `newsletter.html` in your preferred text editor
2. Edit the content within each section
3. Preview using `preview.html`

#### Markdown Version
1. Open `newsletter.md` in your text editor
2. Edit the content using Markdown syntax
3. Convert to HTML using your preferred Markdown processor

### 2. Local Preview

#### Option 1: HTML Preview
1. Open `preview.html` in your browser
2. Make changes to `newsletter.html`
3. Refresh to see updates

#### Option 2: Markdown Preview
- Use VS Code with Markdown Preview extension
- Or use online Markdown editors like StackEdit

### 3. Sending Your Newsletter

The template is compatible with various email platforms:
- Substack
- Buttondown
- ConvertKit
- Mailchimp
- Or any platform that accepts HTML newsletters

## Tips for Customization

### Editing Content Sections

#### Devlog Section
- Keep updates concise and focused
- Include links to relevant projects or resources
- Add screenshots or GIFs for visual interest

#### Tool Stack
- List current tools and technologies
- Include brief descriptions
- Add links to documentation or resources

### Styling Customization

#### Colors
Edit the CSS variables in the HTML file:
```css
:root {
  --primary-color: #your-color;
  --secondary-color: #your-color;
  --text-color: #your-color;
}
```

#### Fonts
Replace the Google Fonts link with your preferred fonts:
```html
<link href="https://fonts.googleapis.com/css2?family=Your+Font&display=swap" rel="stylesheet">
```

### Adding Your Branding
1. Replace the logo in the header
2. Update the footer signature
3. Customize the color scheme to match your brand

## License & Credits

### License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Credits
Created by /build, a content brand by Craft The Future

---

## Support & Contributing

Found a bug or have a suggestion? Open an issue or submit a pull request on our GitHub repository.

Want to share your newsletter? Tag us on Twitter [@craftthefuture](https://twitter.com/craftthefuture) with #buildNewsletter 