# [Notes by Lenz](https://www.lenz.wiki)

<div id="overview">
    <a href="https://www.lenz.wiki/"><img src="https://img.shields.io/badge/site-lenz.wiki-informational?style=for-the-badge&labelColor=2A2A2A&color=7E97FA&logoColor=white"></a>
    <img alt="GitHub forks" src="https://img.shields.io/github/forks/ramennaut/ramennaut.github.io?style=for-the-badge&labelColor=2A2A2A&color=7CD995">
    <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/ramennaut/ramennaut.github.io?style=for-the-badge&labelColor=2A2A2A&color=7CD995">
    <img alt="GitHub License" src="https://img.shields.io/github/license/ramennaut/ramennaut.github.io?style=for-the-badge&labelColor=2A2A2A&color=7CD995">
</div>

This is the repository for my [digital space](https://www.lenz.wiki/) which is hosted on Github Pages and built using Jekyll. The site is a *very public* brain dump, since microblogs don’t seem to do the trick anymore. This space serves as a canvas for my thoughts, learnings, and experiments in a world cluttered with fleeting content -- a project born out of the need for a platform where chaos meets order.

## Project Structure
```
.
├── _data/                   - Data files for site content
├── _includes/               - Contains reusable code snippets
├── _layouts/                - Defines the structure of page templates
├── _posts/                  - Blog posts written in Markdown
├── assets/                  - Houses static assets
├── pages/                   - Contains standalone pages
│
├── _config.yml              - Central configuration file
├── .gitignore               - Lists files excluded from version control
├── CNAME                    - Specifies site access via custom domain
├── Gemfile                  - Specifies Ruby gem dependencies
├── Gemfile.lock             - Ensures consistent gem versions in builds
├── LICENSE                  - Contains the license of the project
└── README.md                - Provides an overview of the project
```

## Tech Stack
<div id="tools">
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
    <img src="https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white" alt="SASS">
    <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap">
    <img src="https://img.shields.io/badge/Ruby-CC342D?style=for-the-badge&logo=ruby&logoColor=white" alt="Ruby">
    <img src="https://img.shields.io/badge/Jekyll-CC0000?style=for-the-badge&logo=Jekyll&logoColor=white" alt="Jekyll">
    <img src="https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white" alt="Markdown">
    <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="Javascript">
    <img src="https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white" alt="Git">
    <img src="https://img.shields.io/badge/GitHub%20Pages-222222?style=for-the-badge&logo=GitHub%20Pages&logoColor=white" alt="GitHub Pages">
</div>

## Getting Started
You can go to https://www.lenz.wiki to access the wesbite; but if you ever want to run the website locally, feel free to follow the steps below.

1. **Clone the repository.**
    Use Git to clone the repository to your local machine. Open a terminal (Command Prompt or PowerShell on Windows, Terminal on macOS and Linux) and run the following command:
    ```bash
    git clone https://github.com/ramennaut/ramennaut.github.io.git
    ```
    This command downloads the project files to a folder named `ramennaut.github.io` in your current directory.
2. **Navigate to the project directory.**
    Change your current working directory to the project folder you just cloned. Run:
    ```bash
    cd ramennaut.github.io
    ```
3. **Install Jekyll and other dependencies.**
    Before proceeding, ensure you have Ruby and Bundler installed on your system. If you haven't, visit the official [Ruby download page](https://www.ruby-lang.org/en/downloads/) and the [Bundler documentation](https://bundler.io/) for installation instructions. Once Ruby and Bundler are set up, install the Jekyll site dependencies by running:
    ```bash
    bundle install
    ```
4. **Serve the site locally.**
    To view your site on a local web server, execute:
    ```bash
    bundle exec jekyll serve
    ```
    This command builds your site and hosts it locally, allowing you to view and test your site in a browser.
5. **Access the site in a web browser:**
    After the site builds, open a web browser and go to http://localhost:4000 to see your site in action. You should now be viewing your local version of the site.

If you make any changes to the site's source files, Jekyll will automatically rebuild the site, allowing you to see the updates by refreshing your browser.

## Reporting a bug
Found a bug? I'd love to squash it! Please report it by [opening an issue on the GitHub repository](https://github.com/ramennaut/ramennaut.github.io/issues) with a detailed description of the problem and steps to reproduce it. Screenshots or screen recordings are highly appreciated for a quicker resolution.

## Licence
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. This means you're free to use, modify, and distribute the project, provided you attribute back to the original source.

## Acknowledgements
This space was built in 2024 by [@ramennaut](https://github.com/ramennaut) on top of [Primer](https://github.com/pages-themes/primer). My deepest gratitude goes to the open-source community for the resources and tutorials that made this space possible. Different parts of the site were inspited by [Steph Ango](https://stephango.com/), [Tom Critchlow](https://tomcritchlow.com/), and [Derek Sivers](https://sive.rs/).

## Contact
For collaboration, support, or inquiries, feel free to reach out to me at [mail@lenz.wiki](mailto:mail@lenz.wiki).