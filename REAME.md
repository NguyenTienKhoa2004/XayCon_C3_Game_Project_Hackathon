📖 OverviewWaste Warriors is an educational web-based game that addresses Vietnam's critical waste management crisis through interactive gameplay. Players learn proper waste segregation by sorting different types of waste into correct bins under time pressure.🎯 Game Concept

Genre: Puzzle/Sorting Game
Theme: Environmental Sustainability & Waste Management in Vietnam
Target Audience: Students, educators, and environmentally-conscious citizens
Platform: Web Browser (Desktop & Mobile)
🌍 Social Impact
Vietnam faces a severe waste management challenge:

27,000+ tons of solid waste generated daily
Only 10-15% recycling rate
Major cities like Hanoi and Ho Chi Minh City produce over 9,000 tons of waste per day
Improper waste disposal causes pollution, health hazards, and environmental degradation
This game aims to educate players about proper waste segregation, which can:

Reduce landfill waste by up to 60%
Create jobs in recycling industries
Decrease CO2 emissions (1.5 tons per person annually)
Improve community health and cleanliness
🚀 Instructions to Run the GameMethod 1: Direct Browser (Simplest)

Download or clone this repository
Navigate to the game_app/ folder
Double-click index.html
The game will open in your default browser
Start playing!


Method 2: Local Web Server (Recommended for Development)
bash# Using Python 3
cd game_app
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (if you have it installed)
npx http-serverThen open your browser and go to: http://localhost:8000Method 3: Live Server (VS Code)

Install "Live Server" extension in VS Code
Right-click on index.html
Select "Open with Live Server"
System Requirements

Browser: Chrome 90+, Firefox 88+, Safari 14+, Edge 90+
Internet: Not required (fully offline playable)
Storage: < 1 MB
Screen: Minimum 800x600 resolution
🎮 How to PlayGame Controls

Mouse: Click and drag waste items
Touch: Tap and drag (for mobile/tablet)
Gameplay Instructions1. Main Menu

Click "Play Game" to start
Click "How to Play" to view instructions
2. During Gameplay

Waste items fall from the top of the screen
Drag and drop each item into the correct bin
Match waste types to bin categories:

🛠️ Technology Stack
Core Technologies

HTML5: Structure and content
CSS3: Styling, animations, and responsive design
Vanilla JavaScript: Game logic and interactivity

CSS Features Used

Flexbox for responsive layouts
CSS Grid for statistics display
Linear gradients for modern aesthetics
CSS animations and transitions
Media queries for mobile responsiveness

JavaScript Features Used

DOM manipulation
Event listeners (mouse and touch)
Drag-and-drop functionality
SetInterval for timer
SetTimeout for delayed actions
Local state management
Dynamic content generation

AI Tools Used

Claude AI (Anthropic): Code generation, game logic, design suggestions
ChatGPT: Brainstorming, concept refinement
No external libraries or frameworks required!