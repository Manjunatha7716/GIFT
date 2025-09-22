# 🎉 Happy Birthday Shaffa - Interactive Love Experience 💕

A beautiful, interactive birthday website created with love for Shaffa Baby! This project features a complete love story experience with games, quizzes, and a stunning photo gallery.

## ✨ Features

### 🏠 **Welcome Page (`index.html`)**
- Beautiful animated landing page
- Floating hearts animation
- Navigation to quiz or photo gallery

### 🎮 **Love Quiz (`game.html`)**
- Interactive relationship quiz with multiple choice questions
- Real-time scoring system with streak tracking
- Smooth animations and feedback
- Challenge mode that connects to the maze
- Confetti celebrations on completion

### 🧩 **Love Maze (`maze.html`)**
- Fully interactive maze game with 3 difficulty levels
- Responsive controls (Arrow keys, WASD, or on-screen buttons)
- Power-ups: Hints, Teleport, and Slow Time
- Progressive difficulty scaling
- Victory animations and auto-redirect

### 📸 **Photo Gallery (`birthday.html`)**
- Responsive photo gallery showcasing beautiful memories
- Hover effects and smooth animations
- Personal love letter
- Navigation between all sections

## 🚀 Deploy to Netlify

### Option 1: Drag & Drop (Easiest)
1. Zip the entire project folder
2. Go to [netlify.com](https://netlify.com)
3. Drag and drop the zip file to deploy instantly

### Option 2: GitHub + Netlify (Recommended)
1. **Create a GitHub repository:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Birthday project for Shaffa"
   git branch -M main
   git remote add origin YOUR_GITHUB_REPO_URL
   git push -u origin main
   ```

2. **Connect to Netlify:**
   - Sign up/Login to [netlify.com](https://netlify.com)
   - Click "New site from Git"
   - Choose GitHub and select your repository
   - Build settings:
     - **Build command:** Leave empty
     - **Publish directory:** Leave empty (root directory)
   - Click "Deploy site"

3. **Your site will be live!** Netlify will provide a URL like `https://amazing-name-123456.netlify.app`

## 📁 Project Structure

```
Birthday/
├── index.html          # Landing page
├── game.html           # Love quiz
├── maze.html           # Interactive maze game
├── birthday.html       # Photo gallery & love letter
├── Images/             # Photo gallery images (1.jpeg to 18.jpeg)
└── README.md          # This file
```

## 🖼️ Adding Photos

**Important:** Make sure your photos are named correctly and placed in the `Images/` folder:

```
Images/
├── 1.jpeg
├── 2.jpeg
├── 3.jpeg
... up to ...
└── 18.jpeg
```

The photo gallery expects exactly these filenames. If you have different names, either:
- Rename your photos to match (1.jpeg, 2.jpeg, etc.)
- Or update the image paths in `birthday.html`

## 🎯 How to Use

1. **Start at `index.html`** - The welcome page
2. **Take the Quiz** - Test relationship knowledge
3. **Play the Maze** - Fun challenge game with different difficulties
4. **View Photos** - Beautiful memory gallery with personal message

## 🎮 Game Controls

### Maze Game:
- **Arrow Keys** or **WASD** - Move the heart
- **R** - Reset game
- **1/2/3** - Change difficulty
- **Mouse** - Click on-screen buttons

### Quiz:
- **Mouse/Touch** - Select answers
- Multiple correct answers possible per question

## 🎨 Customization

### Update Personal Messages:
- Edit the love letter in `birthday.html` (lines 376-392)
- Modify quiz questions in `game.html` (lines 466-497)
- Change captions and names throughout

### Add More Photos:
1. Add images to `Images/` folder
2. Update `birthday.html` to include new photo cards
3. Follow the existing pattern for consistency

## 🔧 Technical Details

- **Pure HTML/CSS/JavaScript** - No build process needed
- **Responsive Design** - Works on desktop and mobile
- **External Dependencies:** 
  - Canvas Confetti library (loaded from CDN)
- **Browser Support:** Modern browsers (Chrome, Firefox, Safari, Edge)

## 🌟 Features Highlights

- 🎨 Beautiful gradient backgrounds and animations
- 💕 Floating hearts animation throughout
- 🎊 Confetti celebrations
- 📱 Mobile-responsive design
- ⚡ Smooth transitions and effects
- 🎮 Interactive games with scoring
- 🖼️ Image hover effects and animations

## 💖 Made with Love

This project was crafted with love for Shaffa's birthday. Every animation, every word, and every feature was designed to create a magical experience.

**Happy Birthday, Shaffa Baby! 🎂💕**

---

## 🆘 Troubleshooting

### Images not showing?
- Check that images are in `Images/` folder (capital I)
- Verify image names match exactly (1.jpeg, 2.jpeg, etc.)
- Make sure images are uploaded to your repository

### Site not loading?
- Ensure `index.html` is in the root directory
- Check browser console for any errors
- Verify all files are uploaded correctly

### Need to update content?
- Edit the HTML files directly
- Push changes to GitHub (if using GitHub deployment)
- Netlify will automatically redeploy

---

*Created with 💖 for the most amazing person in the world!*
