# Random Background Color Changer

Welcome to the **Random Background Color Changer** repository! This project is a simple web application written in HTML, CSS, and JavaScript. The application changes the background color of the webpage to a random color with the click of a button.

## Features

- **Random Color Generation**: Generates a random background color with each button click.
- **Interactive Interface**: Simple button to trigger the color change.
- **Lightweight and Fast**: Minimal code and dependencies for quick performance.
- **Responsive Design**: Works seamlessly on both desktop and mobile devices.

## Technologies

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla JS)

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/random-background-color-changer.git
   cd random-background-color-changer
   ```

2. **Open the index.html file**:
   - You can open the `index.html` file directly in your web browser to use the Random Background Color Changer.

## Usage

1. Open the Random Background Color Changer in your web browser.
2. Click the button to change the background color to a random color.

## Project Structure

- `index.html`: The main HTML file for the Random Background Color Changer.
- `style.css`: CSS file for styling the application.
- `script.js`: JavaScript file for handling the color change functionality.

## Example

Here’s a simple example of the JavaScript code used to change the background color:

```javascript
// Example of changing the background color
document.getElementById('colorButton').addEventListener('click', function() {
  document.body.style.backgroundColor = getRandomColor();
});

function getRandomColor() {
  const letters = '0123456789ABCDEF';
  let color = '#';
  for (let i = 0; i < 6; i++) {
    color += letters[Math.floor(Math.random() * 16)];
  }
  return color;
}
```

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to submit a pull request. Please ensure your changes align with the project goals and maintain code quality.

## License

This project is licensed under the MIT License – see the [LICENSE.md](LICENSE.md) file for details.
