# AutomateMyBiz Tools Website

A modern, responsive website showcasing AI-powered productivity tools and Chrome extensions.

## Structure

```
tools/
├── index.html                    # Homepage
├── assets/
│   ├── css/
│   │   └── style.css            # Main stylesheet with brand colors
│   └── images/                  # Product screenshots and logos
├── chrome-extensions/
│   └── ai-commenting-sidekick/
│       ├── index.html          # Product page
│       └── product.css         # Product-specific styles
├── free-tools/                  # Future free tools
├── legal/
│   ├── privacy-policy.html
│   ├── terms-of-service.html   # To be created
│   ├── refund-policy.html      # To be created
│   └── legal.css
└── api/                         # Stripe integration endpoints (future)
```

## Brand Colors

- **Primary Colors:**
  - Dark Blue: `#091729`
  - Impact Blue: `#71A0E5`
  - White: `#FFFFFF`

- **Accent Colors:**
  - Light Navy: `#344970`
  - Tufts Blue: `#3E74C3`
  - Gray: `#9E9E9E`

## Features

- ✅ Modern, clean design with small font sizes
- ✅ Fully responsive layout
- ✅ SEO optimized with schema markup
- ✅ Fast loading with minimal dependencies
- ✅ Vercel deployment ready

## Deployment

1. Push to GitHub
2. Connect to Vercel
3. Deploy with these settings:
   - Framework Preset: None
   - Build Command: (leave empty)
   - Output Directory: .

## Next Steps

1. Add Terms of Service and Refund Policy pages
2. Create contact page
3. Add product demo images
4. Implement Stripe checkout integration
5. Add more free tools

## API Integration

The site is configured to proxy API calls to your backend:
- `/api/*` routes to `https://ai-commenting-sidekick.vercel.app/api/*`

This allows seamless integration with your existing backend services.