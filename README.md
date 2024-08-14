# Get Motivation

**Get Motivation** is a simple web application that displays motivational quotes with random colors and fonts. The quotes are fetched from a local JSON file and are displayed in an `<h1>` element with a dynamic style that changes with each interaction.

## Features

- **Random Quotes**: Displays quotes fetched from a local JSON file.
- **Random Colors**: Each word in the quote is styled with a random color.
- **Random Fonts**: The entire quote is styled with a randomly selected font-family.
- **Responsive Design**: Utilizes Bootstrap for responsive layout.

## Technologies Used

- HTML
- CSS
- JavaScript (jQuery)
- Bootstrap (for responsive design)

## Setup and Installation

To get started with this project, follow these steps:

1. **Clone the Repository**

```bash
   git clone git@github.com:jmrashed/get-motivation.git
```

2. **Navigate to the Project Directory**

```bash
   cd get-motivation
```

3. **Open the `index.html` File**

   Open the `index.html` file in your preferred web browser to view the application.

## File Structure

- `index.html`: The main HTML file for the project.
- `assets/css/styles.css`: Contains the CSS styles for the application.
- `assets/fonts/stylesheet.css`: Contains font-face definitions for custom fonts.
- `assets/data/motivation.json`: JSON file containing motivational quotes.

## Customization

You can customize the application by modifying the following:

- **Quotes**: Update the `assets/data/motivation.json` file with your own quotes.
- **Fonts**: Add or change fonts in the `assets/fonts/stylesheet.css` file and update the `fontFamily` array in `index.html`.
- **Colors**: Adjust the `getRandomColor()` function in the script to change the color generation logic.

## Usage

- **Initial Load**: When the page loads, a random quote is displayed with a random color and font.
- **Update on Click**: Clicking anywhere on the body updates the quote with a new random color and font.

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries, please reach out to [jmrashed@mail.com](mailto:jmrashed@mail.com). 