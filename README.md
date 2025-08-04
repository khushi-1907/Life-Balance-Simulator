# ⚖️ Life Balance Calculator – Visualize Your Priorities in Real-Time

The **Life Balance Calculator** is a fun, interactive single-page web application designed to help users reflect on their priorities across four core areas of life: **Love**, **Friends**, **Money**, and **Cars**. With dynamic sliders, animated feedback, and customized personality assessments, this app offers both entertainment and introspection.

---

## 🌟 Features

### 🎛️ Interactive Interface
- Four intuitive sliders to represent balance in **Love**, **Friends**, **Money**, and **Cars**
- Real-time percentage updates as sliders move
- Animated character emoji reflects your current balance profile
- Hover effects and touch-friendly design

### 🎨 Visual Design
- Clean, modern layout with soft gradients and card-based UI
- Distinctive color palettes for each life category
- Floating heart animations when Love is prioritized ❤️
- Fully responsive design (mobile, tablet, desktop)
- Dark mode support via `prefers-color-scheme`

### 🧠 Dynamic Analysis
- 20 predefined personality profiles based on slider values
- Each profile includes a unique title and playful feedback
- Algorithm updates personality type live as you adjust your balance

### 🔁 Interactive Elements
- **Randomize** button generates spontaneous balance profiles
- **Share** button allows users to share their result via:
  - Web Share API (on supported devices)
  - Fallback to clipboard copy
- Smooth animations, transitions, and dynamic updates

---

## 📊 Life Balance Profiles (Examples)

| Profile Name             | Focus Area(s)               |
|--------------------------|-----------------------------|
| 💘 Love Guru              | High love                   |
| 👯 Social Butterfly       | High friends                |
| 💰 Money Bags             | High money                  |
| 🚗 Car Enthusiast         | High cars                   |
| 💑 Power Couple           | Love + Money                |
| 🧭 Adventure Leader       | Friends + Cars              |
| 🧠 Life Architect         | Balanced all-around         |
| 🎢 Dynamic Innovator      | Extreme imbalance           |
| 🧘 Essentialist           | All values low              |
| 🚀 Peak Performer         | All values high             |
| 👔 Career Professional    | Strong money focus          |
| 🎥 Social Influencer      | Friends + Cars              |
| 💍 Strategic Partner      | Love + Money                |
| 🏎️ Automotive Investor    | Cars focus                  |
| 📈 Wealth Builder         | Money + low social values   |
| 🫶 Relationship Architect | Love + Friends              |
| 🌍 Experience Seeker      | Friends + Cars              |
| 🌹 Romantic Idealist      | Love-focused, low money     |
| 💼 Network Strategist     | Friends + Money             |
| 💎 Lifestyle Connoisseur  | Money + Cars                |

---

## 🛠️ Tech Stack

- **HTML5** – semantic, accessible structure
- **CSS3** – modern styling with variables, gradients, and `backdrop-filter`
- **Vanilla JavaScript** – dynamic logic, interactivity, and profile matching
- **Google Fonts** – “Inter” for clean typography
- **Font Awesome** – for category and UI icons

---

## 📱 Mobile-Optimized UX

- Sliders work perfectly on touch devices
- Layout adapts fluidly to different screen sizes
- Smooth animations, swipe-safe design, and fast performance

---

## 🚀 Getting Started

### 🔧 Run Locally

1. **Clone the repository**
   git clone https://github.com/yourusername/life-balance-calculator.git
cd life-balance-calculator
open index.html   # macOS
start index.html  # Windows
xdg-open index.html # Linux
Alternatively, use VS Code’s Live Server or Python HTTP server:
python -m http.server
Visit http://localhost:8000 in your browser.

🎨 Customization
Color Scheme: Modify CSS variables in the :root selector
Add Profiles: Edit the profiles array in the JavaScript section
Text Feedback: Customize messages per profile for a unique tone
Icons/Emoji: Update profile visuals for even more personality!

🤝 Contributing
Contributions are welcome!
Fork this repo
Create your branch: git checkout -b feature/your-feature
Commit changes: git commit -m "Add new feature"
Push to your branch: git push origin feature/your-feature
Open a Pull Request

📄 License
This project is licensed under the MIT License.

💬 Contact
Created with ❤️ by Ruchi – @yourusername
If you have feedback, ideas, or want to collaborate, feel free to reach out!
