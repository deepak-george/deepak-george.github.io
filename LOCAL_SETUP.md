# local setup 
https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/
## install ruby
DO NOT  install ruby from snap. ran into lots of issues
```
$ sudo apt-get install ruby-full
```
https://www.ruby-lang.org/en/documentation/installation/#apt:~:text=apt%20(Debian%20or%20Ubuntu)

## install jekyll & bundler
https://jekyllrb.com/docs/

```
gem install jekyll bundler
```
## run bundle
```
bundle
bundle add webrick #https://github.com/jekyll/jekyll/issues/8523
```
## serve website on 
this will throw errors that you can fix
```
bundle exec jekyll serve
```

# Posting 
https://mmistakes.github.io/minimal-mistakes/docs/posts/
refer https://mmistakes.github.io/mm-github-pages-starter/blog/welcome-to-jekyll/ to learn how to post
# Reference
https://github.com/justinrummel/jr.com-mm/blob/jr-branch/_config.yml
https://github.com/chriskhanhtran/minimal-portfolio
https://chriskhanhtran.github.io/about/
