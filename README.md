# Iframe Tester

Iframe Tester is a free online tool for iframe testing, code generation, and live preview. It's perfect for webmasters and designers to easily embed and customize iframes on any webpage.

## Features

- Test URL compatibility for iframe embedding
- Generate iframe code with customizable options
- Live preview of iframe content
- Responsive design for various screen sizes
- Educational content about iframes and their usage

## Getting Started

### Prerequisites

- Node.js (version 12 or higher)
- npm (comes with Node.js)

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/your-username/iframe-tester.git
   ```

2. Navigate to the project directory:
   ```
   cd iframe-tester
   ```

3. Install dependencies:
   ```
   npm install
   ```

4. Start the Tailwind CSS build process:
   ```
   npx tailwindcss -i ./src/css/input.css -o ./src/css/output.css --watch
   ```

5. Open `src/html/index.html` in your web browser to use the application.

## Usage

1. Enter a URL in the input field.
2. Click "Test iframe" to check if the URL can be embedded.
3. If successful, you'll see a preview of the iframe.
4. Use the customization options to adjust the iframe properties.
5. Copy the generated iframe code for use in your own projects.

## Development

This project uses Tailwind CSS for styling. To make changes to the styles:

1. Edit the `src/css/input.css` file or add Tailwind classes directly in the HTML.
2. The Tailwind CLI will automatically rebuild the `output.css` file.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- [Tailwind CSS](https://tailwindcss.com/) for the utility-first CSS framework.
- [Inter font](https://fonts.google.com/specimen/Inter) for the typography.
