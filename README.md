# 🌐 IP Address Checker & Location Finder

A modern, responsive web application for checking IP addresses, finding locations, and performing domain-to-IP lookups. Built with pure HTML, CSS, and JavaScript - no frameworks required!

Also this is my site demo:
```bash
https://ip.iansite.dpdns.org/
```
## ✨ Features

### 🔍 **Your IP Detection**
- Automatically detects your current public IP address
- Displays detailed location information including:
  - Country and country code
  - Region and city
  - ZIP/postal code
  - Internet Service Provider (ISP)
  - Timezone
  - Latitude and longitude coordinates

### 📍 **IP Address Lookup**
- Look up any valid IP address to get its geographic location
- Comprehensive location data with ISP information
- Input validation to ensure valid IP format
- Error handling for invalid or private IP addresses

### 🌐 **Domain to IP Conversion**
- Convert any domain name to its corresponding IP address
- Automatic DNS resolution using Google's public DNS service
- Shows both the IP address and its location information
- Supports all valid domain formats

### 🎨 **User Experience**
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Beautiful gradient backgrounds with smooth animations
- **Tab Interface**: Easy navigation between different lookup types
- **Loading Indicators**: Clear feedback during API calls
- **Error Handling**: Informative error messages for troubleshooting
- **Keyboard Support**: Press Enter in input fields to trigger searches

## 🚀 Quick Start

### Option 1: Direct Download
1. Download the `index.html` file
2. Open it in any modern web browser
3. Start using the IP checker immediately!

### Option 2: Clone Repository
```bash
git clone https://github.com/Ianhsieh122/ipchecker.git
cd ipchecker
```

Then open `index.html` in your browser.

## 🌍 Deployment

### Cloudflare Pages (Recommended)
1. **GitHub Integration**:
   - Push the `index.html` file to your GitHub repository
   - Connect your repo to Cloudflare Pages
   - Deploy automatically (no build configuration needed)

2. **Direct Upload**:
   - Go to Cloudflare Pages dashboard
   - Upload the `index.html` file directly
   - Your site will be live in minutes!

### Other Static Hosting Platforms
This project works on any static hosting service:
- **Netlify**: Drag and drop the HTML file
- **Vercel**: Deploy directly from GitHub
- **GitHub Pages**: Push to `gh-pages` branch
- **Firebase Hosting**: Use `firebase deploy`

## 🔧 Technical Details

### APIs Used
- **IP Geolocation**: [ipapi.co](https://ipapi.co/) - Free tier provides 1,000 requests/day
- **DNS Resolution**: [Google Public DNS](https://dns.google/) - Free public DNS-over-HTTPS service

### Browser Compatibility
- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

### Performance
- **Load Time**: ~2-3 seconds (depends on API response)
- **Size**: Single HTML file (~15KB)
- **Bandwidth**: Minimal usage, only API calls

## 📝 Usage Examples

### Check Your IP
Simply load the page - your IP and location will be displayed automatically.

### Lookup an IP Address
1. Click on "IP Address Lookup" tab
2. Enter IP address (e.g., `8.8.8.8`)
3. Click "Lookup IP Information" or press Enter

### Find Domain IP
1. Click on "Domain to IP" tab
2. Enter domain name (e.g., `google.com`)
3. Click "Get Domain IP" or press Enter

## 🛠️ Customization

### Modify Colors
Edit the CSS variables in the `<style>` section:
```css
/* Primary gradient */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Accent color */
color: #667eea;
```

### Add New Features
The JavaScript is modular and easy to extend:
- Add new API endpoints
- Implement additional lookup types
- Include more location data fields

### Styling
- Uses modern CSS Grid and Flexbox
- Fully responsive design
- Hover effects and animations
- Mobile-first approach

## 🔒 Privacy & Security

- **No Data Storage**: No user data is stored locally or on servers
- **HTTPS Only**: All API calls are made over secure connections
- **No Tracking**: No analytics or tracking scripts included
- **Client-Side Only**: All processing happens in your browser

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**: `git checkout -b feature/amazing-feature`
3. **Commit your changes**: `git commit -m 'Add amazing feature'`
4. **Push to the branch**: `git push origin feature/amazing-feature`
5. **Open a Pull Request**

### Ideas for Contributions
- Add IPv6 support
- Include more geolocation data
- Add bulk IP lookup functionality
- Implement IP range calculations
- Add export functionality (CSV/JSON)

## 📊 API Limits

### ipapi.co (Free Tier)
- 1,000 requests per day
- No API key required
- Rate limit: 1 request per second

### Google DNS
- No official rate limits
- Free public service
- High availability

## 🐛 Troubleshooting

### Common Issues

**"Unable to detect IP"**
- Check internet connection
- Disable ad blockers temporarily
- Try refreshing the page

**"Domain not found"**
- Verify domain spelling
- Ensure domain has A records
- Try with/without 'www' prefix

**"API Rate Limit Exceeded"**
- Wait and try again later
- Consider using your own API key for higher limits

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🔗 Links

- **Live Demo**: [ip.iansite.dpdns.org]

## 📞 Support

If you encounter any issues or have questions:
- Check the troubleshooting section

---

**Made with ❤️ by Ian**

*Star ⭐ this repository if you found it helpful!*
