# 🎓 Would You Rather? - College Edition

A fun, interactive web-based game featuring hilarious college dilemmas with a vibrant, modern UI. Make tough choices, track your streak, and see how the college community votes!

![Game Screenshot](https://img.shields.io/badge/Status-Live-brightgreen?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)

---

## 🎮 Features

✨ **30+ College Dilemmas** across 6 categories:
- 💘 **Love** - Relationship and crush scenarios
- 📚 **Academic** - Study life challenges  
- 🎉 **Social** - Party and friend situations
- 💼 **Career** - Job and success dilemmas
- 🍕 **Food** - Eating habits and cravings
- 🌀 **All** - Random mix of everything

🎯 **Interactive Gameplay**:
- Real-time vote percentage visualization
- Streak counter for consecutive answered questions
- Progress tracking through all questions
- Smooth animations and confetti effects
- Skip questions or answer them all

📊 **Results Screen**:
- Final statistics with questions answered/skipped
- Best streak achieved
- Personality vibe generator
- Share your results with friends

🎨 **Beautiful UI/UX**:
- Dark theme with vibrant gradients
- Responsive design (mobile-friendly)
- Smooth transitions and hover effects
- Glassmorphism design elements
- Dynamic background blobs

---

## 🚀 Quick Start

### Option 1: Play Online (Vercel)
Simply visit the deployed link to start playing immediately!

### Option 2: Run Locally
```bash
# Clone the repository
git clone https://github.com/vamsi215-git/fun-game-.git

# Open in browser
cd fun-game-
open index.html
# or
start index.html  # Windows
xdg-open index.html  # Linux
```

---

## 💻 Technology Stack

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS variables, gradients, and animations
- **Vanilla JavaScript** - No dependencies needed
- **Canvas API** - Confetti particle effects
- **Responsive Design** - Mobile-first approach

---

## 🎯 Game Rules

1. **Choose an Option**: Select between two hilarious college scenarios
2. **View Results**: See how others voted instantly
3. **Track Progress**: Monitor your streak and overall stats
4. **Skip (Optional)**: Skip any question you want (breaks your streak)
5. **Complete the Game**: Answer or skip all 30 questions
6. **See Results**: View your final stats and personality vibe
7. **Play Again**: Restart and try to beat your streak!

---

## 🛠️ Customization

### Add New Questions
Edit the `ALL_QUESTIONS` array in `index.html`:

```javascript
{ cat:'category', emoji_a:'😊', emoji_b:'😡', a:'Your Option A', b:'Your Option B' }
```

**Categories**: `love`, `academic`, `social`, `career`, `food`

### Modify Colors
Change CSS variables in the `:root` selector:
```css
:root {
  --bg: #0f0a1e;
  --a: #ff2d78;
  --b: #00d4ff;
  /* ... more variables */
}
```

### Customize Messages
Update the `toasts` array in the `choose()` function for custom feedback messages.

---

## 📱 Responsive Breakpoints

- **Desktop**: Full 2-column layout
- **Tablet**: Optimized spacing and touch targets
- **Mobile**: Single column, rotated OR badge, adjusted padding

---

## 🚀 Deployment

### Deploy on Vercel (Recommended)

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel
```

### Deploy on GitHub Pages

1. Push code to GitHub
2. Go to Settings → Pages
3. Select main branch as source
4. Your game will be live at `https://yourusername.github.io/fun-game-`

### Deploy on Netlify

```bash
# Install Netlify CLI
npm i -g netlify-cli

# Deploy
netlify deploy --prod
```

---

## 📊 Game Statistics Tracked

- **Questions Answered**: Total dilemmas you chose
- **Questions Skipped**: How many you avoided
- **Current Streak**: Consecutive answers without skipping
- **Best Streak**: Highest streak achieved
- **Personality Vibe**: Fun personality type based on play style

---

## 🎨 Design Features

- **Glassmorphism**: Frosted glass effect on cards
- **Gradient Text**: Eye-catching headings
- **Confetti Animation**: Celebration effects on choices
- **Vote Bar Animation**: Smooth percentage visualization
- **Glow Effects**: Box shadows for depth
- **Smooth Transitions**: 0.25s-0.8s easing animations
- **Toast Notifications**: Fun feedback messages

---

## 🐛 Browser Support

- ✅ Chrome (Latest)
- ✅ Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Edge (Latest)
- ✅ Mobile Browsers (iOS Safari, Chrome Mobile)

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👨‍💻 Author

Created by [vamsi215-git](https://github.com/vamsi215-git)

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 💡 Feature Ideas

- [ ] Leaderboard with localStorage
- [ ] User profiles and history
- [ ] Custom question creation
- [ ] Multiplayer/competitive mode
- [ ] Difficulty levels
- [ ] Achievement badges
- [ ] Dark/Light theme toggle
- [ ] Social media integration

---

## 📮 Feedback & Support

Found a bug? Have a suggestion? Feel free to open an [Issue](https://github.com/vamsi215-git/fun-game-/issues) or reach out!

---

**Have fun playing Would You Rather? 🎉**
