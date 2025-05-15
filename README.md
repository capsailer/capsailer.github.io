# Capsailer Website

This repository contains the source code for the [capsailer.dev](https://capsailer.dev) website.

## About Capsailer

Capsailer is a CLI tool for delivering Kubernetes applications into air-gapped (offline) environments. For more information about the project, visit:

- [Capsailer Website](https://capsailer.dev)
- [Capsailer CLI Repository](https://github.com/capsailer/capsailer-cli)

## Local Development

This website is built using [Jekyll](https://jekyllrb.com/) and hosted on [GitHub Pages](https://pages.github.com/).

### Prerequisites

- Ruby (version 2.5.0 or higher)
- RubyGems
- GCC and Make

### Setup

1. Install Jekyll and Bundler:
   ```
   gem install jekyll bundler
   ```

2. Clone this repository:
   ```
   git clone https://github.com/capsailer/capsailer.github.io.git
   cd capsailer.github.io
   ```

3. Install dependencies:
   ```
   bundle install
   ```

4. Start the local server:
   ```
   bundle exec jekyll serve
   ```

5. Open your browser to `http://localhost:4000`

## Contributing

Contributions to improve the website are welcome! Please feel free to submit a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details. 