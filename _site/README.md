# Personal Website

Welcome to my personal website repository! This website serves as a personal portfolio to display my projects, share my blog posts, learning journal and some fun stuff. It's a minimalist site built using HTML, CSS, Javascript and Jekyll.

#add image

## Running the Project Locally

To run this project on your local machine, follow these steps:

1. **Clone the Repository:**

```
git clone git@github.com:shalinis602/shalini.sinha.github.io.git
cd repository
```

2. **Check Gemfile Presence:** Ensure that you have a `Gemfile` in the root directory of your Jekyll project. If you don't have one, you can create it manually.

Example `Gemfile`:

```
source 'https://rubygems.org'
gem 'jekyll'
gem 'github-pages', group: :jekyll_plugins
```

3. **Install Bundler:** Bundler is a tool for managing Ruby gem dependencies. If you haven't installed Bundler yet, you can do so using RubyGems:

```
gem install bundler
```

4. **Install Gems:** Once Bundler is installed and you have a `Gemfile`, navigate to your project directory in the terminal and run:

```
bundle install
```

This command installs all the gems specified in your `Gemfile`, including Jekyll and any other dependencies.

5. **Run the Jekyll site locally:**

```
bundle exec jekyll serve
```

6. **Access the Local Site:**

Open your web browser and go to `http://localhost:8000`. This URL typically serves your Jekyll site locally. If port 4000 is already in use, Jekyll will assign a different port, which will be displayed in your terminal.

## Contact

Feel free to reach out via email at [shalinisinha602@gmail.com](mailto:shalinisinha602@gmail.com) or connect with me on [Twitter](https://x.com/asimov_algos)
