# Roguelike Card Adventure

A sophisticated web-based roguelike card game that combines traditional poker mechanics with strategic artifact collection and enemy encounters. Built with pure HTML5, CSS3, and vanilla JavaScript.

## 🎮 [Live Demo](https://jacksonjohnallanchambers.github.io/Rougelike/)

## 🎯 Project Overview

**Roguelike Card Adventure** is a single-page web application inspired by Balatro that challenges players to defeat enemies using poker hands formed from playing cards. The game features a progressive difficulty system, collectible artifacts that modify gameplay mechanics, and smooth CSS animations for enhanced user experience.

## ⚡ Key Features

### Core Gameplay Mechanics
- **Poker-Based Combat System**: Players form traditional poker hands (Royal Flush, Straight, etc.) to deal damage
- **Strategic Card Management**: 8-card hand limit with deck shuffling and discard pile mechanics
- **Progressive Enemy Encounters**: 5 unique enemies with distinct AI patterns and special abilities
- **Artifact Collection System**: 9 unique artifacts that modify game rules and provide strategic depth

### Technical Highlights
- **Pure Vanilla JavaScript**: No frameworks or libraries - demonstrates strong foundation in core web technologies
- **Responsive CSS Design**: Flexbox-based layout with mobile-friendly responsive design
- **Advanced CSS Animations**: Keyframe animations for card movement, damage indicators, and visual feedback
- **Modular Architecture**: Clean separation of game logic, UI management, and animation systems
- **State Management**: Comprehensive game state system handling multiple game phases

### Advanced Systems
- **Dynamic Hand Evaluation**: Complex algorithm evaluating poker hands with artifact modifications
- **Animation Queue Management**: Smooth transitions and visual feedback for all player actions
- **Damage Calculation Engine**: Multi-layered system incorporating base damage, hand scores, and artifact bonuses
- **Enemy AI Patterns**: Unique attack patterns and special abilities for each enemy type

## 🏗️ Technical Architecture

### File Structure
```
├── index.html          # Main game file containing HTML, CSS, and JavaScript
├── animatedPROTO.html  # Prototype version with enhanced animations
└── README.md          # Project documentation
```

### Core Systems

#### 1. Card Management System
```javascript
// Deck creation, shuffling, and hand management
- Standard 52-card deck implementation
- Fisher-Yates shuffle algorithm
- Dynamic card drawing with discard pile recycling
```

#### 2. Combat Engine
```javascript
// Poker hand evaluation and damage calculation
- Royal Flush: 250 base damage
- Straight Flush: 150 base damage
- Four of a Kind: 100 base damage
- [Additional hands with scaling damage]
```

#### 3. Artifact System
```javascript
// Nine unique artifacts with gameplay modifications
- "Sapphire Lens": Reduces flush requirement to 4 cards
- "Berserker's Pact": 50% damage bonus with 50% damage vulnerability
- "Royal Signet": +5 damage bonus for face cards
- [Six additional artifacts with unique effects]
```

#### 4. Enemy AI System
```javascript
// Five distinct enemy types with unique mechanics
- Goblin Grunt: Basic scaling damage (150 HP)
- Slime Cube: Self-healing abilities (200 HP)
- Shadow Mage: Health drain attacks (250 HP)
- Orc Brute: High initial damage (300 HP)
- The Card Master: Final boss encounter (500 HP)
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and game structure
- **CSS3**: Advanced animations, flexbox layout, responsive design
- **JavaScript (ES6+)**: Game logic, state management, DOM manipulation
- **CSS Animations**: Keyframes for smooth visual transitions
- **Responsive Design**: Mobile-first approach with flexible layouts

## 🎨 UI/UX Features

### Visual Design
- **Dark Theme**: Professional gaming aesthetic with high contrast
- **Animated Feedback**: Visual confirmation for all player actions
- **Health Bars**: Dynamic health visualization with smooth transitions
- **Card Selection**: Interactive card highlighting with hover effects

### User Experience
- **Intuitive Controls**: Click-to-select card interface
- **Game Log**: Real-time action feedback and combat information
- **Progressive Disclosure**: Clear game state transitions and information hierarchy
- **Accessibility**: High contrast colors and clear visual indicators

## 🚀 Performance Optimizations

- **Efficient DOM Management**: Minimal DOM queries with cached element references
- **Animation Optimization**: CSS transforms for smooth 60fps animations
- **Memory Management**: Proper event listener cleanup and object pooling
- **Responsive Animations**: Hardware-accelerated CSS transforms

## 🎮 Game Flow

1. **Start Phase**: Game initialization and deck creation
2. **Battle Phase**: Card selection and combat resolution
3. **Artifact Selection**: Strategic upgrades between encounters
4. **Victory/Defeat**: End game state management

## 🔧 Development Highlights

### Code Quality
- **Modular Functions**: Clean separation of concerns
- **Consistent Naming**: Clear variable and function naming conventions
- **Error Handling**: Robust error checking and user feedback
- **Performance**: Optimized algorithms for hand evaluation and game logic

### Problem-Solving Examples
- **Animation Timing**: Coordinated multiple CSS animations with JavaScript promises
- **State Synchronization**: Complex game state management across multiple phases
- **Algorithm Design**: Efficient poker hand evaluation with modifier system
- **User Experience**: Smooth transitions between game states

## 📊 Metrics & Achievements

- **Single File Implementation**: Entire game contained in one HTML file for easy deployment
- **Zero Dependencies**: No external libraries or frameworks required
- **Cross-Browser Compatibility**: Works across modern web browsers
- **Mobile Responsive**: Fully functional on mobile devices

## 🎯 Skills Demonstrated

- **Frontend Development**: HTML5, CSS3, JavaScript (ES6+)
- **Game Development**: State management, game loops, collision detection
- **UI/UX Design**: Responsive design, animation timing, user feedback
- **Algorithm Design**: Card shuffling, hand evaluation, damage calculation
- **Code Architecture**: Modular design, clean code principles
- **Problem Solving**: Complex state management and user interaction handling

---

*This project demonstrates proficiency in modern web development technologies while showcasing game development concepts and user experience design.*
