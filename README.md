DevSecOps Pipeline Implementation for Tic Tac Toe Game

Features
🎮 Fully functional Tic Tac Toe game
📊 Score tracking for X, O, and draws
📜 Game history with timestamps
🏆 Highlights winning combinations
🔄 Reset game and statistics
📱 Responsive design for all devices
Technologies Used
React 18
TypeScript
Tailwind CSS
Lucide React for icons
Project Structure
src/
├── components/
│   ├── Board.tsx       # Game board component
│   ├── Square.tsx      # Individual square component
│   ├── ScoreBoard.tsx  # Score tracking component
│   └── GameHistory.tsx # Game history component
├── utils/
│   └── gameLogic.ts    # Game logic utilities
├── App.tsx             # Main application component
└── main.tsx           # Entry point
Game Logic
The game implements the following rules:

X goes first, followed by O
The first player to get 3 of their marks in a row (horizontally, vertically, or diagonally) wins
If all 9 squares are filled and no player has 3 marks in a row, the game is a draw
Winning combinations are highlighted
Game statistics are tracked and displayed
Getting Started
Prerequisites
Node.js (v14 or higher)
npm or yarn
Installation
Clone the repository:

git clone https://github.com/yourusername/devsecops-demo.git
cd devsecops-demo

Install dependencies:
npm install
# or
yarn
Start the development server:

npm run dev
# or
yarn dev
Open your browser and navigate to http://localhost:5173

Building for Production
To create a production build:

npm run build
# or
yarn build
The build artifacts will be stored in the dist/ directory.
