# ess-chatbot

Brand Builders Academy AI Assistant - A simple static web page that provides access to the AI chatbot for authenticated users.

## Features
- Email-based authentication via backend API
- Dynamic chat URL loading based on user access
- Chrome extension download option
- Responsive design

## Local Development

### Quick Start
1. Open `index.html` in your browser directly from the file system
2. The page will work with full functionality

### With Local Server (Optional)
For better development experience:

```bash
# Python 3
python -m http.server 8000 latest

# Python 2  
python -m SimpleHTTPServer 8000

# Node.js (if you have http-server installed)
npx http-server -p 8000

# Then open: http://localhost:8000
```

## Architecture
- **Static Frontend**: Single HTML file with embedded CSS/JS
- **Backend API**: External service at `https://ess-backend-api.vercel.app`
  - `/api/get-chat-config` - Authenticates users and returns chat URL
- **No server required** - Pure static site

## Deployment Options
This is a static site that can be deployed to:
- GitHub Pages
- Netlify
- Vercel (static)
- Any static hosting service
- CDN

Simply upload the files and configure your domain.
# ess-opengpt-page
