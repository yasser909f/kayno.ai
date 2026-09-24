# 🎬 KAYNO AI - Free Video Creation Platform

Create professional ranking videos instantly. No credit card required. 100% Free Forever.

## ✨ Features

- 🎨 Beautiful modern UI
- 📹 Multi-platform support (TikTok, Instagram, YouTube)
- ✂️ Visual video trimming
- 🎯 Real-time canvas preview
- ✨ 6 animation effects
- 🆓 No watermarks
- 💾 No signup required
- 🚀 No monthly costs

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ ([Download](https://nodejs.org/))
- npm 9+ (comes with Node.js)
- Git ([Download](https://git-scm.com/))

### Installation

1. Clone this repository:
```bash
git clone https://github.com/YOUR-USERNAME/kayno-ai.git
cd kayno-ai
```

2. Install dependencies:
```bash
npm install
```

3. Start development server:
```bash
npm run dev
```

4. Open your browser and visit:
```
http://localhost:3000
```

## 📁 Project Structure

```
kayno-ai/
├── src/
│   ├── App.jsx          # Main application component
│   ├── main.jsx         # React entry point
│   └── index.css        # Global styles
├── index.html           # HTML template
├── package.json         # Dependencies
├── vite.config.js       # Vite configuration
├── tailwind.config.js   # Tailwind configuration
├── postcss.config.js    # PostCSS configuration
└── .env.local          # Environment variables
```

## 🛠️ Available Scripts

### Development
```bash
npm run dev
```
Starts the development server at http://localhost:3000

### Build
```bash
npm run build
```
Creates an optimized production build in the `dist` folder

### Preview
```bash
npm run preview
```
Previews the production build locally

## 🌍 Deployment

### Deploy to Vercel (Recommended - Free)

1. Push your code to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Import your GitHub repository
4. Vercel automatically deploys your changes

**That's it!** Your site is live! 🎉

### Environment Variables

If you add a backend, update `.env.local`:

```env
VITE_API_URL=your-backend-url
VITE_WS_URL=your-websocket-url
```

## 🎯 How to Use Kayno AI

1. **Create a Project**
   - Click "Create New Video"
   - Enter your title

2. **Edit Title**
   - Type your title in the left panel
   - Click words to highlight with colors
   - See live updates in the center preview

3. **Add Videos**
   - Right panel: Paste TikTok/Instagram/YouTube URL
   - Enter clip title
   - Set start/end times
   - Choose animation effect

4. **Generate**
   - Click "Generate Video"
   - Backend processes your video (5-10 minutes)
   - Download MP4 when ready

## 📚 Technology Stack

- **Frontend**: React 18, Vite, Tailwind CSS
- **Icons**: Lucide React
- **State Management**: React Hooks, localStorage
- **Build Tool**: Vite
- **CSS Framework**: Tailwind CSS

## 🎨 Customization

### Change Colors

Edit `src/App.jsx` and replace color classes:
- `purple` → `blue`, `red`, `green`, etc.
- `pink` → `orange`, `yellow`, etc.

### Change Logo/Brand

Find "Kayno AI" in `src/App.jsx` and replace with your brand name.

### Add New Features

Add components following the existing pattern:
1. Create new function component
2. Add to main App component
3. Style with Tailwind CSS

## 🐛 Troubleshooting

### Port 3000 already in use
```bash
npm run dev -- --port 3001
```

### Dependencies won't install
```bash
npm cache clean --force
rm -rf node_modules package-lock.json
npm install
```

### Build fails
```bash
rm -rf dist
npm run build
```

## 📝 License

MIT License - Feel free to use for personal or commercial projects

## 🤝 Contributing

Have ideas for improvements? Feel free to fork and submit pull requests!

## 📞 Support

- Check the [Documentation](./DOCS.md)
- Open an issue on GitHub
- Visit [Kayno AI Website](https://kayno.ai)

## 🎉 Getting Started

```bash
# Clone
git clone <your-repo-url>

# Install
npm install

# Run
npm run dev

# Build
npm run build

# Deploy to Vercel
# (Push to GitHub, connect to Vercel, done!)
```

---

**Created with ❤️ for creators**

**Kayno AI - Free Forever. No Watermarks. No Limits.** 🚀✨
