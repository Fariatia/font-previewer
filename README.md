# Font Previewer

## Description
The **Font Previewer** is a simple web application that allows users to preview different font styles by typing text and selecting from a list of popular fonts. The entered text is displayed in real-time using the selected font, giving users an easy way to visualize their text in different font styles.

## Features
- **Real-time text preview**: Users can type any text, and it will be displayed instantly in the selected font.
- **Font selection**: Choose from five pre-defined font options including Arial, Georgia, Verdana, Courier New, and Times New Roman.
- **Simple, responsive design**: The application has a clean, user-friendly interface that works across different screen sizes.

## Technologies Used
- **HTML5**: For the structure and layout of the page.
- **CSS3**: To style the page, making it visually appealing and user-friendly.
- **JavaScript**: To handle the dynamic text update and font previewing functionality.

## How to Use
1. Open the `index.html` file in a modern web browser.
2. Type any text in the input box where it says "Type your text here."
3. Select a font from the dropdown menu.
4. The text you typed will be displayed in real-time with the selected font style in the preview area.

### Available Fonts:
- **Arial**
- **Georgia**
- **Verdana**
- **Courier New**
- **Times New Roman**

## Code Explanation
- **HTML**: Provides the structure of the application, including a text input field, a font selection dropdown, and an output div where the text is displayed.
- **CSS**: Styles the input elements and ensures a responsive layout with a clean, modern design.
- **JavaScript**: 
  - `updateText()`: This function is called whenever the user types text or changes the font. It dynamically updates the content of the output div with the typed text and applies the selected font style.

## Installation
1. Download or clone the repository.
2. Open the `index.html` file in any web browser to use the application.

## Future Enhancements
- Add more font options for users to choose from.
- Allow users to adjust the font size, color, and style (e.g., bold, italic).
- Implement a feature for users to upload custom fonts or download the previewed text as an image.

## License
This project is licensed under the MIT License.
