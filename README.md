# Links Page

Links Page is an open-source project designed to provide a clean, fast, and easy-to-use landing page where you can centralize all your important links. Whether you're a content creator, a business, or an individual, this project allows you to share your social media profiles, portfolio, blog posts, online store, and more, all from a single, customizable page.

## Features

*   **Clean and Responsive Design:** Optimized for both desktop and mobile devices.
*   **Easy Customization:** Easily change colors, fonts, and add/remove links.
*   **SEO Friendly:** Includes meta tags for better search engine visibility and social media sharing.
*   **Open Source:** MIT License, allowing for free use, modification, and distribution.
*   **Lightweight:** Built with pure HTML, CSS, and JavaScript (no heavy frameworks).
*   **Social Media Integration:** Dedicated section for your social media profiles.

## Getting Started

### Prerequisites

To use this project, you only need a web browser. To modify it, a text editor is sufficient.

### Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/gmasson/links-page.git
    ```

2.  **Navigate to the project directory:**

    ```bash
    cd links-page
    ```

3.  **Open `index.html` in your browser:**

    Simply double-click `index.html` or open it with your preferred web server.

## Customization

### HTML (`index.html`)

*   **Profile Picture:** Replace `assets/img/example.jpg` with your own image.
*   **Profile Name and Description:** Edit the `<h1>` and `<p>` tags within the `<header>` section.
*   **Social Links:** Modify the `href` attributes and `title` tags in the `<section class="social-links">` for your social media profiles. You can also change the icons by replacing the `src` attribute of the `<img>` tags with other icons from the `assets/img/icons/` directory or your own SVG icons.
*   **Main Links:** In the `<section class="links">`, update the `href` and `title` attributes for your main links. Change the `<span>` text to reflect the link's purpose. Icons can be changed similarly to social links.
*   **SEO and Meta Tags:** Update the `<title>`, `<meta name="description">`, `<meta name="keywords">`, and Open Graph/Twitter meta tags in the `<head>` section to match your content.

### CSS (`assets/css/links-page.css`)

*   **Colors and Fonts:** Modify the CSS variables defined in the `:root` selector at the top of `links-page.css` to change the theme colors and font family.
*   **Layout and Styling:** Adjust other CSS rules to fine-tune the appearance of your links page.

## Contributing

We welcome contributions to the Links Page project! If you have suggestions for improvements, new features, or bug fixes, please feel free to:

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/YourFeature`).
3.  Make your changes.
4.  Commit your changes (`git commit -m 'Add some feature'`).
5.  Push to the branch (`git push origin feature/YourFeature`).
6.  Open a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or suggestions, please open an issue on the GitHub repository.

