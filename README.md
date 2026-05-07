# Greenpeace Redesign

A modern, responsive web application redesign for Greenpeace Indonesia, focused on environmental advocacy and community engagement.

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0.0-blue.svg" />
  <img src="https://img.shields.io/badge/HTML5-E34F26.svg" />
  <img src="https://img.shields.io/badge/CSS3-1572B6.svg" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E.svg" />
  <a href="LICENSE">
    <img alt="License" src="https://img.shields.io/badge/license-MIT-yellow.svg" target="_blank" />
  </a>
</p>

## Description

Greenpeace Redesign is a comprehensive frontend overhaul of the Greenpeace Indonesia digital presence. The project addresses the need for a more intuitive, impactful, and accessible platform to mobilize climate action. By utilizing modern web standards and high-fidelity layouts, it provides a seamless experience for users to explore environmental issues, participate in campaigns, and contribute to global sustainability efforts.

## Features

- **Dynamic Hero Interactions** - Engaging visual storytelling with clear calls to action to drive immediate user participation
- **Comprehensive Article System** - Structured content delivery for environmental news, investigative reports, and educational resources
- **Interactive Action Hub** - Dedicated modules for current campaigns, allowing users to stay informed and get involved in local activism
- **Streamlined Donation Portal** - Optimized user journey for financial contributions, designed to maximize conversion and support
- **Rich Media Integration** - Lightbox-enabled galleries for documenting field investigations and environmental documentation
- **Full Responsive Design** - Fluid layouts that ensure accessibility across mobile, tablet, and desktop devices
- **Administrative Transparency** - Dedicated sections for privacy policies, community guidelines, and organizational information

## Tech Stack

- **Markup**: Semantic HTML5
- **Styling**: Vanilla CSS3 with Custom Properties
- **Logic**: JavaScript (ES6+), jQuery 3.6.4
- **Components**: Magnific Popup (Media Lightboxes), Font Awesome 6.4.0 (Icons)
- **Deployment**: Static Web Hosting compatible

## Installation Guide

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, or Edge)
- A local web server (optional, but recommended for testing)

### Steps

1. Clone the repository to your local machine

```bash
git clone https://github.com/reynaldiarya/Greenpeace-Redesign.git
```

2. Navigate to the project directory

```bash
cd Greenpeace-Redesign
```

3. Open the project in your preferred code editor or browser

```bash
# Using a local server (e.g., Live Server in VS Code)
# or simply opening index.html
open index.html
```

## Configuration

As a static frontend project, configuration is primarily handled within the HTML and CSS files.

### Branding Customization

**Updating the Logo:**
Replace the existing images in `assets/images/greenpeace-logo.png` and `assets/images/greenpeace-putih.png` with your organization's assets.

**Modifying Color Palette:**
The primary design tokens are managed within `assets/css/main.css`. Update the color definitions to match your branding:

```css
:root {
  --primary-green: #00d93d;
  --dark-green: #00a02a;
  --white: #ffffff;
  --text-dark: #333333;
}
```

## Usage

### Campaign Management

To add a new campaign or action, navigate to `aksi.html` and replicate the card structure. Ensure the `lightbox` class is applied to image links to trigger the Magnific Popup functionality.

### Article Publishing

New articles can be added by creating a new HTML file (e.g., `detail-artikel-4.html`) and linking it from the `artikel.html` grid. Use the `detail-artikel.html` template for consistent typography and layout.

## Project Structure

```text
/
├── assets/
│   ├── css/
│   │   └── main.css            # Primary stylesheet containing all UI tokens
│   ├── images/                 # Project assets including icons and hero images
│   └── js/
│       └── main.js             # Interaction logic and plugin initialization
├── index.html                  # Landing page and primary entry point
├── aksi.html                   # Campaigns and actions overview
├── donasi.html                 # Contribution and donation flow
├── artikel.html                # News and articles directory
├── tentang-kami.html           # Organizational history and mission
├── faq.html                    # Frequently Asked Questions
└── LICENSE                     # Project licensing information
```

## Scripts / Commands

| Action | Description |
|--------|-------------|
| Open `index.html` | Launches the main application in a browser |
| Edit `main.css` | Modifies global styling and responsive breakpoints |
| Update `main.js` | Configures popup behavior and event handlers |

## Contributing

Contributions are essential to the improvement of this platform. To contribute:

1. Fork the repository
2. Create a specific feature branch (`git checkout -b feature/improvement-name`)
3. Commit your changes with descriptive messages (`git commit -m 'Implement new navigation'`)
4. Push to your branch (`git push origin feature/improvement-name`)
5. Open a Pull Request for review

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for the full text.

## Author

Reynaldi Arya