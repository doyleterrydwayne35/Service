Interpol Crime Trend Update Webpage

This repository contains a professional, responsive HTML webpage for an Interpol crime trend update on human trafficking-fueled scam centers. The page is designed as a single HTML file with embedded CSS and JavaScript for easy deployment.

## Features

- **Professional Interpol Design**: Official-looking styling with dark blue gradients and police aesthetic
- **Responsive Layout**: Works on mobile, tablet, and desktop devices
- **Key Information Sections**:
  - Urgent alert banner with warning icon
  - Global threat overview
  - Criminal modus operandi
  - International response
  - Statistics with key figures
  - Global impact map
- **Contact Section**: Dedicated area with provided email address
- **Interactive Elements**: 
  - Hover effects on cards
  - Animated alert banner
  - Statistic cards that scale on hover

## How to Use

1. **Save the HTML file**:
   - Copy the entire HTML code
   - Save it as `index.html`

2. **Run locally**:
   - Double-click the file to open in any web browser
   - Or use a local server:
     ```bash
     # Python 3
     python -m http.server
     
     # Node.js
     npx serve
     ```

3. **Host online**:
   - Upload to any static hosting service (see Hosting Options below)

## Hosting Options

### 1. GitLab Pages (Recommended)
1. Create a new GitLab repository
2. Add your `index.html` file
3. Go to Settings → Pages
4. Enable GitLab Pages (no configuration needed for basic HTML)
5. Your site will be available at `https://<username>.gitlab.io/<projectname>`

### 2. Cloudflare Pages
1. Sign up at [pages.cloudflare.com](https://pages.cloudflare.com/)
2. Create new project → "Direct upload"
3. Drag and drop your HTML file
4. Deploy

### 3. Vercel
1. Sign up at [vercel.com](https://vercel.com/)
2. Create new project → "Import project"
3. Drag and drop your HTML file
4. Deploy

### 4. Firebase Hosting
```bash
# Install Firebase CLI
npm install -g firebase-tools

# Login
firebase login

# Initialize project
firebase init hosting

# Deploy
firebase deploy
```

### 5. AWS S3 Static Website
1. Create S3 bucket
2. Enable static website hosting in properties
3. Upload HTML file
4. Set bucket policy for public access

## Contact Information

For immediate assistance, reporting, or victim support:
- **Email**: contactsupportinterpol@paymentrefund.info
- **Reference ID**: CTU-2023-7170

## Customization

To customize the page:
1. Update contact email in both contact sections
2. Modify statistics in the stats grid
3. Update regions in the global impact map
4. Change the reference number in footer and contact note

## Technical Details

- Single HTML file with embedded CSS and JavaScript
- Uses Font Awesome for icons (CDN)
- Responsive design with CSS Grid and Flexbox
- No external dependencies beyond Font Awesome

## License

This project is for official law enforcement use only. Distribution restricted to Interpol member countries.
