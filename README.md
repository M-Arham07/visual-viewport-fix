# Mobile Keyboard Footer Fix

Fixes mobile input footers staying visible above the keyboard by combining the new  
`interactive-widget=resizes-content` meta tag, and a VisualViewport API fallback.

Works smoothly across Android, iOS, and modern browsers for React/Next.js apps.

---

## Features

- Uses native viewport resizing on Android Chrome & Firefox  
- JavaScript fallback with VisualViewport API for iOS Safari  
- Lightweight Solution, tested myself
---

## Installation

Install via npm or yarn:

```bash
npm install your-package-name
# or
yarn add your-package-name
