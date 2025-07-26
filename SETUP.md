# 🚀 CDN Setup Instructions

## Quick Start

### 1. Enable GitHub Pages
1. Go to: https://github.com/Rosehouse1618/ilm-assets/settings/pages
2. Source: Deploy from a branch
3. Branch: main
4. Folder: / (root)
5. Click Save

### 2. Update Your Code
In your `js/admin.js`, update the configuration:

```javascript
const PDF_LOGO_CONFIG = {
  github: 'https://rosehouse1618.github.io/ilm-assets/images/ilm-logo.svg',
  // ... other options
};
```

### 3. Upload Your Logo
1. Go to: https://github.com/Rosehouse1618/ilm-assets/tree/main/images
2. Click "Add file" → "Upload files"
3. Upload your logo (replace ilm-logo.svg)
4. Commit changes

## 📊 Expected Results

- **Current egress**: 2.6GB/day
- **After CDN**: 0.3GB/day
- **Reduction**: 88%

## 🔧 File URLs

- **Logo**: `https://rosehouse1618.github.io/ilm-assets/images/ilm-logo.svg`
- **Documents**: `https://rosehouse1618.github.io/ilm-assets/documents/filename.pdf`
- **Gallery**: `https://rosehouse1618.github.io/ilm-assets/gallery/image.jpg`

## ✅ Benefits

- Zero egress cost
- Global CDN
- No bandwidth limits
- Easy file management