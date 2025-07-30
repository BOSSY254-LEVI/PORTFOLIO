Livingstone Oduor Otieno - My First web Portfolio
https://via.placeholder.com/1200x600/0d0d23/ffffff?text=Livingstone+Oduor+Portfolio
A modern, responsive portfolio showcasing my skills as an IT Expert & Developer

🔗 Live Demo: https://bossy254-levi.github.io/PORTFOLIO/#

🚀 Features
✨ Core Highlights
✅ 100% JavaScript-Free - Pure HTML/CSS for maximum performance
✅ Fully Responsive - Flawless on mobile, tablet & desktop
✅ Modern UI/UX - Clean design with subtle animations
✅ Dynamic Theme Toggle - CSS-only light/dark mode
✅ Interactive Elements - Hover effects, animated skill bars

📊 Content Sections
Professional Bio - Skills summary & career philosophy

Education Timeline - Academic journey with key achievements

Technical Skills - Visual proficiency indicators

Work Experience - Detailed role descriptions

Project Showcase - Interactive project cards

Contact Form - Easy communication channel

🛠 Tech Stack
Technology	Usage
HTML5	Semantic structure & accessibility
CSS3	Animations, grids, flexbox layouts
Bootstrap Icons	Scalable vector icons
Google Fonts	Modern typography (Poppins/Orbitron)
CSS Variables	Easy theme management
🎨 Design Philosophy
Visual Style
Color Palette: Professional purple/blue gradient theme

Typography: Clean sans-serif for readability

Spacing: Consistent padding/margin system

Animations: Subtle hover effects and transitions

Key Design Decisions
Performance First: No JavaScript = faster load times

Mobile-First: Designed for small screens first

Accessibility: Proper contrast ratios & ARIA labels

Professional Tone: Balanced personality with professionalism

📂 Project Structure
bash
portfolio/
├── index.html          # Main website file
├── assets/
│   ├── css/            # All CSS styles
│   ├── images/         # Portfolio images
│   └── fonts/          # Custom font files
├── Livingstone_cv.pdf  # Downloadable resume
└── README.md           # This documentation
🚀 Getting Started
Option 1: Fork & Customize
Fork this repository

Replace placeholder content with your information

Update color scheme in :root CSS variables

Option 2: Local Development
bash
git clone https://github.com/BOSSIE254-LEVI/portfolio.git
cd portfolio
# Open index.html in your browser
🔍 Key Code Highlights
1. CSS-Only Theme Toggle
html
<input type="checkbox" id="theme-toggle" hidden>
<label for="theme-toggle" class="theme-btn">
  <i class="bi bi-palette"></i>
</label>

<style>
  #theme-toggle:checked ~ .container {
    --primary: #5e35b1;
    --secondary: #1e88e5;
  }
</style>
2. Animated Skill Bars
css
.skill-progress {
  animation: fillBar 2s forwards;
  background: linear-gradient(90deg, var(--primary), var(--secondary));
}

@keyframes fillBar {
  from { width: 0 }
  to { width: var(--skill-level) }
}
3. Interactive Project Cards
html
<div class="project-card">
  <img src="project.jpg" class="project-img">
  <div class="project-overlay">
    <h3>Project Title</h3>
    <div class="tech-tags">
      <span>React</span>
      <span>Node.js</span>
    </div>
  </div>
</div>
📈 Why This Portfolio Stands Out
Technical Showcase

Demonstrates CSS mastery without JavaScript

Clean, maintainable code structure

Professional Presentation

Organized content hierarchy

Balanced visual elements

Recruiter-Friendly

Quick-loading contact access

Clear skills visualization

Personal Branding

Consistent design language

Authentic personality elements

📜 License
MIT License - Free for personal and commercial use

📬 Let's Connect!
LinkedIn: linkedin.com/in/livingstone-otieno

GitHub: github.com/BOSSY254-LEVI

Email: livingstoneoduory@gmail.com

