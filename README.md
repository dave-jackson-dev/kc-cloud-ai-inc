# KC Cloud AI Inc — Static Site

This repository contains a simple one-page static site for the KC Cloud AI Inc freelance consultancy. The site is ready to publish on GitHub Pages.

Preview locally
- Open `index.html` in your browser, or serve with a local static server.

Publish to GitHub Pages (basic)
1. Create a new repository on GitHub (for example `kc-cloud-ai-inc`).
2. From your local project folder, run the following commands in `cmd.exe` (Windows):

```bat
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin https://github.com\<yourusername>\<your-repo>.git
git push -u origin main
```

3. Open your repository on GitHub, go to `Settings` → `Pages`, and under `Source` choose the `main` branch and root (`/`). Save. The site will be published at `https://<yourusername>.github.io/<your-repo>/` shortly.

Notes and options
- If you prefer to publish from a `docs/` folder, move site files into `docs/` and set `Pages` source to `main` branch → `/docs`.
- For a custom domain, add a `CNAME` file with your domain and configure DNS. GitHub Pages also supports automatic HTTPS.
- The file `.nojekyll` is included to avoid Jekyll processing (useful for files that start with `_`).

If you'd like, I can:
- add a `CNAME` file for a custom domain
- create a GitHub Actions workflow to deploy automatically to `gh-pages`
- update the page content with your bio, project links, or contact email

Replace placeholders (`<yourusername>`, `<your-repo>`) with your GitHub information before pushing.
# KC Cloud AI Inc.

Welcome to the KC Cloud AI Inc. project! This is a simple one-page static website for a freelance software consultancy specializing in cloud and AI solutions.

## Project Structure

The project consists of the following files and directories:

- `index.html`: The main HTML document for the website.
- `css/styles.css`: Contains the styles for the website, defining layout, colors, and fonts.
- `js/main.js`: Includes JavaScript code for interactivity and dynamic behavior.
- `assets/README.md`: Documentation for the assets folder, detailing images, logos, and other media used in the project.
- `README.md`: This documentation file, providing an overview and instructions.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```
   cd kc-cloud-ai-inc
   ```

3. Open `index.html` in your web browser to view the website.

## Usage

This website serves as a portfolio for KC Cloud AI Inc., showcasing services and expertise in cloud computing and artificial intelligence. Feel free to explore the site and reach out for any inquiries.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please create a pull request or open an issue.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.