
# Prereqs

- Install Ruby (2.7+), bundler, and Xcode CLT on macOS.
- From the repo root (ctseng777.github.io).

# Install Dependencies

- gem install bundler (if needed)
- bundle config set path 'vendor/bundle'
- bundle install

# Run the Server

- Development (with live reload): bundle exec jekyll serve --livereload
- Open: http://127.0.0.1:4000/
- Production-like build: JEKYLL_ENV=production bundle exec jekyll serve

# Notes / Troubleshooting

- If links look wrong due to subpath, try: bundle exec jekyll serve --baseurl ''
- The generated site outputs to _site/; it’s recreated on each serve.
- If you hit native extension build errors, ensure Command Line Tools are installed: xcode-
  select --install
- If you prefer Docker: docker run --rm -p 4000:4000 -v "$PWD":/srv/jekyll -it jekyll/jekyll:3.9
  jekyll serve (requires Docker and image pull).
