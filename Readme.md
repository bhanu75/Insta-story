# Instagram Stories Feature

A fully functional Instagram Stories clone built with React, featuring story creation, viewing, comments, likes, and a complete feed page.

## ✨ Features

### Stories
- 📸 Upload photos with captions
- 👀 View stories with auto-advance (5 seconds)
- 👆 Manual navigation (tap left/right)
- 📊 Progress bars for each story segment
- ❤️ Like stories
- 💬 Comment on stories with real-time updates
- 🔄 Smooth transitions between stories

### Feed
- 📱 Instagram-like feed with posts
- ❤️ Like posts with heart animation
- 💬 Comment on posts
- 👁️ View all comments
- ⏰ Timestamp display

### Data Persistence
- 💾 All data saved in localStorage
- 🔄 Survives page refresh
- 📦 No backend required

## 🚀 Live Demo

[View Live Demo](https://your-app.vercel.app)

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/instagram-stories.git

# Navigate to project directory
cd instagram-stories

# Install dependencies
npm install

# Start development server
npm run dev
```

## 🛠️ Tech Stack

- **React 18** - UI Framework
- **Vite** - Build Tool
- **Tailwind CSS** - Styling
- **localStorage** - Data Persistence

## 📁 Project Structure

```
instagram-stories/
├── public/
├── src/
│   ├── App.jsx          # Main application component
│   ├── index.css        # Tailwind CSS imports
│   └── main.jsx         # React entry point
├── index.html           # HTML template
├── package.json         # Dependencies
├── tailwind.config.js   # Tailwind configuration
├── postcss.config.js    # PostCSS configuration
├── vite.config.js       # Vite configuration
└── README.md           # This file
```

## 🎯 Usage

### Adding a Story
1. Click the **+** button in the top right
2. Select an image from your device
3. Add a caption
4. Click "Share to Story"

### Viewing Stories
1. Click on any story thumbnail
2. Tap left side to go back
3. Tap right side to go forward
4. Stories auto-advance after 5 seconds

### Commenting
1. Open any story
2. Click the comment icon
3. Type your comment
4. Click "Post"

### Feed Interaction
1. Scroll through the feed
2. Click heart to like posts
3. Click comment icon to view/add comments
4. All interactions are saved locally

## 🔧 Configuration

### Tailwind CSS Setup

```js
// tailwind.config.js
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,jsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

### Vite Configuration

```js
// vite.config.js
import { defineConfig } from 'vite'
import react from '@vitejs/plugin-react'

export default defineConfig({
  plugins: [react()],
})
```

## 📱 Mobile First Design

This application is designed primarily for mobile devices. For the best experience:
- View on mobile devices or use browser DevTools mobile emulation
- Optimized for touch gestures
- Responsive design adapts to screen sizes

## 🚀 Deployment

### Deploy to Vercel

1. Push your code to GitHub
2. Visit [vercel.com](https://vercel.com)
3. Click "Import Project"
4. Select your GitHub repository
5. Click "Deploy"

Vercel will automatically detect Vite and configure the build settings.

### Deploy to Netlify

1. Push your code to GitHub
2. Visit [netlify.com](https://netlify.com)
3. Click "New site from Git"
4. Select your repository
5. Build settings:
   - Build command: `npm run build`
   - Publish directory: `dist`
6. Click "Deploy site"

## 📝 Scripts

```bash
# Development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

Your Name
- GitHub: Bhanu75 (https://github.com/Bhanu75)
- Website: (https://bt12.netlify.app/)

## 🙏 Acknowledgments

- Design inspired by Instagram
- Built as a learning project for React and modern web development
- Icons from Heroicons

---

Made with ❤️ using React and Tailwind CSS
