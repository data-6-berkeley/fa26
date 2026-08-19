# Data 6 Fall 2026 Website

BADGES HERE

Follow the installation and usage instructions below for development work on the site and large content changes. Small content changes can easily be made on [GitHub](https://docs.github.com/en/repositories/working-with-files/managing-files/editing-files).

## Installation
### Local install

Rather than using Docker containers (and VSCode's devcontainer extension), instead we will install our project dependencies "locally".

#### Install Ruby and Bundler
**The berkeley-class-site template requires Ruby 3.3.9 or higher and bundler >= 2.6**
Install Ruby before continuing. You can check your Ruby version by running:

```bash
ruby --version
bundle --version
```

Prerequisites:

- You have everything that [Jekyll requires](https://jekyllrb.com/docs/installation/)
- You have installed [Bundler](https://bundler.io/): Run `gem install jekyll bundler`

1. [Fork](https://github.com/berkeley-eecs/berkeley-class-site/fork) the repository.
2. Clone your fork (replace `YOUR_GITHUB_USERNAME` and `YOUR_REPO` accordingly).
```
git clone git@github.com:YOUR_GITHUB_USERNAME/YOUR_REPO.git
```
3. Install dependencies:

```
cd YOUR_REPO
bundle install
```

## Usage

To run the site locally, run:

```
bundle exec jekyll serve
```

Note that if you alter `_config.yml`, you will need to rerun the above command to see the changes reflected.

## Deployment

The easiest way to deploy your site is with [GitHub Pages](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll) and the `.github/workflows/jekyll.yml` workflow included in this template.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for instructions on how to develop this template as part of your role on course staff or if you're otherwise interested in contributing to this template repository.

## License

[MIT](LICENSE)
