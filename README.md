# NorthWest Arkansas Resources

## Introduction


#### Features

- Automatically changes from dark/light modes depending on the OS settings.
- Easy integration with Google Analytics.
- Generates XML sitemap and RSS Atom feed.
- jekyll-seo-tag to add metadata tags for search engines and social networks to better index and display your site's content.
- Full markdown support: code blocks and tables are automatically bootstrap components.

## Installation

Clone this repo:

    $ git clone https://github.com/psibir/nwa-resources.git

If you haven't already, install bundler:

    $ gem install bundler

And then execute:

    $ bundle install

Serve the site:

    $ bundle exec jekyll serve

# Installation with Github Pages

After cloning the repo, checkout to the gh-pages branch.

    $ git checkout gh-pages && git pull

In the directory:

    $ bundle install

For local development:

    $ bundle exec jekyll serve

After tweaking with it, you can publish the site. Under your repository name, click Settings.

In the left sidebar, click Pages.

To see your published site, under "GitHub Pages", click your site's URL.

For a more detailed guide, visit this guide by Github: https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll

## Usage

### First things first: \_config.yml

First, you should change data in \_config.yml to the appropriate information such as your social links for the footer icons, avatar for navbar logo, title and name of the site, and more crucial information.

### Adding content

In order to add permanent pages, add in similar fashion to about.md and portfolio.md and add apppropriate data to \_data/navigation.yml.

In order to add blog posts, add in similar fashion to \_posts/2021-07-16-this-post-demonstrates-post-content-styles.md.

### Custom style changes

If you wish to add custom styling through SCSS or CSS, you can add or edit \_sass/main.scss.

### Custom domains with Github Pages

Follow this simple guide: https://medium.com/@xiang_zhou/how-to-add-custom-domain-to-your-jekyll-blog-provided-that-you-built-your-site-using-github-6e1c8bf20afe

## Contributing

Bug reports and pull requests are welcome on GitHub

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
