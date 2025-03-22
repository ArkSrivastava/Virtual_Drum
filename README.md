# Virtual Drum 🥁

A simple and interactive Drum Kit web application built using HTML, CSS, and JavaScript.

## Features
- Clickable drum buttons to produce drum sounds.
- Keyboard support to play drums using keys (`W, A, S, D, J, K, L`).
- Animated button effects when played.
- Stylish gradient background with smooth animations.
- Responsive design.

## Technologies Used
- **HTML**: Structure of the web page.
- **CSS**: Styling and animations.
- **JavaScript**: Handling interactions and playing sounds.

## How to Use
### Play the Drums:
- Click on the drum pads with your mouse.
- Or use the following keys on your keyboard:
  - `w` for Tom 1
  - `a` for Tom 2
  - `s` for Tom 3
  - `d` for Tom 4
  - `j` for Snare
  - `k` for Kick Bass
  - `l` for Crash

## Installation
```sh
# Clone the repository
git clone https://github.com/your-username/drum-kit.git

# Open the project in a browser
cd drum-kit
open index.html
```

## File Structure
```
Drum Kit/
│── index.html       # The main HTML file containing the structure of the drum kit
│── styles.css       # The CSS file for styling and animations
│── index.js         # The JavaScript file handling the logic for playing sounds and animations
│── sounds/          # Directory containing the drum sound files
│── images/          # Directory containing images for the drum pads
```

## Customization
- **Add More Sounds**: You can add more drum sounds by adding new audio files in the `sounds/` directory and updating the `playSound` function in `index.js`.
- **Change Background**: Modify the `bgAnimation` keyframes in `styles.css` to change the background gradient animation.
- **Add More Drum Pads**: Add more buttons in `index.html` and update the `playSound` function to handle the new keys.

## Contributing
Feel free to fork this repository and submit pull requests for improvements.

## License
This project is open-source and available under the MIT License.

Enjoy playing the drums! 🎶

