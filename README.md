# Tile Drag-and-Drop Game

This project is a **Tile Drag-and-Drop Game** built using **React.js**. The game challenges users to move tiles from one column to another, following the rules of width hierarchy. The goal is to move all the tiles from the first column to the third column while making as few moves as possible.
This game allows users to drag and drop tiles across three columns. Each tile has a specific **width**, and users can only place smaller tiles on top of larger tiles. The game tracks the **number of moves** made, and once all tiles are successfully moved to the third column, a **"You Win"** message is displayed.

## Features
- **Drag-and-Drop Interface**: Users can drag tiles between columns.
- **Move Counter**: Tracks the number of moves made.
- **Win Condition**: Displays a win message when all tiles are correctly moved to the third column.
- **Responsive Design**: Tile placement adjusts dynamically based on the column and tile count.
- **Tile Hierarchy Validation**: Only smaller tiles can be placed on larger tiles.

## Technologies Used
- **React.js**: JavaScript library for building user interfaces.
- **CSS**: Styling for the UI components.
- **JavaScript**: Logic for handling drag-and-drop functionality.

- ## Getting Started

### Prerequisites
- Node.js installed on your machine.

### Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/hbasrik/Puzzle-Game/
   cd <project-directory>

2. **Install Dependencies**:
   ```bash
   npm install
   npm start
