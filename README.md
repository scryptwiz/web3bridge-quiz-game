# 🧠 Quiz Game - Web3Bridge Challenge

A modern, interactive quiz game built with HTML, CSS, and JavaScript. Test your knowledge across various web development topics with this beautifully designed quiz application.

## 🌟 Features

- **10 Challenging Questions** covering HTML, CSS, and JavaScript fundamentals
- **30-Second Timer** for each question to add excitement
- **Real-time Scoring** with immediate feedback
- **Beautiful UI** with gradient backgrounds and smooth animations
- **Responsive Design** that works on desktop, tablet, and mobile devices
- **Progress Tracking** with visual progress bar
- **Detailed Results** showing accuracy, correct/incorrect counts
- **Glass Morphism Design** with modern visual effects

## 🚀 Demo

![Quiz Game Screenshot](https://via.placeholder.com/800x400/667eea/ffffff?text=Quiz+Game+Demo)

## 📁 Project Structure

```
quiz-game/
├── index.html          # Main HTML file with game structure
├── styles.css          # Custom CSS with modern styling
├── questions.json      # Question database (easily customizable)
├── README.md          # Project documentation
```

## 🛠️ Technologies Used

- **HTML5** - Semantic markup and structure
- **CSS3** - Custom styling with gradients, animations, and glass morphism
- **JavaScript (ES6+)** - Game logic, timers, and interactivity
- **Bootstrap 5.3** - Responsive grid system and components
- **Font Awesome 6.4** - Beautiful icons throughout the interface

## 🎮 How to Play

1. **Start the Game** - Click the "Start Quiz" button on the welcome screen
2. **Answer Questions** - Select your answer from the multiple choice options
3. **Beat the Timer** - You have 30 seconds per question
4. **Get Feedback** - See immediate results after each answer
5. **View Results** - Check your final score and accuracy at the end
6. **Play Again** - Restart anytime to improve your score

## 🔧 Installation & Setup

### Option 1: Direct Download
1. Download all files to your local machine
2. Open `index.html` in any modern web browser
3. Start playing immediately!

### Option 2: Local Server (Recommended)
```bash
# Clone or download the project
cd quiz-game

# Open the index.html file in your browser
open index.html
```

### Option 3: Live Server (VS Code)
1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

## 📝 Customizing Questions

The quiz questions are stored in `questions.json` and can be easily modified:

```json
{
    "question": "Your question here?",
    "answers": [
        "Option A",
        "Option B", 
        "Option C",
        "Option D"
    ],
    "correct": 1
}
```

- **question**: The question text
- **answers**: Array of 4 possible answers
- **correct**: Index (0-3) of the correct answer

## 🎨 Customizing Styles

The game uses a beautiful gradient background and glass morphism effects. You can customize colors in `styles.css`:

```css
body {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}

.quiz-container {
    background: rgba(255, 255, 255, 0.95);
    backdrop-filter: blur(10px);
}
```

## 📱 Browser Compatibility

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🏆 Scoring System

- **10 points** per correct answer
- **0 points** for incorrect or timed-out answers
- **Maximum score**: 100 points (10 questions × 10 points)
- **Performance levels**:
  - 90%+ : Quiz Master 🏆
  - 80%+ : Excellent 🌟
  - 70%+ : Good Job 👍
  - 60%+ : Keep Learning 📚
  - <60%  : Study More 💪

## 🤝 Contributing

Want to improve the quiz game? Here's how you can contribute:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

### Ideas for Contributions:
- Add more question categories
- Implement difficulty levels
- Add sound effects
- Create leaderboard functionality
- Add question explanations
- Implement user accounts

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Web3Bridge Quiz Game**
- Created as part of the Web3Bridge development challenge
- Built with ❤️ for learning and education

## 🙏 Acknowledgments

- **Web3Bridge** for the development challenge
- **Bootstrap** for the responsive framework
- **Font Awesome** for the beautiful icons
- **CSS Gradient** inspiration from modern web design trends

---

### 🚀 Ready to test your knowledge? [Start the Quiz!](index.html)

