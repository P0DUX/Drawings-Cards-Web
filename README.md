# Web Cards with p5.js
#### Author: Bocaletto Luca

This project is a collection of examples designed to demonstrate how to draw on the web using HTML5, CSS3, JavaScript, and the p5.js library. It also shows how to create cards that combine artistic visuals with preset game stats—such as Attack (Atk), Defense (Dif), Health (HP), and Magic (MP)—making them perfect for prototyping game characters or collectible card designs.

## Project Overview

The focus of this project is twofold:

1. **Web Drawing with p5.js:**  
   Using p5.js (included via a CDN), we create creative, vector-based drawings directly in the browser. The examples include drawings of:
   - A human face masked as a dog face (Mandogs)
   - A pipistrello (bat) face  
   The code illustrates how you can create intricate details (like eyes, ears, and facial elements) using basic geometric shapes, curves, and custom design logic.

2. **Game Card Prototyping:**  
   In addition to the artwork, each card presents preset values for game-related stats (Atk, Dif, HP, MP). This concept is useful not only for visual design but also for prototyping game mechanics, where each card can represent a character or a unique collectible with defined abilities.  
   
   In the **Mandogs** example, for instance, the card displays:
   - **Atk:** 45  
   - **Dif:** 30  
   - **HP:** 120  
   - **MP:** 40

## Technologies Used

- **HTML5/CSS3/JavaScript:** The core web technologies ensuring broad compatibility and responsiveness.
- **p5.js:** A JavaScript library for creative coding, used here to handle all the drawing and animation on the canvas.  
- **Bootstrap 5:** For layout and styling, especially to create modern, responsive card components.

## Project Structure

- **Index Files (e.g., `mandogs.html`):**  
  Each page (or card) is designed in a self-contained HTML file. For example, `mandogs.html` contains a card that displays the "Masked Dog Face (Mandogs)" with its associated stats.
  
- **Cards Data (Potential Extension):**  
  In a further iteration, the project can be extended to load card data from a JSON file (e.g., `cards.json`). This would allow the game cards to be dynamically generated and updated without altering the core HTML code.

## How to Run

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/your-repository-name.git
   cd your-repository-name
   ```

2. **Open the HTML Files:**  
   Open any of the provided HTML files (for example, `mandogs.html`) in your preferred web browser. Since the project uses a CDN for external libraries (e.g., Bootstrap and p5.js), no additional setup is required on your local machine.

## Future Enhancements

- **Dynamic Data Loading:**  
  Use a JSON file (e.g., `cards.json`) to store card stats and details and generate pages dynamically.
  
- **Interactivity and Animations:**  
  Add further interactive elements and animations to make the cards more engaging. For example, cards could flip or animate when hovered over.

- **Integration with a Game Framework:**  
  To prototype a full game, these cards could later be integrated with a JavaScript-based game engine.

## Contributing

Contributions are welcome! If you have ideas for new drawing examples, additional card features, or improvements in interactivity, feel free to open an issue or submit a pull request.

## License

This project is open source and available under the [GPL License](LICENSE).

---

Feel free to explore the examples, experiment with the p5.js code, and adapt the card designs to suit your game or creative project!
```
