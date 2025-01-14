# City Skyline Project

This project creates a city skyline using HTML and CSS. The page includes background and foreground buildings with various styles and colors.

## Project Structure
- `index.html`: Contains the HTML structure of the city skyline.
- `styles.css`: Contains the CSS styles for the city skyline.

## HTML Structure
The HTML file includes the following elements:
- `div.background-buildings`: A div containing the background buildings.
  - `div.bb1`: A background building with windows.
  - `div.bb2`: A background building with a triangular top.
  - `div.bb3`: A background building with repeating linear gradients.
  - `div.bb4`: A background building with multiple windows.
- `div.foreground-buildings`: A div containing the foreground buildings.
  - `div.fb1`: A foreground building with a triangular top.
  - `div.fb2`: A foreground building with windows.
  - `div.fb3`: A foreground building with multiple sections and windows.
  - `div.fb4`: A foreground building with a slanted top and windows.
  - `div.fb5`: A foreground building with repeating linear gradients.
  - `div.fb6`: A foreground building with repeating linear gradients.

## CSS Styles
The CSS file includes styles for the following elements:
- `:root`: Defines CSS variables for building and window colors.
- `*`: Resets box-sizing.
- `body`: Sets the height, margin, and overflow properties.
- `.background-buildings`, `.foreground-buildings`: Styles for the building containers, including width, height, display, alignment, and position.
- `.building-wrap`: Styles for wrapping building elements.
- `.window-wrap`: Styles for wrapping window elements.
- `.sky`: Styles for the sky background using radial gradients.
- `.bb1`, `.bb2`, `.bb3`, `.bb4`: Styles for the background buildings, including width, height, and background properties.
- `.fb1`, `.fb2`, `.fb3`, `.fb4`, `.fb5`, `.fb6`: Styles for the foreground buildings, including width, height, and background properties.
- `@media (max-width: 1000px)`: Media query to adjust styles for smaller screens.

## How to Run
1. Clone the repository or download the project files.
2. Open `index.html` in your web browser to view the city skyline.

