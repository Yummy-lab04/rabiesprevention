# Rabies Awareness Initiative

An educational web application about rabies prevention and awareness. The message is clear: **100% Fatal. 100% Preventable.**

**Repository**: https://github.com/Yummy-lab04/rabiesprevention

## Features

- **Hero Section**: Immediate call-to-action for those bitten by animals
- **Data Visualization**: Interactive chart showing survival rates with/without Post-Exposure Prophylaxis (PEP)
- **Education Hub**: Tabbed interface covering transmission, symptoms, and myths vs facts
- **Prevention Schedules**: Visual timelines for both human PEP and pet vaccination protocols
- **Emergency Locator**: Tool to find nearby animal bite treatment centers
- **Interactive Quiz**: Test your knowledge about rabies prevention

## Technology Stack

- **HTML5**: Semantic markup
- **Tailwind CSS**: Utility-first CSS framework (via CDN)
- **Chart.js**: Data visualization library (via CDN)
- **Vanilla JavaScript**: No framework dependencies

## Local Development

### Using Node.js (Recommended)

1. Clone the repository:
   ```bash
   git clone https://github.com/Yummy-lab04/rabiesprevention.git
   cd rabiesprevention
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm run dev
   ```

3. Open http://localhost:3000 in your browser

### Using Python

If you prefer Python:
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

Then visit http://localhost:8000

## Deployment

### Vercel (Recommended)

This project is configured for easy deployment on Vercel.

1. The code is already in the GitHub repository: https://github.com/Yummy-lab04/rabiesprevention
2. Go to [vercel.com](https://vercel.com)
3. Click "New Project"
4. Select your GitHub repository (rabiesprevention)
5. Vercel will automatically detect and deploy your static site

#### Environment Setup
The `vercel.json` file is pre-configured for static HTML deployment.

### Other Deployment Options

#### Netlify
1. Connect your GitHub repository to Netlify at https://app.netlify.com
2. Set build command: (leave empty)
3. Publish directory: `.` (current directory)

#### GitHub Pages
1. Go to your repository settings: https://github.com/Yummy-lab04/rabiesprevention/settings
2. Scroll to "Pages" section
3. Under "Source", select "Deploy from a branch"
4. Select "main" branch and root folder
5. Your site will be available at `https://yummy-lab04.github.io/rabiesprevention/`

#### Traditional Web Server
1. Copy `rabiesprevention.html` to your web server's public directory
2. Ensure the server is configured to serve `.html` files with proper MIME types

## File Structure

```
rabiesprevention/
├── rabiesprevention.html    # Main application file
├── vercel.json             # Vercel deployment configuration
├── package.json            # Project metadata and scripts
├── .gitignore             # Git ignore rules
└── README.md              # This file
```

## Medical Disclaimer

This application is for educational and informational purposes only. It is not a substitute for professional medical advice, diagnosis, or treatment. Always seek the advice of your physician or qualified health provider with any questions you may have regarding a medical condition or animal bite. If you believe you have a medical emergency, call your doctor or emergency services immediately.

## License

MIT License

## Contributing

Educational content corrections and improvements are welcome. Please ensure any changes maintain medical accuracy.

Submit pull requests to: https://github.com/Yummy-lab04/rabiesprevention/pulls

## Resources

- [WHO Rabies Resources](https://www.who.int/health-topics/rabies)
- [CDC Rabies Information](https://www.cdc.gov/rabies/index.html)
- [Rabies Without Borders](https://rabieswithoutborders.org/)

---

**Stay Safe. Be Aware. Vaccinate.**
