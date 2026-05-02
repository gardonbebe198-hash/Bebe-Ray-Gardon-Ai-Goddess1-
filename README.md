# Bebe AI Goddess - AI Command Center

A beautiful, interactive AI chatbot interface with Vercel Web Analytics integration.

## Features

- 🎨 Stunning gold-themed UI with animated backgrounds
- 💬 Interactive chat interface
- 📊 Vercel Web Analytics for visitor tracking
- 📱 Responsive design for all devices

## Getting Started

### Local Development

1. Install dependencies:
```bash
npm install
```

2. Run the development server:
```bash
npm run dev
```

3. Open your browser and navigate to `http://localhost:3000`

## Vercel Deployment

This project is ready to deploy to Vercel:

1. Push your code to a Git repository (GitHub, GitLab, or Bitbucket)
2. Import the project in Vercel
3. Enable Web Analytics in your Vercel dashboard:
   - Go to your project settings
   - Navigate to the "Analytics" tab
   - Click "Enable Web Analytics"
4. Deploy your project

After deployment, Vercel Web Analytics will automatically track:
- Page views
- Visitor sessions
- Geographic data
- Referral sources

## Project Structure

```
.
├── index.html        # Main HTML file with Analytics integration
├── style.css         # Styling for the application
├── script.js         # Interactive chat functionality
├── package.json      # Project dependencies and scripts
└── README.md         # This file
```

## Analytics Configuration

Vercel Web Analytics is integrated using the HTML5 method as documented in the [Vercel Analytics Quickstart Guide](https://vercel.com/docs/analytics/quickstart).

The analytics script is added to `index.html`:
```html
<script>
  window.va = window.va || function () { 
    (window.vaq = window.vaq || []).push(arguments); 
  };
</script>
<script defer src="/_vercel/insights/script.js"></script>
```

## License

ISC
