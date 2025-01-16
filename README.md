# Programmin in Science - Winter 2025
This website is used for the notes of the course 420-SN1.

# Test the website locally
## Windows:
1. Install [ruby](https://jekyllrb.com/docs/installation/windows/)
2. Install jekyll and the bundler:
```
gem install jekyll bundler
```

3. Clone this repo
4. Open a Terminal (or Powershell) and make sure to navigate to the root of the cloned directory.
5. Install the dependencies required by the GemFile
```
bundle install 
```
Make sure there are no errors 
6.  Run the website locally:
```
bundle exec jekyll serve
```
The link to the local website should appear in the console and it should look like:
> Server address: http://127.0.0.1:4000