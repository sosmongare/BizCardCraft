# BizCardCraft - Digital Business Card Creator

BizCardCraft is a web application that allows users to create, customize, and share digital business cards. The application features a simple, intuitive interface for designing professional business cards with a front and back side, complete with contact information and a scannable QR code that saves directly as a contact.

## Features

### Card Design
- **Two-sided card**: Front side for contact details and back side for QR code
- **Standard business card dimensions**: Professional sizing for digital sharing or printing
- **Custom logo**: Upload your own logo or use the default leaf icon
- **Color customization**: Customize logo color, text color, and background colors

### Contact Information
- Full name and job title
- Company/organization name
- Phone number
- Email address
- Website URL
- Social media links (LinkedIn, Facebook, Instagram)
- FontAwesome icons for visual appeal

### QR Code Integration
- **vCard format**: QR code contains contact information in standard vCard format
- **Instant contact saving**: Recipients can scan and save your contact details directly to their phone
- **Dedicated vCard download**: Download your contact information as a .vcf file

### Sharing & Export Options
- **Download front**: Save the front of your card as a PNG image
- **Download back**: Save the back of your card as a PNG image 
- **Share card**: Share both sides directly (using Web Share API when available)
- **Download vCard**: Export your contact information as a standard .vcf file

### User Experience
- **Real-time preview**: See changes as you make them
- **Card flip animation**: Interactive flipping between front and back sides
- **No scrolling layout**: Everything fits in a single viewport for ease of use
- **Responsive design**: Works on desktops, tablets, and mobile devices

## Technology Stack

BizCardCraft is built using modern web technologies:

- **HTML5**: For structure and content
- **CSS3**: For styling and animations
- **JavaScript (ES6+)**: For interactivity and functionality
- **Bootstrap 5**: For responsive layout and UI components
- **FontAwesome 6**: For icons
- **QRCode.js**: For generating QR codes
- **html2canvas**: For capturing card designs as images

## Browser Compatibility

BizCardCraft works best in modern browsers:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

Some features (like Web Share API) may not be available in all browsers, but fallback mechanisms are in place.

## Installation

No installation required! BizCardCraft runs entirely in the browser. Simply open the HTML file in a web browser to start using it.

### Quick Start
1. Download the project files
2. Open `index.html` in your browser
3. Start customizing your digital business card

## Usage Guide

### Creating Your Card
1. Fill in your personal and company information in the form fields
2. Upload a logo (optional) or use the default
3. Customize colors for the logo, text, and backgrounds
4. Preview your card in real-time

### Customizing Your Card
- Click on color pickers to change various colors
- Upload a logo using the file input
- Add a custom message for the back of your card

### Previewing Your Card
- Click on the card or use the "View Back/Front" button to flip between sides
- All changes are displayed in real-time

### Sharing Your Card
- Click "Download Front" or "Download Back" to save either side as an image
- Click "Share" to use your device's native sharing options (if available)
- Click "vCard" to download your contact information as a .vcf file

## Project Structure

- `index.html`: Main HTML file containing the structure and content
- CSS styles (embedded): Contains all styling and animations
- JavaScript (embedded): Contains all functionality and interactivity (Empty at the Moment because of timing issues related to the DOM content loading)

## Future Enhancements

Potential features for future versions:
- Card templates and presets
- Additional customization options (fonts, layouts)
- Cloud saving and account integration
- QR code customization
- Print-ready PDF export


## Credits

- FontAwesome for icons
- Bootstrap for UI components
- QRCode.js for QR code generation
- html2canvas for image capture

---

*Created with ❤️ by Sospeter Mong'are*