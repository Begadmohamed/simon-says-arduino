# Simon Says Game 🎮

This project implements an interactive **Simon Says** game using **Arduino**. The game simulates the classic memory game where players must follow an LED sequence by pressing buttons. It incorporates LED sequences and button inputs to provide an engaging and interactive experience.

---

## Features 🌟

1. **LED Sequence Generation**
   - Randomly lights up LEDs in a specific order.
   - Each sequence becomes longer as the player progresses.

2. **User Input**
   - The player must replicate the LED sequence by pressing the corresponding buttons.
   - The game verifies the input and provides feedback.

3. **Game Progression**
   - The difficulty increases as the player successfully follows each sequence.
   - The game resets if the player makes an error.

---

## How It Works ⚙️

1. **Sequence Generation:**
   - The Arduino generates a random sequence of LEDs.
   - Each LED flashes in the sequence, with delays between each flash.

2. **User Input:**
   - The player presses buttons to match the generated sequence.
   - The sequence is compared to the player's input for accuracy.

3. **Game Feedback:**
   - Correct input results in the next sequence being generated.
   - Incorrect input triggers a game over message and resets the sequence.

---

## Components Used 🔧

- **Arduino Uno** or compatible microcontroller.
- **LEDs** (for visual display of sequence).
- **Buttons** (for user input).
- **Resistors** (to limit current to LEDs and buttons).
- **Breadboard and Jumper Wires** (for circuit setup).

---

## How to Play 🎮

1. **Set Up the Circuit:**
   - Connect the LEDs and buttons to the Arduino according to the schematic provided.

2. **Upload the Code:**
   - Open the Arduino sketch in the Arduino IDE.
   - Upload the code to the Arduino board.

3. **Start the Game:**
   - The game will start by lighting up a random LED sequence.
   - Press the corresponding buttons to replicate the sequence.
   - If you make a mistake, the game will reset.

---

## Demonstration 🔍

### Online Simulation:
You can simulate the game on **TinkerCAD**:  
[Click here to access the simulation](https://www.tinkercad.com/things/kIUK6lmU5mc-simon-game-by-bigm?sharecode=4MoL8ZVL_CJZYoJ3RF2SPYVDVKOY-9iJmoqPk28ZE6I)

---

## Learning Outcomes 📚

- Gained practical experience with **Arduino programming**.
- Learned how to interact with **LEDs** and **buttons** in a hardware environment.
- Developed a deeper understanding of **game logic** and **feedback mechanisms** in embedded systems.

---

## Future Improvements 🔮

- Increase the number of LEDs and buttons for more complex sequences.
- Add an **LCD screen** to display game information and scores.
- Implement **sound effects** to enhance the user experience.

---

## Author ✍️

**Begad Mohamed**  
- 📫 Email: es-begad.mohamed2027@alexu.edu.eg  
- 🌐 [LinkedIn](https://linkedin.com/in/begad-mohamed)
