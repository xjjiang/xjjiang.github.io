# Notes on how to use jekyll

<https://xjjiang.github.io/>

## 1. Testing locally

To start the jekyll server, run:
```
bundle exec jekyll serve
```
Then, go to `http://localhost:4000` in your browser.

## 2. Making configuration changes
Configuration changes like the site title, description, email, etc.
are in `_config.yml`.

## 3. Creating new posts
To create a new posts, create a new `.md` file in the `_posts/` directory.
You can use the existing posts as an example.

## 4. Creating/editing pages
Pages can be written with html or markdown. You can use the 
`about.markdown` file in the root directory as an example.

## 5. Publishing to Github Pages.
To publish your changes:
1. Commit your changes to your local git repository.
2. Run `git push`.
