# UltraLocal Site

Simple Hugo site for UltraLocal podcast episodes.

## Quick Commands

### Development
```bash
# Start local development server
hugo server

# Start with drafts
hugo server -D
```

### Build & Deploy
```bash
# Build the site (generates public/ folder)
hugo

# Build with drafts
hugo -D
```

### Git Workflow
```bash
# Add changes
git add .

# Commit changes
git commit -m "Update content"

# Push to deploy
git push origin main
```

## Structure
- `content/episodes/` - Episode markdown files
- `layouts/` - HTML templates
- `static/` - Static assets (images, fonts, CSS)
- `public/` - Generated site (auto-created by Hugo)
