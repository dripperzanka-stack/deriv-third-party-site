# Deriv Third-Party Integration Site

A modern third-party integration website for Deriv (formerly Binary.com). This project provides a template for integrating with Deriv's trading platform.

## Features

- ✅ Responsive web design
- ✅ API integration documentation
- ✅ OAuth 2.0 authentication support
- ✅ Webhook integration
- ✅ Real-time market data access
- ✅ Secure API token management

## Quick Start

### Prerequisites
- A modern web browser
- Python 3.x or Node.js for running a local server

### Installation

1. Clone this repository:
```bash
git clone https://github.com/dripperzanka-stack/deriv-third-party-site.git
cd deriv-third-party-site
```

2. Start a local server:

**Using Python:**
```bash
python -m http.server 8000
```

**Using Node.js (http-server):**
```bash
npm install -g http-server
http-server
```

3. Open your browser and navigate to:
```
http://localhost:8000
```

## Project Structure

```
.
├── index.html              # Main landing page
├── styles/
│   └── main.css           # Stylesheet
├── js/
│   └── main.js            # Main JavaScript file
├── docs/
│   └── api-reference.html # API documentation
├── package.json           # Project metadata
├── README.md              # This file
└── .gitignore             # Git ignore file
```

## API Integration

For detailed API integration instructions, see [API Reference](docs/api-reference.html)

### Base URL
```
https://api.deriv.com/v1
```

### Authentication
```
Authorization: Bearer YOUR_API_TOKEN
```

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for any bugs or feature requests.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Support

For support and documentation, visit:
- [Deriv Developer Documentation](https://developer.deriv.com/)
- [API Reference](docs/api-reference.html)

## Disclaimer

This is a third-party integration site and is not affiliated with Deriv official products. Always refer to the official Deriv documentation for accurate API information.
