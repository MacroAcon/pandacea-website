# Pandacea Recruitment Website

A clean, minimalist recruitment website designed to attract a Technical Co-Founder and Community/Governance Architect for the Pandacea Protocol project.

## Overview

This website presents Pandacea as a well-researched, credible, and inspiring mission. The design follows a blueprint aesthetic with clean lines, excellent typography, and a focus on content over flashy visuals. The tone is personal, direct, honest, and mission-driven—like a proposal from a founder rather than a marketing page.

## Website Structure

### Main Pages

1. **`index.html`** - Primary homepage with the complete narrative
2. **`research.html`** - Central library of all research documents
3. **`journal.html`** - Founder's journal documenting the project journey

### Supporting Files

- **`styles.css`** - Complete styling with responsive design
- **`script.js`** - Interactive functionality (smooth scrolling, animations)
- **`README.md`** - This documentation file

## Customization Guide

### Personal Information

Before deploying, update the following personal information throughout the website:

#### In `index.html`:
- Replace `[Your Name]` with your actual name (currently set to "Ace C.")
- Replace `[Your Background]` with your professional background (currently set to "data-analytics-driven founder & privacy-tech strategist (self-taught, early-career)")
  - Update contact information in the "Let's Connect" section:
    - Email address (currently set to pandaceaproject@gmail.com)
    - LinkedIn profile URL (currently set to https://www.linkedin.com/in/ace-conan-81362195/)
    - Secure chat handle and Discord username (currently commented out)

#### In `journal.html`:
- Update the journal entries to reflect your actual journey and insights
- Add your own entries to show current momentum and progress

### Content Customization

#### Hero Section
The opening message can be personalized while maintaining the direct, honest tone:

```html
<h1 class="hero-title">I have a blueprint to fix the broken data economy. But I can't build it alone.</h1>
<p class="hero-subtitle">
    My name is Ace C., and I've spent months researching a new protocol called Pandacea—a system designed to give people ownership of their data. The vision is clear, the research is done, but the project is still just an idea.
</p>
```

#### Role Descriptions
The recruitment cards can be customized to better match your specific needs:

- **Technical Co-Founder**: Adjust the technical requirements and responsibilities
- **Community & Governance Architect**: Modify the community building and governance focus areas

#### Research Documents
The research page automatically links to all documents in the `pandacea v2.7/` folder. Ensure all PDF and Markdown files are properly linked.

### Design Customization

#### Colors
The current color scheme uses:
- Primary: `#1a1a1a` (dark gray/black)
- Secondary: `#666` (medium gray)
- Background: `#ffffff` (white) and `#f8f9fa` (light gray)
- Accents: Various shades for problem/solution sections

#### Typography
The website uses Inter font family for a clean, modern look. You can change this by updating the Google Fonts link in the HTML files.

#### Layout
The design is responsive and works on all device sizes. The grid layouts automatically adjust for mobile devices.

## Deployment

### Local Development
1. Simply open `index.html` in a web browser to view locally
2. All files are static HTML/CSS/JS, so no server setup is required

### Web Hosting
The website can be deployed to any static hosting service:

- **GitHub Pages**: Push to a GitHub repository and enable Pages
- **Netlify**: Drag and drop the folder to deploy
- **Vercel**: Connect your repository for automatic deployments
- **AWS S3**: Upload files to an S3 bucket with static website hosting
- **Traditional hosting**: Upload files to any web server

### Custom Domain
After deployment, you can configure a custom domain through your hosting provider.

## File Organization

```
/
├── index.html              # Main homepage
├── research.html           # Research documents library
├── journal.html            # Founder's journal
├── styles.css              # All styling
├── script.js               # Interactive functionality
├── README.md               # This documentation
└── pandacea v2.7/          # Research documents folder
    ├── *.pdf               # PDF versions of documents
    └── *.md                # Markdown versions of documents
```

## Key Features

### Design Principles
- **Minimalist**: Clean, uncluttered design focused on content
- **Blueprint aesthetic**: Inspired by architectural drawings and founder whiteboarding
- **Responsive**: Works perfectly on all devices
- **Accessible**: Proper semantic HTML and focus states

### User Experience
- **Smooth scrolling**: Navigation links smoothly scroll to sections
- **Fade-in animations**: Sections animate in as users scroll
- **Hover effects**: Subtle interactions on cards and buttons
- **Clear hierarchy**: Easy to scan and understand the content flow

### Content Strategy
- **Evidence-based**: All claims backed by research
- **Transparent**: Full access to all research documents
- **Personal**: Direct communication from founder to potential partners
- **Action-oriented**: Clear calls to action and contact methods

## Maintenance

### Adding New Journal Entries
To add new entries to the Founder's Journal:

1. Open `journal.html`
2. Add a new `<div class="journal-entry">` at the top of the entries list
3. Follow the existing format with date, title, content, and tags
4. Keep entries focused and authentic to show ongoing progress

### Updating Research Documents
When you have new research documents:

1. Add the files to the `pandacea v2.7/` folder
2. Update the research page in `research.html` to include the new documents
3. Ensure both PDF and Markdown versions are available

### Contact Information Updates
Remember to update contact information whenever it changes, particularly:
- Email addresses
- Social media handles
- Professional profile links

## Technical Notes

- **No dependencies**: Pure HTML, CSS, and JavaScript
- **No build process**: Ready to deploy immediately
- **SEO-friendly**: Proper meta tags and semantic structure
- **Fast loading**: Optimized for performance
- **Cross-browser compatible**: Works in all modern browsers

## Support

This website is designed to be self-contained and easy to maintain. The code is well-commented and follows standard web development practices. If you need help with customization or deployment, the structure is simple enough that any web developer can assist.

---

**Note**: This website is designed specifically for recruiting founding partners for the Pandacea Protocol. The content and messaging are tailored to attract technical and community-building talent who share the vision of a more equitable data economy. 