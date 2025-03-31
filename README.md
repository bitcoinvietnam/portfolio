## Preview a Jekyll site locally:

### **1. Install Jekyll and Bundler**

If you haven't installed Jekyll yet, run the following command (ensure you have Ruby installed):

```sh
gem install jekyll bundler
```

### **2. Navigate to Your Jekyll Project**

Go to the directory where your Jekyll site is located:

```sh
cd /path/to/your-jekyll-site
```

### **3. Install Dependencies**

If your project has a `Gemfile`, install the required dependencies:

```sh
bundle install
```

### **4. Build and Serve the Site**

Run the following command to build and preview the site locally:

```sh
bundle exec jekyll serve
```

or (if you installed Jekyll globally without Bundler):

```sh
jekyll serve
```

### **5. Open in Browser**

Once the server starts, open your browser and go to:

```
http://127.0.0.1:4000
```

By default, Jekyll serves on port `4000`, but you can specify another port if needed:

```sh
bundle exec jekyll serve --port 5000
```

### **6. Enable Live Reload (Optional)**

To automatically refresh the page when you edit files:

```sh
bundle exec jekyll serve --livereload
```

## Minimal Mistakes remote theme starter

Click [**Use this template**](https://github.com/mmistakes/mm-github-pages-starter/generate) button above for the quickest method of getting started with the [Minimal Mistakes Jekyll theme](https://github.com/mmistakes/minimal-mistakes).

Contains basic configuration to get you a site with:

- Sample posts.
- Sample top navigation.
- Sample author sidebar with social links.
- Sample footer links.
- Paginated home page.
- Archive pages for posts grouped by year, category, and tag.
- Sample about page.
- Sample 404 page.
- Site wide search.

Replace sample content with your own and [configure as necessary](https://mmistakes.github.io/minimal-mistakes/docs/configuration/).

---

## Troubleshooting

If you have a question about using Jekyll, start a discussion on the [Jekyll Forum](https://talk.jekyllrb.com/) or [StackOverflow](https://stackoverflow.com/questions/tagged/jekyll). Other resources:

- [Ruby 101](https://jekyllrb.com/docs/ruby-101/)
- [Setting up a Jekyll site with GitHub Pages](https://jekyllrb.com/docs/github-pages/)
- [Configuring GitHub Metadata](https://github.com/jekyll/github-metadata/blob/master/docs/configuration.md#configuration) to work properly when developing locally and avoid `No GitHub API authentication could be found. Some fields may be missing or have incorrect data.` warnings.
