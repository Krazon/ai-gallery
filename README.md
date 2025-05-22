# Random AI Gallery

This project is a Hugo-based website designed to display a gallery of AI-generated images.

## Features

* Basic layout
* Navigation partial
* Tag cloud shortcode

## Running Locally

To run this project locally, follow these steps:

1. **Install Hugo:** If you don't have Hugo installed, download and install it from the official Hugo website: [https://gohugo.io/getting-started/installing/](https://gohugo.io/getting-started/installing/)
2. **Clone the Repository:** Clone this repository to your local machine using Git:
   ```bash
   git clone https://github.com/your-username/random-ai-gallery.git
   ```
3. **Start the Development Server:** Navigate to the project directory in your terminal and run the following command to start the Hugo development server:
   ```bash
   hugo server
   ```
   This will typically make the site available at `http://localhost:1313/`.

## Deployment

This website is automatically deployed to GitHub Pages whenever changes are pushed to the `main` branch, using a GitHub Actions workflow defined in `.github/workflows/hugo.yaml`.

## Contributing

If you would like to contribute to the project, you can do so by:

*   **Adding new images:**
    1.  Place your AI-generated images in the `static/images/` directory.
    2.  Create a new markdown file in the `content/gallery/` directory (e.g., `new-image.md`).
    3.  Add the following front matter to the markdown file, replacing the placeholder values with your image's details:
        ```markdown
        ---
        title: "Image Title"
        image: "/images/your-image-filename.png" # Path to the image in the static/images directory
        tags: ["tag1", "tag2"]
        date: YYYY-MM-DD
        ---

        Optional description of the image.
        ```
*   **Improving the theme or functionality:** Feel free to open an issue or submit a pull request if you have ideas for improving the website.

## License

[MIT](https://choosealicense.com/licenses/mit/)
