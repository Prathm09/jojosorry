# For JOJO — I'm Sorry 💗

A heartfelt message for JOJO with Vercel Web Analytics integration.

## Project Structure

This is a static HTML website with no build process required.

## Vercel Web Analytics

This project is configured with Vercel Web Analytics to track visitor interactions.

### Implementation

The analytics are implemented using Vercel's recommended approach for static HTML sites:

1. **Analytics Initialization** (in `index.html`):
   ```html
   <script>
     window.va = window.va || function () { (window.vaq = window.vaq || []).push(arguments); };
   </script>
   <script defer src="/_vercel/insights/script.js"></script>
   ```

2. **Configuration**: The `vercel.json` file is configured for static site deployment.

### Enabling Analytics

To enable Web Analytics for this project:

1. Deploy the project to Vercel
2. Go to your project dashboard on Vercel
3. Navigate to the "Analytics" tab
4. Enable "Web Analytics"
5. Analytics will start tracking once enabled

### Viewing Analytics Data

Once deployed and enabled:
- Visit your Vercel project dashboard
- Click on the "Analytics" tab
- View page views, visitor data, and other metrics

## Development

To run locally:

```bash
npm install
npm run dev
```

This will serve the site locally using `serve`.

## Deployment

Deploy to Vercel:

```bash
vercel deploy
```

Or connect your GitHub repository to Vercel for automatic deployments.

## License

ISC
