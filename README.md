# Edirom.github.io

## Contributing

If you want to contribute please consider forking the repo or at lieast sticking to the gitflow workflow describe at https://nvie.com/posts/a-successful-git-branching-model/.

For bigger changes we recommend cloning the repo to your local machine. This allows you to preview your changes before committing and filing a pull request. Once you have cloned the repo stick to the following steps:

1. make sure you have Bundler installed:
   
   ```sh
   which bundler
   ```

2. If the above command did not return a path install bundler:

   ```sh
   gem install bundler
   ```

3. Prepare the repo to be served locally

   ```sh
   bundle install
   ```

4. Serve the site locally

   ```sh
   bundle exec jekyll serve
   ```

5. Check your local verision
   Open your favourite web browser and visit http://localhost:4000
   
Whenever you modify any of the source documents jekyll will automatically rebuild the site and the changes should be visible on your browser after a short moment.