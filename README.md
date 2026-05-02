# Bebe Ray Gardon AI Goddess Command Center

A sophisticated chat interface with integrated Vercel Speed Insights for performance monitoring.

## Features

- Interactive AI chat interface with beautiful gold-themed UI
- Responsive design for mobile and desktop
- Integrated Vercel Speed Insights for performance tracking
- Smooth animations and transitions

## Vercel Speed Insights

This project includes Vercel Speed Insights to monitor Core Web Vitals and page performance metrics.

### How It Works

The Speed Insights integration automatically tracks:
- Largest Contentful Paint (LCP)
- First Input Delay (FID)
- Cumulative Layout Shift (CLS)
- First Contentful Paint (FCP)
- Time to First Byte (TTFB)

### Viewing Analytics

Once deployed to Vercel:
1. Navigate to your project dashboard on Vercel
2. Click on "Speed Insights" in the sidebar
3. View real-time performance metrics and Core Web Vitals
4. Analyze performance trends over time

Note: Data appears after your site receives visitor traffic (typically a few days).

## Deployment

### Deploy to Vercel

1. Push this code to a Git repository (GitHub, GitLab, or Bitbucket)
2. Visit [vercel.com](https://vercel.com) and sign in
3. Click "Add New Project"
4. Import your repository
5. Vercel will automatically detect the configuration
6. Click "Deploy"

### Enable Speed Insights

Speed Insights is automatically configured in the code. To view the dashboard:
1. Go to your project on Vercel
2. Navigate to the "Speed Insights" tab
3. Enable the feature if prompted
4. Wait for visitor data to accumulate

## Local Development

```bash
# Install dependencies
npm install

# Serve the site locally
npm run dev
```

Then open http://localhost:3000 in your browser.

## File Structure

```
.
├── index.html          # Main HTML file with Speed Insights integration
├── style.css           # Styling and animations
├── script.js           # Chat functionality
├── package.json        # Dependencies including @vercel/speed-insights
├── vercel.json         # Vercel deployment configuration
└── README.md           # This file
```

## Technologies

- HTML5
- CSS3 with custom properties and animations
- Vanilla JavaScript (ES6+)
- Vercel Speed Insights for performance monitoring

## License

MIT
