# 🎮 Tetris Game in C# using WPF

I have done a complete implementation of the classic Tetris game built in **C#** using **Windows Presentation Foundation (WPF)**. This project demonstrates solid game logic, object-oriented principles, and graphical rendering using XAML.

---

## 📌 Features

- Classic Tetris block shapes (I, J, L, O, S, T, Z)
- Grid-based gameplay with proper rotation and drop mechanics
- Real-time user controls and game state management
- Custom assets for colored blocks
- Modular and extensible block classes

---

## 🛠️ Tech Stack

- **Frontend/UI**: WPF (XAML)
- **Language**: C#
- **IDE**: Visual Studio
- **Assets**: PNG-based tiles for block rendering

---

## 📁 Project Structure

Tetris/
├── Assets/ # PNG tiles for each Tetris block
├── App.xaml # Application-level settings
├── App.xaml.cs # App startup logic
├── AssemblyInfo.cs # Metadata for assembly
├── BlockQueue.cs # Handles block generation order
├── GameGrid.cs # Logical representation of the grid
├── GameState.cs # Core game logic (movement, collision)
├── IBlock.cs # Interface for Tetris blocks
├── JBlock.cs, LBlock.cs ... # Implementations for different Tetris shapes
├── MainWindow.xaml # GUI layout
├── MainWindow.xaml.cs # Event handling & rendering logic
├── Position.cs # Coordinate utility class
├── Tetris.csproj # Project file
├── Tetris.sln # Visual Studio solution
├── README.md # You're here 😊

---

## 🚀 Getting Started

1. **Clone the repository**

```bash
git clone https://github.com/SyedaHadiaZainab/tetris-game.git
cd tetris-game
Open in Visual Studio
Double-click on Tetris.sln to open the project in Visual Studio.
Build and Run
Press F5 or click the Start button to compile and run the game.

🎮 Gameplay Instructions
Use the arrow keys to move and rotate the blocks.

Complete horizontal lines to score points.

The game ends when blocks stack to the top of the grid.

👩‍💻 Developer
Syeda Hadia Zainab
BS Software Engineering – Fatima Jinnah Women University
📧 Email: taqviggg@gmail.com
🔗 LinkedIn: www.linkedin.com/in/syeda-hadia-zainab-a3331126b

📜 License
This project is licensed under the MIT License.
