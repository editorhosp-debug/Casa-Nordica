# Casa Nórdica na Montanha - Digital Guide

## Overview
This is a static HTML website serving as a digital guest guide for "Casa Nórdica na Montanha" (Nordic House in the Mountain), a vacation rental property. The site is entirely in Portuguese and provides information for guests including:

- About the property
- WiFi information
- House rules
- Tourist attractions
- Restaurants
- Contact information
- Emergency information
- Local tips

## Project Structure
```
.
├── index.html           # Main homepage with navigation grid
├── bem-vindos.html      # Welcome page
├── contato.html         # Contact information
├── dicas.html           # Tips for guests
├── emergencia.html      # Emergency information
├── pontos-turisticos.html # Tourist attractions
├── regras.html          # House rules
├── restaurantes.html    # Restaurant recommendations
├── sobre.html           # About the property
├── wifi.html            # WiFi information
├── logo.jpeg            # Property logo
└── server.py            # Simple Python HTTP server
```

## Technology Stack
- Pure HTML/CSS (no build system required)
- Python SimpleHTTPServer for local development
- Static deployment

## Running Locally
The site is served via a Python HTTP server on port 5000:
```bash
python server.py
```

## Deployment
Configured for static deployment serving the root directory.
