# Letterdle - A Wordle Clone

## Disclaimer

**Letterdle** is a non-commercial, educational project created for demonstrative purposes only. This implementation is:
- Not affiliated with the original Wordle (owned by The New York Times Company)
- Not monetized or used for profit
- Not intended for commercial distribution
- Built purely for learning web development concepts

## Features

- Classic Wordle-style gameplay
- 6 attempts to guess a 5-letter word
- Color feedback system:
  - Green: Correct letter in correct position
  - Yellow: Correct letter in wrong position
  - Gray: Letter not in word
- Virtual and physical keyboard support
- Intended for desktop

## How to Play

1. Guess the 5-letter word in 6 tries
2. Type your guess using keyboard input
3. Submit with Enter/Return key
4. Colors will show how close your guess was
5. Win by guessing correctly or start a new game

## Local Setup Instructions

### Requirements
- Modern web browser (Chrome, Firefox, Safari)
- Python 3.x (for local server)

### Step-by-Step Setup

1. **Clone/Download Repository**
   ```bash
   git clone https://github.com/your-username/letterdle.git
   cd letterdle

2. **Set Up Local Server (Python 3)**
    ```bash
    # For Linux/macOS
    python3 -m http.server 8000

    # For Windows
    py -m http.server 8000

3. **Access Game**

    Open browser and visit: 

    http://localhost:8000

4. **File Structure**

    Ensure file directory contains:
    
    letterdle/
    ├── index.html
    ├── words.txt
    └── styles.css (optional if using separate CSS)

### Customization

To modify the word list:

Edit words.txt file
Add one 5-letter word per line
Save and refresh browser

### Technical Details

Frontend: Vanilla JavaScript
No backend/server storage
All processing happens client-side
Word list loaded locally from words.txt

### License

MIT License - Free for personal/educational use. Commercial use prohibited. Original Wordle concept © The New York Times Company.

### Credits

Inspired by Josh Wardle's Wordle
Developed for educational purposes
Dictionary from SGB Words (sample words)
