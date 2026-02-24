# PDF Editor Pro

A comprehensive, client-side PDF editing web application built with React, TypeScript, and Tailwind CSS. All processing happens locally in your browser - your documents are never uploaded to any server.

![PDF Editor Pro](https://img.shields.io/badge/PDF-Editor%20Pro-blue)
![React](https://img.shields.io/badge/React-18.0+-61DAFB?logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-3178C6?logo=typescript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-3.4+-06B6D4?logo=tailwindcss)

## Features

### 1. PDF Text Editor
- Upload and view PDF documents
- Add text anywhere on the page
- Edit existing text overlays
- Adjust font size and position
- Download the edited PDF
- Page navigation and zoom controls

### 2. Image to PDF Scanner
- Convert multiple images to a single PDF
- Drag & drop image upload
- Take photos directly from camera (mobile-friendly)
- Reorder images before conversion
- Preview images before converting
- Supports JPG, PNG, GIF, WebP formats

### 3. PDF Organizer
- **Combine**: Merge multiple PDFs into one
- **Split**: Extract specific page ranges from a PDF
- **Rotate**: Rotate individual pages or all pages at once
- **Insert**: Insert one PDF into another at a specific position
- Visual preview of PDF pages
- Page navigation with zoom controls

## Tech Stack

- **Frontend**: React 18+ with TypeScript
- **Styling**: Tailwind CSS 3.4+
- **UI Components**: shadcn/ui
- **PDF Processing**: pdf-lib, react-pdf
- **Build Tool**: Vite
- **Icons**: Lucide React

## Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/pdf-editor-pro.git
cd pdf-editor-pro
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

### Building for Production

```bash
npm run build
```

The built files will be in the `dist/` directory.

## Deployment

### Deploy to GitHub Pages

1. Update `vite.config.ts` with your base URL:
```typescript
export default defineConfig({
  base: '/pdf-editor-pro/',
  // ... rest of config
})
```

2. Build the project:
```bash
npm run build
```

3. Deploy to GitHub Pages:
```bash
# Install gh-pages if not already installed
npm install --save-dev gh-pages

# Add to package.json scripts:
# "deploy": "gh-pages -d dist"

npm run deploy
```

### Deploy to Netlify

1. Build the project:
```bash
npm run build
```

2. Drag and drop the `dist/` folder to Netlify

### Deploy to Vercel

1. Install Vercel CLI:
```bash
npm i -g vercel
```

2. Deploy:
```bash
vercel --prod
```

## Usage Guide

### Editing PDF Text

1. Click on the "Text Editor" tab
2. Upload your PDF file
3. Navigate to the page you want to edit
4. Click anywhere on the PDF to place text
5. Enter your text and adjust font size
6. Click "Add Text" to apply
7. Download the edited PDF

### Converting Images to PDF

1. Click on the "Image to PDF" tab
2. Upload images by dragging & dropping or clicking "Browse"
3. On mobile, use "Take Photo" to capture images directly
4. Reorder images by clicking the arrow buttons
5. Click "Convert to PDF" to download

### Organizing PDFs

#### Combine PDFs
1. Click on the "Organize" tab
2. Upload multiple PDF files
3. Select "Combine" sub-tab
4. Arrange files in the desired order
5. Click "Combine All PDFs"

#### Split a PDF
1. Select the PDF you want to split
2. Click on the "Split" sub-tab
3. Enter the page range (start and end)
4. Click "Split PDF"

#### Rotate Pages
1. Select the PDF you want to rotate
2. Click on the "Rotate" sub-tab
3. Navigate to the page you want to rotate
4. Click "Rotate This Page" or "Rotate All Pages"

#### Insert PDFs
1. Select the target PDF
2. Click on the "Insert" sub-tab
3. Choose the PDF to insert and specify the position
4. Click the "+" button to insert

## Mobile-Friendly Features

- Responsive design that works on all screen sizes
- Touch-friendly interface
- Camera integration for scanning documents
- Optimized layouts for mobile devices
- Swipe-friendly navigation

## Privacy & Security

All PDF processing happens **locally in your browser**. Your documents are:
- â Never uploaded to any server
- â Never stored in the cloud
- â Processed entirely on your device
- â Deleted when you close the tab

## Browser Compatibility

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [pdf-lib](https://pdf-lib.js.org/) - PDF manipulation library
- [react-pdf](https://react-pdf.org/) - PDF rendering for React
- [shadcn/ui](https://ui.shadcn.com/) - UI component library
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework

## Support

If you found this project helpful, please give it a â­ on GitHub!

For issues and feature requests, please use the [GitHub Issues](https://github.com/yourusername/pdf-editor-pro/issues) page.

---

Made with â¤ï¸ by [Jasir Sayed]
